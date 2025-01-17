# Mesh diagnostics

<a id="mesh-statistics-and-quality"></a>

## Mesh statistics and quality

You can use a set of quality metrics to measure the mesh quality. The [`SurfaceSearch`](../api/_autosummary/ansys.meshing.prime.SurfaceSearch.md#ansys.meshing.prime.SurfaceSearch)
and [`VolumeSearch`](../api/_autosummary/ansys.meshing.prime.VolumeSearch.md#ansys.meshing.prime.VolumeSearch) classes allow you to verify surface and volume mesh quality, respectively.

<a id="connectivity-checks"></a>

### Connectivity checks

Surface diagnostics are important prior to generating a volume mesh. You can get a surface diagnostic summary by using
the [`SurfaceSearch.get_surface_diagnostic_summary()`](../api/_autosummary/ansys.meshing.prime.SurfaceSearch.get_surface_diagnostic_summary.md#ansys.meshing.prime.SurfaceSearch.get_surface_diagnostic_summary)
method. The [`SurfaceDiagnosticSummaryParams`](../api/_autosummary/ansys.meshing.prime.SurfaceDiagnosticSummaryParams.md#ansys.meshing.prime.SurfaceDiagnosticSummaryParams) class provides for
diagnosing surface connectivity for the given scope and controls:

* Duplicate faces
* Free face edges
* Multi face edges
* Self intersections

This code determines if a wrap surface is closed:

```python
# Check if wrap surface is closed
scope = prime.ScopeDefinition(model=model, part_expression="wrap")
diag = prime.SurfaceSearch(model)

diag_params = prime.SurfaceDiagnosticSummaryParams(
    model,
    scope=scope,
    compute_duplicate_faces=True,
    compute_free_edges=True,
    compute_multi_edges=True,
    compute_self_intersections=True,
)

diag_res = diag.get_surface_diagnostic_summary(diag_params)
```

This code prints the results of the surface diagnostic summary:

```pycon
>>> print("Number of duplicate faces : ", diag_res.n_duplicate_faces)
>>> print("Number of free edges : ", diag_res.n_free_edges)
>>> print("Number of multi edges : ", diag_res.n_multi_edges)
>>> print("Number of self intersections : ", diag_res.n_self_intersections)

Number of duplicate faces :  0
Number of free edges :  0
Number of multi edges :  0
Number of self intersections :  0
```

<a id="face-metrics"></a>

### Face metrics

The [`FaceQualityMeasure`](../api/_autosummary/ansys.meshing.prime.FaceQualityMeasure.md#ansys.meshing.prime.FaceQualityMeasure) class offers various types
of measures to verify face quality metrics.

* The [`SKEWNESS`](../api/_autosummary/ansys.meshing.prime.FaceQualityMeasure.SKEWNESS.md#ansys.meshing.prime.FaceQualityMeasure.SKEWNESS) metric ranges between 0 (ideal) and 1 (worst).
* The [`ASPECTRATIO`](../api/_autosummary/ansys.meshing.prime.FaceQualityMeasure.ASPECTRATIO.md#ansys.meshing.prime.FaceQualityMeasure.ASPECTRATIO) metric is greater than 1. The smaller
  the aspect ratio, the higher the quality of an element.
* The [`ELEMENTQUALITY`](../api/_autosummary/ansys.meshing.prime.FaceQualityMeasure.ELEMENTQUALITY.md#ansys.meshing.prime.FaceQualityMeasure.ELEMENTQUALITY) metric ranges between
  0 (worst) and 1 (ideal).

This code gets face quality measures:

```python
face_quality_measures = prime.FaceQualityMeasure.SKEWNESS
quality = prime.SurfaceSearch(model)
quality_params = prime.SurfaceQualitySummaryParams(
    model=model,
    scope=prime.ScopeDefinition(model=model, part_expression="wrap"),
    face_quality_measures=[face_quality_measures],
    quality_limit=[0.9],
)
qual_summary_res = quality.get_surface_quality_summary(quality_params)
```

This code prints face quality summary results:

```pycon
>>> print("Maximum surface skewness : ", qual_summary_res.quality_results[0].max_quality)
>>> print("Number of faces above limit : ", qual_summary_res.quality_results[0].n_found)

Maximum surface skewness :  0.862375
Number of faces above limit :  0
```

<a id="cell-metrics"></a>

### Cell metrics

The [`CellQualityMeasure`](../api/_autosummary/ansys.meshing.prime.CellQualityMeasure.md#ansys.meshing.prime.CellQualityMeasure) class offers various types
of measures to verify cell quality metrics.

* The [`SKEWNESS`](../api/_autosummary/ansys.meshing.prime.CellQualityMeasure.SKEWNESS.md#ansys.meshing.prime.CellQualityMeasure.SKEWNESS) metric ranges between
  0 (ideal) and 1 (worst).
* The [`ASPECTRATIO`](../api/_autosummary/ansys.meshing.prime.CellQualityMeasure.ASPECTRATIO.md#ansys.meshing.prime.CellQualityMeasure.ASPECTRATIO) metric
  is greater than 1. The smaller the aspect ratio, the higher the quality of an element.
* The [`FLUENTASPECTRATIO`](../api/_autosummary/ansys.meshing.prime.CellQualityMeasure.FLUENTASPECTRATIO.md#ansys.meshing.prime.CellQualityMeasure.FLUENTASPECTRATIO) metric
  is greater than 1. The smaller the Fluent aspect ratio, the higher the quality of an element.
* The [`ELEMENTQUALITY`](../api/_autosummary/ansys.meshing.prime.CellQualityMeasure.ELEMENTQUALITY.md#ansys.meshing.prime.CellQualityMeasure.ELEMENTQUALITY) metric ranges
  between 0 (worst) and 1 (ideal).

This code gets cell quality measures:

```python
cell_quality_measures = prime.CellQualityMeasure.SKEWNESS
quality = prime.VolumeSearch(model)
quality_params = prime.VolumeQualitySummaryParams(
    model=model,
    scope=prime.ScopeDefinition(model=model, part_expression="wrap"),
    cell_quality_measures=[cell_quality_measures],
    quality_limit=[0.95],
)
qual_summary_res = quality.get_volume_quality_summary(quality_params)
```

This code prints cell quality summary results:

```pycon
>>> print("Maximum skewness : ", qual_summary_res.quality_results_part[0].max_quality)
>>> print(
...     "Number of cells above limit : ", qual_summary_res.quality_results_part[0].n_found
... )

Maximum skewness :  0.948388
Number of cells above limit :  0
```

<a id="mesh-counts"></a>

### Mesh counts

The [`Part.get_summary()`](../api/_autosummary/ansys.meshing.prime.Part.get_summary.md#ansys.meshing.prime.Part.get_summary) method provides the
number of nodes, faces, or cells after meshing with the given parameters.

This code gets mesh counts:

```python
part_summary_res = part.get_summary(
    prime.PartSummaryParams(model=model, print_id=False, print_mesh=True)
)
```

This code prints mesh counts:

```pycon
>>> print("Number of tri faces : ", part_summary_res.n_tri_faces)
>>> print("Number of tet cells : ", part_summary_res.n_tet_cells)
>>> print("Number of poly cells : ", part_summary_res.n_poly_cells)
>>> print("Total number of cells : ", part_summary_res.n_cells)

Number of tri faces :  49430
Number of tet cells :  254669
Number of poly cells :  82760
Total number of cells :  337429
```

<a id="mesh-improvement"></a>

## Mesh improvement

When the metrics show that the mesh quality is low, the [`VolumeMeshTool`](../api/_autosummary/ansys.meshing.prime.VolumeMeshTool.md#ansys.meshing.prime.VolumeMeshTool)
class provides various volume mesh improvement algorithms for improving the mesh.

<a id="auto-node-move"></a>

### Auto node move

You can improve volume mesh by auto node move using the
[`VolumeMeshTool.improve_by_auto_node_move()`](../api/_autosummary/ansys.meshing.prime.VolumeMeshTool.improve_by_auto_node_move.md#ansys.meshing.prime.VolumeMeshTool.improve_by_auto_node_move)
method with given parameters. In addition, you can verify the mesh using the
[`VolumeMeshTool.check_mesh()`](../api/_autosummary/ansys.meshing.prime.VolumeMeshTool.check_mesh.md#ansys.meshing.prime.VolumeMeshTool.check_mesh) method.

This code improves and checks the volume mesh:

```python
# Auto node move
perform_anm = prime.VolumeMeshTool(model=model)
anm_params = prime.AutoNodeMoveParams(
    model=model,
    quality_measure=prime.CellQualityMeasure.SKEWNESS,
    target_quality=0.95,
    dihedral_angle=90,
    n_iterations_per_node=50,
    restrict_boundary_nodes_along_surface=True,
    n_attempts=10,
)

perform_anm.improve_by_auto_node_move(
    part_id=part.id,
    cell_zonelets=part.get_cell_zonelets(),
    boundary_zonelets=part.get_face_zonelets(),
    params=anm_params,
)

# Mesh checking
vtool = prime.VolumeMeshTool(model=model)
res = vtool.check_mesh(part_id=part.id, params=prime.CheckMeshParams(model=model))
```

This code prints the results of checking mesh operation:

```pycon
>>> print("Non positive volumes:", result.has_non_positive_volumes)
>>> print("Non positive areas:", result.has_non_positive_areas)
>>> print("Invalid shape:", result.has_invalid_shape)
>>> print("Left handed faces:", result.has_left_handed_faces)

Non positive volumes :  False
Non positive areas :  False
Invalid shape :  False
Left handed faces :  False
```
