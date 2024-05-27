# StressProbe

<a id="StressProbe"></a>

### *class* StressProbe

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a StressProbe.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|-------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`ExportAnimation`](#StressProbe.ExportAnimation)                 | Run the ExportAnimation action.                                                   |
| [`ClearGeneratedData`](#StressProbe.ClearGeneratedData)           | Run the ClearGeneratedData action.                                                |
| [`DuplicateWithoutResults`](#StressProbe.DuplicateWithoutResults) | Run the DuplicateWithoutResults action.                                           |
| [`EvaluateAllResults`](#StressProbe.EvaluateAllResults)           | Run the EvaluateAllResults action.                                                |
| [`SnapToMeshNodes`](#StressProbe.SnapToMeshNodes)                 | Snap the coordinates of probe result to the mesh nodes.                           |
| [`RenameBasedOnDefinition`](#StressProbe.RenameBasedOnDefinition) | Run the RenameBasedOnDefinition action.                                           |
| [`Delete`](#StressProbe.Delete)                                   | Run the Delete action.                                                            |
| [`GetChildren`](#id1)                                             | Gets the list of children, filtered by type.                                      |
| [`GetChildren`](#id1)                                             | Gets the list of children, filtered by type.                                      |
| [`AddComment`](#StressProbe.AddComment)                           | Creates a new child Comment.                                                      |
| [`AddFigure`](#StressProbe.AddFigure)                             | Creates a new child Figure.                                                       |
| [`AddImage`](#StressProbe.AddImage)                               | Creates a new child Image.                                                        |
| [`Activate`](#StressProbe.Activate)                               | Activate the current object.                                                      |
| [`CopyTo`](#StressProbe.CopyTo)                                   | Copies all visible properties from this object to another.                        |
| [`Duplicate`](#StressProbe.Duplicate)                             | Creates a copy of the current DataModelObject.                                    |
| [`GroupAllSimilarChildren`](#StressProbe.GroupAllSimilarChildren) | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#StressProbe.GroupSimilarObjects)         | Run the GroupSimilarObjects action.                                               |
| [`PropertyByName`](#StressProbe.PropertyByName)                   | Get a property by its unique name.                                                |
| [`PropertyByAPIName`](#StressProbe.PropertyByAPIName)             | Get a property by its API name.                                                   |
| [`CreateParameter`](#StressProbe.CreateParameter)                 | Creates a new parameter for a Property.                                           |
| [`GetParameter`](#StressProbe.GetParameter)                       | Gets the parameter corresponding to the given property.                           |
| [`RemoveParameter`](#StressProbe.RemoveParameter)                 | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Description |
|---------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`InternalObject`](#id0)                                                                                                  | Gets the internal object. For advanced usage only.                                                                                                                         |
| [`EquivalentStress`](../StressResults/EquivalentStress.md#EquivalentStress)                                               | Gets the EquivalentStress.                                                                                                                                                 |
| [`XCoordinate`](#StressProbe.XCoordinate)                                                                                 | Gets the XCoordinate.                                                                                                                                                      |
| [`YCoordinate`](#StressProbe.YCoordinate)                                                                                 | Gets the YCoordinate.                                                                                                                                                      |
| [`ZCoordinate`](#StressProbe.ZCoordinate)                                                                                 | Gets the ZCoordinate.                                                                                                                                                      |
| [`MaximumEquivalentStress`](#StressProbe.MaximumEquivalentStress)                                                         | Gets the MaximumEquivalentStress.                                                                                                                                          |
| [`MaximumMaximumPrincipalStress`](#StressProbe.MaximumMaximumPrincipalStress)                                             | Gets the MaximumMaximumPrincipalStress.                                                                                                                                    |
| [`MaximumMiddlePrincipalStress`](#StressProbe.MaximumMiddlePrincipalStress)                                               | Gets the MaximumMiddlePrincipalStress.                                                                                                                                     |
| [`MaximumMinimumPrincipalStress`](#StressProbe.MaximumMinimumPrincipalStress)                                             | Gets the MaximumMinimumPrincipalStress.                                                                                                                                    |
| [`MaximumNormalXAxisStress`](#StressProbe.MaximumNormalXAxisStress)                                                       | Gets the MaximumNormalXAxisStress.                                                                                                                                         |
| [`MaximumNormalYAxisStress`](#StressProbe.MaximumNormalYAxisStress)                                                       | Gets the MaximumNormalYAxisStress.                                                                                                                                         |
| [`MaximumNormalZAxisStress`](#StressProbe.MaximumNormalZAxisStress)                                                       | Gets the MaximumNormalZAxisStress.                                                                                                                                         |
| [`MaximumPrincipalStress`](../StressResults/MaximumPrincipalStress.md#MaximumPrincipalStress)                             | Gets the MaximumPrincipalStress.                                                                                                                                           |
| [`MaximumXYShearStress`](#StressProbe.MaximumXYShearStress)                                                               | Gets the MaximumXYShearStress.                                                                                                                                             |
| [`MaximumXZShearStress`](#StressProbe.MaximumXZShearStress)                                                               | Gets the MaximumXZShearStress.                                                                                                                                             |
| [`MaximumYZShearStress`](#StressProbe.MaximumYZShearStress)                                                               | Gets the MaximumYZShearStress.                                                                                                                                             |
| [`MaximumStressIntensity`](#StressProbe.MaximumStressIntensity)                                                           | Gets the MaximumStressIntensity.                                                                                                                                           |
| [`MiddlePrincipalStress`](../StressResults/MiddlePrincipalStress.md#MiddlePrincipalStress)                                | Gets the MiddlePrincipalStress.                                                                                                                                            |
| [`MinimumEquivalentStress`](#StressProbe.MinimumEquivalentStress)                                                         | Gets the MinimumEquivalentStress.                                                                                                                                          |
| [`MinimumMaximumPrincipalStress`](#StressProbe.MinimumMaximumPrincipalStress)                                             | Gets the MinimumMaximumPrincipalStress.                                                                                                                                    |
| [`MinimumMiddlePrincipalStress`](#StressProbe.MinimumMiddlePrincipalStress)                                               | Gets the MinimumMiddlePrincipalStress.                                                                                                                                     |
| [`MinimumMinimumPrincipalStress`](#StressProbe.MinimumMinimumPrincipalStress)                                             | Gets the MinimumMinimumPrincipalStress.                                                                                                                                    |
| [`MinimumNormalXAxisStress`](#StressProbe.MinimumNormalXAxisStress)                                                       | Gets the MinimumNormalXAxisStress.                                                                                                                                         |
| [`MinimumNormalYAxisStress`](#StressProbe.MinimumNormalYAxisStress)                                                       | Gets the MinimumNormalYAxisStress.                                                                                                                                         |
| [`MinimumNormalZAxisStress`](#StressProbe.MinimumNormalZAxisStress)                                                       | Gets the MinimumNormalZAxisStress.                                                                                                                                         |
| [`MinimumPrincipalStress`](../StressResults/MinimumPrincipalStress.md#MinimumPrincipalStress)                             | Gets the MinimumPrincipalStress.                                                                                                                                           |
| [`MinimumXYShearStress`](#StressProbe.MinimumXYShearStress)                                                               | Gets the MinimumXYShearStress.                                                                                                                                             |
| [`MinimumXZShearStress`](#StressProbe.MinimumXZShearStress)                                                               | Gets the MinimumXZShearStress.                                                                                                                                             |
| [`MinimumYZShearStress`](#StressProbe.MinimumYZShearStress)                                                               | Gets the MinimumYZShearStress.                                                                                                                                             |
| [`MinimumStressIntensity`](#StressProbe.MinimumStressIntensity)                                                           | Gets the MinimumStressIntensity.                                                                                                                                           |
| [`NormalXAxisStress`](#StressProbe.NormalXAxisStress)                                                                     | Gets the NormalXAxisStress.                                                                                                                                                |
| [`NormalYAxisStress`](#StressProbe.NormalYAxisStress)                                                                     | Gets the NormalYAxisStress.                                                                                                                                                |
| [`NormalZAxisStress`](#StressProbe.NormalZAxisStress)                                                                     | Gets the NormalZAxisStress.                                                                                                                                                |
| [`XYShearStress`](#StressProbe.XYShearStress)                                                                             | Gets the XYShearStress.                                                                                                                                                    |
| [`XZShearStress`](#StressProbe.XZShearStress)                                                                             | Gets the XZShearStress.                                                                                                                                                    |
| [`YZShearStress`](#StressProbe.YZShearStress)                                                                             | Gets the YZShearStress.                                                                                                                                                    |
| [`StressIntensity`](../StressResults/StressIntensity.md#StressIntensity)                                                  | Gets the StressIntensity.                                                                                                                                                  |
| [`DataModelObjectCategory`](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                                                                                                                               |
| [`Summation`](#StressProbe.Summation)                                                                                     | Gets or sets the Summation.                                                                                                                                                |
| [`LocationMethod`](#StressProbe.LocationMethod)                                                                           | Gets or sets the LocationMethod.                                                                                                                                           |
| [`GeometryLocation`](#StressProbe.GeometryLocation)                                                                       | Gets or sets the GeometryLocation.                                                                                                                                         |
| [`CoordinateSystemSelection`](#StressProbe.CoordinateSystemSelection)                                                     | Gets or sets the CoordinateSystemSelection.                                                                                                                                |
| [`BoundaryConditionSelection`](#StressProbe.BoundaryConditionSelection)                                                   | Gets or sets the BoundaryConditionSelection. In order to select the option ‘WeakSprings’, please use the property ‘LocationMethod = LocationDefinitionMethod.WeakSprings’. |
| [`ContactRegionSelection`](#StressProbe.ContactRegionSelection)                                                           | Gets or sets the ContactRegionSelection.                                                                                                                                   |
| [`RemotePointSelection`](#StressProbe.RemotePointSelection)                                                               | Gets or sets the RemotePointSelection.                                                                                                                                     |
| [`BeamSelection`](#StressProbe.BeamSelection)                                                                             | Gets or sets the BeamSelection.                                                                                                                                            |
| [`MeshConnectionSelection`](#StressProbe.MeshConnectionSelection)                                                         | Gets or sets the MeshConnectionSelection.                                                                                                                                  |
| [`SurfaceSelection`](#StressProbe.SurfaceSelection)                                                                       | Gets or sets the MeshConnectionSelection.                                                                                                                                  |
| [`SpringSelection`](#StressProbe.SpringSelection)                                                                         | Gets or sets the SpringSelection.                                                                                                                                          |
| [`IsSolved`](#StressProbe.IsSolved)                                                                                       | Gets the IsSolved.                                                                                                                                                         |
| [`Orientation`](#StressProbe.Orientation)                                                                                 | Gets or sets the Orientation. Accepts/Returns None if it is the Solution Coordinate System.                                                                                |
| [`IterationNumber`](#StressProbe.IterationNumber)                                                                         | Gets the IterationNumber.                                                                                                                                                  |
| [`LoadStep`](#StressProbe.LoadStep)                                                                                       | Gets the LoadStep.                                                                                                                                                         |
| [`LoadStepNumber`](#StressProbe.LoadStepNumber)                                                                           | Gets or sets the LoadStepNumber.                                                                                                                                           |
| [`Substep`](#StressProbe.Substep)                                                                                         | Gets the Substep.                                                                                                                                                          |
| [`DisplayTime`](#StressProbe.DisplayTime)                                                                                 | Gets or sets the DisplayTime.                                                                                                                                              |
| [`MaximumTotal`](#StressProbe.MaximumTotal)                                                                               | Gets the MaximumTotal.                                                                                                                                                     |
| [`MaximumXAxis`](#StressProbe.MaximumXAxis)                                                                               | Gets the MaximumXAxis.                                                                                                                                                     |
| [`MaximumYAxis`](#StressProbe.MaximumYAxis)                                                                               | Gets the MaximumYAxis.                                                                                                                                                     |
| [`MaximumZAxis`](#StressProbe.MaximumZAxis)                                                                               | Gets the MaximumZAxis.                                                                                                                                                     |
| [`MinimumTotal`](#StressProbe.MinimumTotal)                                                                               | Gets the MinimumTotal.                                                                                                                                                     |
| [`MinimumXAxis`](#StressProbe.MinimumXAxis)                                                                               | Gets the MinimumXAxis.                                                                                                                                                     |
| [`MinimumYAxis`](#StressProbe.MinimumYAxis)                                                                               | Gets the MinimumYAxis.                                                                                                                                                     |
| [`MinimumZAxis`](#StressProbe.MinimumZAxis)                                                                               | Gets the MinimumZAxis.                                                                                                                                                     |
| [`Time`](#StressProbe.Time)                                                                                               | Gets the Time.                                                                                                                                                             |
| [`Total`](#StressProbe.Total)                                                                                             | Gets the Total.                                                                                                                                                            |
| [`XAxis`](#StressProbe.XAxis)                                                                                             | Gets the XAxis.                                                                                                                                                            |
| [`YAxis`](#StressProbe.YAxis)                                                                                             | Gets the YAxis.                                                                                                                                                            |
| [`ZAxis`](#StressProbe.ZAxis)                                                                                             | Gets the ZAxis.                                                                                                                                                            |
| [`ResultSelection`](#StressProbe.ResultSelection)                                                                         | Gets or sets the ResultSelection.                                                                                                                                          |
| [`SpatialResolution`](#StressProbe.SpatialResolution)                                                                     | Gets or sets the SpatialResolution.                                                                                                                                        |
| [`Type`](#StressProbe.Type)                                                                                               | Gets the Type.                                                                                                                                                             |
| [`DpfEvaluation`](#StressProbe.DpfEvaluation)                                                                             | Gets or sets the DpfEvaluation.                                                                                                                                            |
| [`Suppressed`](#StressProbe.Suppressed)                                                                                   | Gets or sets the Suppressed.                                                                                                                                               |
| [`Children`](#StressProbe.Children)                                                                                       | Gets the list of children.                                                                                                                                                 |
| [`Comments`](#StressProbe.Comments)                                                                                       | Gets the list of associated comments.                                                                                                                                      |
| [`Figures`](#StressProbe.Figures)                                                                                         | Gets the list of associated figures.                                                                                                                                       |
| [`Images`](#StressProbe.Images)                                                                                           | Gets the list of associated images.                                                                                                                                        |
| [`InternalObject`](#id0)                                                                                                  | Gets the internal object. For advanced usage only.                                                                                                                         |
| [`Properties`](#StressProbe.Properties)                                                                                   | Gets the list of properties for this object.                                                                                                                               |
| [`VisibleProperties`](#StressProbe.VisibleProperties)                                                                     | Gets the list of properties that are visible for this object.                                                                                                              |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical.Results.ProbeResults import StressProbe
```

<a id="property-detail"></a>

## Property detail

<a id="StressProbe.InternalObject"></a>

### *property* StressProbe.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSProbeResultAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.EquivalentStress"></a>

### *property* StressProbe.EquivalentStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the EquivalentStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.XCoordinate"></a>

### *property* StressProbe.XCoordinate *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the XCoordinate.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.YCoordinate"></a>

### *property* StressProbe.YCoordinate *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the YCoordinate.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.ZCoordinate"></a>

### *property* StressProbe.ZCoordinate *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the ZCoordinate.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumEquivalentStress"></a>

### *property* StressProbe.MaximumEquivalentStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumEquivalentStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumMaximumPrincipalStress"></a>

### *property* StressProbe.MaximumMaximumPrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumMaximumPrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumMiddlePrincipalStress"></a>

### *property* StressProbe.MaximumMiddlePrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumMiddlePrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumMinimumPrincipalStress"></a>

### *property* StressProbe.MaximumMinimumPrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumMinimumPrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumNormalXAxisStress"></a>

### *property* StressProbe.MaximumNormalXAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumNormalXAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumNormalYAxisStress"></a>

### *property* StressProbe.MaximumNormalYAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumNormalYAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumNormalZAxisStress"></a>

### *property* StressProbe.MaximumNormalZAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumNormalZAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumPrincipalStress"></a>

### *property* StressProbe.MaximumPrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumPrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumXYShearStress"></a>

### *property* StressProbe.MaximumXYShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumXYShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumXZShearStress"></a>

### *property* StressProbe.MaximumXZShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumXZShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumYZShearStress"></a>

### *property* StressProbe.MaximumYZShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumYZShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumStressIntensity"></a>

### *property* StressProbe.MaximumStressIntensity *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumStressIntensity.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MiddlePrincipalStress"></a>

### *property* StressProbe.MiddlePrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MiddlePrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumEquivalentStress"></a>

### *property* StressProbe.MinimumEquivalentStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumEquivalentStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumMaximumPrincipalStress"></a>

### *property* StressProbe.MinimumMaximumPrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumMaximumPrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumMiddlePrincipalStress"></a>

### *property* StressProbe.MinimumMiddlePrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumMiddlePrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumMinimumPrincipalStress"></a>

### *property* StressProbe.MinimumMinimumPrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumMinimumPrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumNormalXAxisStress"></a>

### *property* StressProbe.MinimumNormalXAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumNormalXAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumNormalYAxisStress"></a>

### *property* StressProbe.MinimumNormalYAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumNormalYAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumNormalZAxisStress"></a>

### *property* StressProbe.MinimumNormalZAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumNormalZAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumPrincipalStress"></a>

### *property* StressProbe.MinimumPrincipalStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumPrincipalStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumXYShearStress"></a>

### *property* StressProbe.MinimumXYShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumXYShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumXZShearStress"></a>

### *property* StressProbe.MinimumXZShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumXZShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumYZShearStress"></a>

### *property* StressProbe.MinimumYZShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumYZShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumStressIntensity"></a>

### *property* StressProbe.MinimumStressIntensity *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumStressIntensity.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.NormalXAxisStress"></a>

### *property* StressProbe.NormalXAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the NormalXAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.NormalYAxisStress"></a>

### *property* StressProbe.NormalYAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the NormalYAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.NormalZAxisStress"></a>

### *property* StressProbe.NormalZAxisStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the NormalZAxisStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.XYShearStress"></a>

### *property* StressProbe.XYShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the XYShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.XZShearStress"></a>

### *property* StressProbe.XZShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the XZShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.YZShearStress"></a>

### *property* StressProbe.YZShearStress *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the YZShearStress.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.StressIntensity"></a>

### *property* StressProbe.StressIntensity *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the StressIntensity.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.DataModelObjectCategory"></a>

### *property* StressProbe.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Summation"></a>

### *property* StressProbe.Summation *: [Ansys.Mechanical.DataModel.Enums.MomentsAtSummationPointType](../../../../../Mechanical/DataModel/Enums/MomentsAtSummationPointType.md#MomentsAtSummationPointType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Summation.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.LocationMethod"></a>

### *property* StressProbe.LocationMethod *: [Ansys.Mechanical.DataModel.Enums.LocationDefinitionMethod](../../../../../Mechanical/DataModel/Enums/LocationDefinitionMethod.md#LocationDefinitionMethod) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the LocationMethod.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.GeometryLocation"></a>

### *property* StressProbe.GeometryLocation *: Ansys.ACT.Interfaces.Common.ISelectionInfo | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the GeometryLocation.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.CoordinateSystemSelection"></a>

### *property* StressProbe.CoordinateSystemSelection *: [Ansys.ACT.Automation.Mechanical.CoordinateSystem](../../CoordinateSystem.md#CoordinateSystem) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the CoordinateSystemSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.BoundaryConditionSelection"></a>

### *property* StressProbe.BoundaryConditionSelection *: Ansys.ACT.Automation.Mechanical.DataModelObject | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the BoundaryConditionSelection. In order to select the option ‘WeakSprings’, please use the property ‘LocationMethod = LocationDefinitionMethod.WeakSprings’.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.ContactRegionSelection"></a>

### *property* StressProbe.ContactRegionSelection *: [Ansys.ACT.Automation.Mechanical.Connections.ContactRegion](../../Connections/ContactRegion.md#ContactRegion) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ContactRegionSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.RemotePointSelection"></a>

### *property* StressProbe.RemotePointSelection *: [Ansys.ACT.Automation.Mechanical.RemotePoint](../../RemotePoint.md#RemotePoint) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the RemotePointSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.BeamSelection"></a>

### *property* StressProbe.BeamSelection *: [Ansys.ACT.Automation.Mechanical.Connections.Beam](../../Connections/Beam.md#Beam) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the BeamSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MeshConnectionSelection"></a>

### *property* StressProbe.MeshConnectionSelection *: [Ansys.ACT.Automation.Mechanical.MeshConnection](../../MeshConnection.md#MeshConnection) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the MeshConnectionSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.SurfaceSelection"></a>

### *property* StressProbe.SurfaceSelection *: [Ansys.ACT.Automation.Mechanical.Surface](../../Surface.md#Surface) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the MeshConnectionSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.SpringSelection"></a>

### *property* StressProbe.SpringSelection *: [Ansys.ACT.Automation.Mechanical.Connections.Spring](../../Connections/Spring.md#Spring) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the SpringSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.IsSolved"></a>

### *property* StressProbe.IsSolved *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the IsSolved.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Orientation"></a>

### *property* StressProbe.Orientation *: [Ansys.ACT.Automation.Mechanical.CoordinateSystem](../../CoordinateSystem.md#CoordinateSystem) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Orientation. Accepts/Returns None if it is the Solution Coordinate System.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.IterationNumber"></a>

### *property* StressProbe.IterationNumber *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the IterationNumber.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.LoadStep"></a>

### *property* StressProbe.LoadStep *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the LoadStep.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.LoadStepNumber"></a>

### *property* StressProbe.LoadStepNumber *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the LoadStepNumber.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Substep"></a>

### *property* StressProbe.Substep *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Substep.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.DisplayTime"></a>

### *property* StressProbe.DisplayTime *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the DisplayTime.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumTotal"></a>

### *property* StressProbe.MaximumTotal *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumTotal.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumXAxis"></a>

### *property* StressProbe.MaximumXAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumXAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumYAxis"></a>

### *property* StressProbe.MaximumYAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumYAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MaximumZAxis"></a>

### *property* StressProbe.MaximumZAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumZAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumTotal"></a>

### *property* StressProbe.MinimumTotal *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumTotal.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumXAxis"></a>

### *property* StressProbe.MinimumXAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumXAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumYAxis"></a>

### *property* StressProbe.MinimumYAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumYAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.MinimumZAxis"></a>

### *property* StressProbe.MinimumZAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumZAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Time"></a>

### *property* StressProbe.Time *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Time.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Total"></a>

### *property* StressProbe.Total *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Total.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.XAxis"></a>

### *property* StressProbe.XAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the XAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.YAxis"></a>

### *property* StressProbe.YAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the YAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.ZAxis"></a>

### *property* StressProbe.ZAxis *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the ZAxis.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.ResultSelection"></a>

### *property* StressProbe.ResultSelection *: [Ansys.Mechanical.DataModel.Enums.ProbeDisplayFilter](../../../../../Mechanical/DataModel/Enums/ProbeDisplayFilter.md#ProbeDisplayFilter) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ResultSelection.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.SpatialResolution"></a>

### *property* StressProbe.SpatialResolution *: [Ansys.Mechanical.DataModel.Enums.MinimumOrMaximum](../../../../../Mechanical/DataModel/Enums/MinimumOrMaximum.md#MinimumOrMaximum) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the SpatialResolution.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Type"></a>

### *property* StressProbe.Type *: [Ansys.Mechanical.DataModel.Enums.ProbeResultType](../../../../../Mechanical/DataModel/Enums/ProbeResultType.md#ProbeResultType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Type.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.DpfEvaluation"></a>

### *property* StressProbe.DpfEvaluation *: [Ansys.Mechanical.DataModel.Enums.DpfEvaluationType](../../../../../Mechanical/DataModel/Enums/DpfEvaluationType.md#DpfEvaluationType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the DpfEvaluation.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Suppressed"></a>

### *property* StressProbe.Suppressed *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Suppressed.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Children"></a>

### *property* StressProbe.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Comments"></a>

### *property* StressProbe.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](../../Comment.md#Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Figures"></a>

### *property* StressProbe.Figures *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Figure](../../Figure.md#Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Images"></a>

### *property* StressProbe.Images *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Image](../../Image.md#Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* StressProbe.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Properties"></a>

### *property* StressProbe.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.VisibleProperties"></a>

### *property* StressProbe.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="StressProbe.ExportAnimation"></a>

### StressProbe.ExportAnimation(filePath: System.String, format: [Ansys.Mechanical.DataModel.Enums.GraphicsAnimationExportFormat](../../../../../Mechanical/DataModel/Enums/GraphicsAnimationExportFormat.md#GraphicsAnimationExportFormat), settings: [Ansys.Mechanical.Graphics.AnimationExportSettings](../../../../../Mechanical/Graphics/AnimationExportSettings.md#AnimationExportSettings))

Run the ExportAnimation action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.ClearGeneratedData"></a>

### StressProbe.ClearGeneratedData()

Run the ClearGeneratedData action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.DuplicateWithoutResults"></a>

### StressProbe.DuplicateWithoutResults()

Run the DuplicateWithoutResults action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.EvaluateAllResults"></a>

### StressProbe.EvaluateAllResults()

Run the EvaluateAllResults action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.SnapToMeshNodes"></a>

### StressProbe.SnapToMeshNodes()

Snap the coordinates of probe result to the mesh nodes.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.RenameBasedOnDefinition"></a>

### StressProbe.RenameBasedOnDefinition()

Run the RenameBasedOnDefinition action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Delete"></a>

### StressProbe.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.GetChildren"></a>

### StressProbe.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### StressProbe.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.AddComment"></a>

### StressProbe.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.AddFigure"></a>

### StressProbe.AddFigure()

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.AddImage"></a>

### StressProbe.AddImage(filePath: System.String)

Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Activate"></a>

### StressProbe.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.CopyTo"></a>

### StressProbe.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.Duplicate"></a>

### StressProbe.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.GroupAllSimilarChildren"></a>

### StressProbe.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.GroupSimilarObjects"></a>

### StressProbe.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.PropertyByName"></a>

### StressProbe.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.PropertyByAPIName"></a>

### StressProbe.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.CreateParameter"></a>

### StressProbe.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.GetParameter"></a>

### StressProbe.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="StressProbe.RemoveParameter"></a>

### StressProbe.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->