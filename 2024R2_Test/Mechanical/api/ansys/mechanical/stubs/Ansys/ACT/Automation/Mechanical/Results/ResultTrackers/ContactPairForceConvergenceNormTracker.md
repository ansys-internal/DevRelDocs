<a id="contactpairforceconvergencenormtracker"></a>

# ContactPairForceConvergenceNormTracker

<a id="ContactPairForceConvergenceNormTracker"></a>

### *class* ContactPairForceConvergenceNormTracker

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a ContactPairForceConvergenceNormTracker.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Summary |
|----------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`ExportAnimation`](#ContactPairForceConvergenceNormTracker.ExportAnimation)                 | Run the ExportAnimation action.                                                   |
| [`ClearGeneratedData`](#ContactPairForceConvergenceNormTracker.ClearGeneratedData)           | Run the ClearGeneratedData action.                                                |
| [`EvaluateAllResults`](#ContactPairForceConvergenceNormTracker.EvaluateAllResults)           | Run the EvaluateAllResults action.                                                |
| [`RenameBasedOnDefinition`](#ContactPairForceConvergenceNormTracker.RenameBasedOnDefinition) | Run the RenameBasedOnDefinition action.                                           |
| [`Delete`](#ContactPairForceConvergenceNormTracker.Delete)                                   | Run the Delete action.                                                            |
| [`GetChildren`](#id1)                                                                        | Gets the list of children, filtered by type.                                      |
| [`GetChildren`](#id1)                                                                        | Gets the list of children, filtered by type.                                      |
| [`AddComment`](#ContactPairForceConvergenceNormTracker.AddComment)                           | Creates a new child Comment.                                                      |
| [`AddImage`](#ContactPairForceConvergenceNormTracker.AddImage)                               | Creates a new child Image.                                                        |
| [`Activate`](#ContactPairForceConvergenceNormTracker.Activate)                               | Activate the current object.                                                      |
| [`CopyTo`](#ContactPairForceConvergenceNormTracker.CopyTo)                                   | Copies all visible properties from this object to another.                        |
| [`Duplicate`](#ContactPairForceConvergenceNormTracker.Duplicate)                             | Creates a copy of the current DataModelObject.                                    |
| [`GroupAllSimilarChildren`](#ContactPairForceConvergenceNormTracker.GroupAllSimilarChildren) | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#ContactPairForceConvergenceNormTracker.GroupSimilarObjects)         | Run the GroupSimilarObjects action.                                               |
| [`PropertyByName`](#ContactPairForceConvergenceNormTracker.PropertyByName)                   | Get a property by its unique name.                                                |
| [`PropertyByAPIName`](#ContactPairForceConvergenceNormTracker.PropertyByAPIName)             | Get a property by its API name.                                                   |
| [`CreateParameter`](#ContactPairForceConvergenceNormTracker.CreateParameter)                 | Creates a new parameter for a Property.                                           |
| [`GetParameter`](#ContactPairForceConvergenceNormTracker.GetParameter)                       | Gets the parameter corresponding to the given property.                           |
| [`RemoveParameter`](#ContactPairForceConvergenceNormTracker.RemoveParameter)                 | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Summary |
|---------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| [`InternalObject`](#id0)                                                                                                  | Gets the internal object. For advanced usage only.            |
| [`ContactRegion`](../../Connections/ContactRegion.md#ContactRegion)                                                       | Gets or sets the ContactRegion.                               |
| [`DataModelObjectCategory`](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                  |
| [`IsSolved`](#ContactPairForceConvergenceNormTracker.IsSolved)                                                            | Gets the IsSolved.                                            |
| [`ChartDimensions`](../../../../../Mechanical/DataModel/Enums/ChartDimensions.md#ChartDimensions)                         | Gets or sets the Chart Dimensions                             |
| [`BoundaryCondition`](#ContactPairForceConvergenceNormTracker.BoundaryCondition)                                          | Gets or sets the BoundaryCondition.                           |
| [`CutFrequency`](#ContactPairForceConvergenceNormTracker.CutFrequency)                                                    | Gets or sets the CutFrequency.                                |
| [`SectorNumber`](#ContactPairForceConvergenceNormTracker.SectorNumber)                                                    | Gets or sets the SectorNumber.                                |
| [`GeometrySelectionString`](#ContactPairForceConvergenceNormTracker.GeometrySelectionString)                              | Gets or sets the GeometrySelectionString.                     |
| [`LoadStepNumber`](#ContactPairForceConvergenceNormTracker.LoadStepNumber)                                                | Gets or sets the LoadStepNumber.                              |
| [`ReportedFrequency`](#ContactPairForceConvergenceNormTracker.ReportedFrequency)                                          | Gets the ReportedFrequency.                                   |
| [`Duration`](#ContactPairForceConvergenceNormTracker.Duration)                                                            | Gets or sets the Duration.                                    |
| [`FilterMaximum`](#ContactPairForceConvergenceNormTracker.FilterMaximum)                                                  | Gets the FilterMaximum.                                       |
| [`FilterMinimum`](#ContactPairForceConvergenceNormTracker.FilterMinimum)                                                  | Gets the FilterMinimum.                                       |
| [`FrequencyAtMaximumAmplitude`](#ContactPairForceConvergenceNormTracker.FrequencyAtMaximumAmplitude)                      | Gets the FrequencyAtMaximumAmplitude.                         |
| [`ImaginaryAtMaximumAmplitude`](#ContactPairForceConvergenceNormTracker.ImaginaryAtMaximumAmplitude)                      | Gets the ImaginaryAtMaximumAmplitude.                         |
| [`MaximumAmplitude`](#ContactPairForceConvergenceNormTracker.MaximumAmplitude)                                            | Gets the MaximumAmplitude.                                    |
| [`MaximumFrequency`](#ContactPairForceConvergenceNormTracker.MaximumFrequency)                                            | Gets or sets the MaximumFrequency.                            |
| [`Maximum`](#ContactPairForceConvergenceNormTracker.Maximum)                                                              | Gets the Maximum.                                             |
| [`MinimumFrequency`](#ContactPairForceConvergenceNormTracker.MinimumFrequency)                                            | Gets or sets the MinimumFrequency.                            |
| [`Minimum`](#ContactPairForceConvergenceNormTracker.Minimum)                                                              | Gets the Minimum.                                             |
| [`PhaseAngle`](#ContactPairForceConvergenceNormTracker.PhaseAngle)                                                        | Gets the PhaseAngle.                                          |
| [`RealAtMaximumAmplitude`](#ContactPairForceConvergenceNormTracker.RealAtMaximumAmplitude)                                | Gets the RealAtMaximumAmplitude.                              |
| [`RequestedFrequency`](#ContactPairForceConvergenceNormTracker.RequestedFrequency)                                        | Gets or sets the RequestedFrequency.                          |
| [`AccelerationType`](#ContactPairForceConvergenceNormTracker.AccelerationType)                                            | Gets or sets the AccelerationType.                            |
| [`ChartViewingStyle`](#ContactPairForceConvergenceNormTracker.ChartViewingStyle)                                          | Gets or sets the ChartViewingStyle.                           |
| [`DeformationType`](../../../../../Mechanical/DataModel/Enums/DeformationType.md#DeformationType)                         | Gets or sets the DeformationType.                             |
| [`FilterType`](../../../../../Mechanical/DataModel/Enums/FilterType.md#FilterType)                                        | Gets or sets the FilterType.                                  |
| [`SpatialResolution`](#ContactPairForceConvergenceNormTracker.SpatialResolution)                                          | Gets or sets the SpatialResolution.                           |
| [`NormalOrientation`](#ContactPairForceConvergenceNormTracker.NormalOrientation)                                          | Gets or sets the NormalOrientation.                           |
| [`CurvesAppearanceDisplay`](#ContactPairForceConvergenceNormTracker.CurvesAppearanceDisplay)                              | Gets or sets the CurvesAppearanceDisplay.                     |
| [`ResultChartType`](#ContactPairForceConvergenceNormTracker.ResultChartType)                                              | Gets the ResultChartType.                                     |
| [`DpfEvaluation`](#ContactPairForceConvergenceNormTracker.DpfEvaluation)                                                  | Gets or sets the DpfEvaluation.                               |
| [`XAxisValues`](../../../../../Mechanical/DataModel/Enums/XAxisValues.md#XAxisValues)                                     | Gets or sets the XAxisValues.                                 |
| [`ShearOrientation`](#ContactPairForceConvergenceNormTracker.ShearOrientation)                                            | Gets or sets the ShearOrientation.                            |
| [`StressStrainType`](../../../../../Mechanical/DataModel/Enums/StressStrainType.md#StressStrainType)                      | Gets or sets the StressStrainType.                            |
| [`TimeHistoryDisplay`](#ContactPairForceConvergenceNormTracker.TimeHistoryDisplay)                                        | Gets or sets the TimeHistoryDisplay.                          |
| [`VelocityType`](#ContactPairForceConvergenceNormTracker.VelocityType)                                                    | Gets or sets the VelocityType.                                |
| [`Suppressed`](#ContactPairForceConvergenceNormTracker.Suppressed)                                                        | Gets or sets the Suppressed.                                  |
| [`EnhancedTracking`](#ContactPairForceConvergenceNormTracker.EnhancedTracking)                                            | Gets the EnhancedTracking.                                    |
| [`UseParentFrequencyRange`](#ContactPairForceConvergenceNormTracker.UseParentFrequencyRange)                              | Gets or sets the UseParentFrequencyRange.                     |
| [`CoordinateSystem`](../../../../Common/CoordinateSystem.md#CoordinateSystem)                                             | Gets or sets the CoordinateSystem.                            |
| [`Spring`](../../Connections/Spring.md#Spring)                                                                            | Gets or sets the Spring.                                      |
| [`Location`](#ContactPairForceConvergenceNormTracker.Location)                                                            | Gets or sets the Location.                                    |
| [`Children`](#ContactPairForceConvergenceNormTracker.Children)                                                            | Gets the list of children.                                    |
| [`Comments`](#ContactPairForceConvergenceNormTracker.Comments)                                                            | Gets the list of associated comments.                         |
| [`Images`](#ContactPairForceConvergenceNormTracker.Images)                                                                | Gets the list of associated images.                           |
| [`InternalObject`](#id0)                                                                                                  | Gets the internal object. For advanced usage only.            |
| [`Properties`](#ContactPairForceConvergenceNormTracker.Properties)                                                        | Gets the list of properties for this object.                  |
| [`VisibleProperties`](#ContactPairForceConvergenceNormTracker.VisibleProperties)                                          | Gets the list of properties that are visible for this object. |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical.Results.ResultTrackers import ContactPairForceConvergenceNormTracker
```

<a id="property-detail"></a>

## Property detail

<a id="ContactPairForceConvergenceNormTracker.InternalObject"></a>

### *property* ContactPairForceConvergenceNormTracker.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSResultChartAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ContactRegion"></a>

### *property* ContactPairForceConvergenceNormTracker.ContactRegion *: [Ansys.ACT.Automation.Mechanical.Connections.ContactRegion](../../Connections/ContactRegion.md#ContactRegion) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ContactRegion.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.DataModelObjectCategory"></a>

### *property* ContactPairForceConvergenceNormTracker.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.IsSolved"></a>

### *property* ContactPairForceConvergenceNormTracker.IsSolved *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the IsSolved.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ChartDimensions"></a>

### *property* ContactPairForceConvergenceNormTracker.ChartDimensions *: [Ansys.Mechanical.DataModel.Enums.ChartDimensions](../../../../../Mechanical/DataModel/Enums/ChartDimensions.md#ChartDimensions) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Chart Dimensions

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.BoundaryCondition"></a>

### *property* ContactPairForceConvergenceNormTracker.BoundaryCondition *: [Ansys.ACT.Automation.Mechanical.BoundaryConditions.GenericBoundaryCondition](../../BoundaryConditions/GenericBoundaryCondition.md#GenericBoundaryCondition) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the BoundaryCondition.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.CutFrequency"></a>

### *property* ContactPairForceConvergenceNormTracker.CutFrequency *: System.Double | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the CutFrequency.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.SectorNumber"></a>

### *property* ContactPairForceConvergenceNormTracker.SectorNumber *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the SectorNumber.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.GeometrySelectionString"></a>

### *property* ContactPairForceConvergenceNormTracker.GeometrySelectionString *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the GeometrySelectionString.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.LoadStepNumber"></a>

### *property* ContactPairForceConvergenceNormTracker.LoadStepNumber *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the LoadStepNumber.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ReportedFrequency"></a>

### *property* ContactPairForceConvergenceNormTracker.ReportedFrequency *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the ReportedFrequency.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Duration"></a>

### *property* ContactPairForceConvergenceNormTracker.Duration *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Duration.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.FilterMaximum"></a>

### *property* ContactPairForceConvergenceNormTracker.FilterMaximum *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the FilterMaximum.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.FilterMinimum"></a>

### *property* ContactPairForceConvergenceNormTracker.FilterMinimum *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the FilterMinimum.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.FrequencyAtMaximumAmplitude"></a>

### *property* ContactPairForceConvergenceNormTracker.FrequencyAtMaximumAmplitude *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the FrequencyAtMaximumAmplitude.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ImaginaryAtMaximumAmplitude"></a>

### *property* ContactPairForceConvergenceNormTracker.ImaginaryAtMaximumAmplitude *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the ImaginaryAtMaximumAmplitude.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.MaximumAmplitude"></a>

### *property* ContactPairForceConvergenceNormTracker.MaximumAmplitude *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumAmplitude.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.MaximumFrequency"></a>

### *property* ContactPairForceConvergenceNormTracker.MaximumFrequency *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the MaximumFrequency.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Maximum"></a>

### *property* ContactPairForceConvergenceNormTracker.Maximum *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Maximum.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.MinimumFrequency"></a>

### *property* ContactPairForceConvergenceNormTracker.MinimumFrequency *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the MinimumFrequency.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Minimum"></a>

### *property* ContactPairForceConvergenceNormTracker.Minimum *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Minimum.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.PhaseAngle"></a>

### *property* ContactPairForceConvergenceNormTracker.PhaseAngle *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the PhaseAngle.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.RealAtMaximumAmplitude"></a>

### *property* ContactPairForceConvergenceNormTracker.RealAtMaximumAmplitude *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the RealAtMaximumAmplitude.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.RequestedFrequency"></a>

### *property* ContactPairForceConvergenceNormTracker.RequestedFrequency *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the RequestedFrequency.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.AccelerationType"></a>

### *property* ContactPairForceConvergenceNormTracker.AccelerationType *: [Ansys.Mechanical.DataModel.Enums.TotalOrDirectional](../../../../../Mechanical/DataModel/Enums/TotalOrDirectional.md#TotalOrDirectional) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the AccelerationType.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ChartViewingStyle"></a>

### *property* ContactPairForceConvergenceNormTracker.ChartViewingStyle *: [Ansys.Mechanical.DataModel.Enums.ChartAxisScaleType](../../../../../Mechanical/DataModel/Enums/ChartAxisScaleType.md#ChartAxisScaleType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ChartViewingStyle.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.DeformationType"></a>

### *property* ContactPairForceConvergenceNormTracker.DeformationType *: [Ansys.Mechanical.DataModel.Enums.TotalOrDirectional](../../../../../Mechanical/DataModel/Enums/TotalOrDirectional.md#TotalOrDirectional) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the DeformationType.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.FilterType"></a>

### *property* ContactPairForceConvergenceNormTracker.FilterType *: [Ansys.Mechanical.DataModel.Enums.FilterType](../../../../../Mechanical/DataModel/Enums/FilterType.md#FilterType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the FilterType.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.SpatialResolution"></a>

### *property* ContactPairForceConvergenceNormTracker.SpatialResolution *: [Ansys.Mechanical.DataModel.Enums.MultipleNodeType](../../../../../Mechanical/DataModel/Enums/MultipleNodeType.md#MultipleNodeType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the SpatialResolution.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.NormalOrientation"></a>

### *property* ContactPairForceConvergenceNormTracker.NormalOrientation *: [Ansys.Mechanical.DataModel.Enums.NormalOrientationType](../../../../../Mechanical/DataModel/Enums/NormalOrientationType.md#NormalOrientationType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the NormalOrientation.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.CurvesAppearanceDisplay"></a>

### *property* ContactPairForceConvergenceNormTracker.CurvesAppearanceDisplay *: [Ansys.Mechanical.DataModel.Enums.ChartPlotStyle](../../../../../Mechanical/DataModel/Enums/ChartPlotStyle.md#ChartPlotStyle) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the CurvesAppearanceDisplay.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ResultChartType"></a>

### *property* ContactPairForceConvergenceNormTracker.ResultChartType *: [Ansys.Mechanical.DataModel.Enums.ChartResultType](../../../../../Mechanical/DataModel/Enums/ChartResultType.md#ChartResultType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the ResultChartType.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.DpfEvaluation"></a>

### *property* ContactPairForceConvergenceNormTracker.DpfEvaluation *: [Ansys.Mechanical.DataModel.Enums.DpfEvaluationType](../../../../../Mechanical/DataModel/Enums/DpfEvaluationType.md#DpfEvaluationType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the DpfEvaluation.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.XAxisValues"></a>

### *property* ContactPairForceConvergenceNormTracker.XAxisValues *: [Ansys.Mechanical.DataModel.Enums.XAxisValues](../../../../../Mechanical/DataModel/Enums/XAxisValues.md#XAxisValues) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the XAxisValues.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ShearOrientation"></a>

### *property* ContactPairForceConvergenceNormTracker.ShearOrientation *: [Ansys.Mechanical.DataModel.Enums.ShearOrientationType](../../../../../Mechanical/DataModel/Enums/ShearOrientationType.md#ShearOrientationType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ShearOrientation.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.StressStrainType"></a>

### *property* ContactPairForceConvergenceNormTracker.StressStrainType *: [Ansys.Mechanical.DataModel.Enums.StressStrainType](../../../../../Mechanical/DataModel/Enums/StressStrainType.md#StressStrainType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the StressStrainType.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.TimeHistoryDisplay"></a>

### *property* ContactPairForceConvergenceNormTracker.TimeHistoryDisplay *: [Ansys.Mechanical.DataModel.Enums.TimeHistoryDisplayType](../../../../../Mechanical/DataModel/Enums/TimeHistoryDisplayType.md#TimeHistoryDisplayType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the TimeHistoryDisplay.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.VelocityType"></a>

### *property* ContactPairForceConvergenceNormTracker.VelocityType *: [Ansys.Mechanical.DataModel.Enums.TotalOrDirectional](../../../../../Mechanical/DataModel/Enums/TotalOrDirectional.md#TotalOrDirectional) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the VelocityType.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Suppressed"></a>

### *property* ContactPairForceConvergenceNormTracker.Suppressed *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Suppressed.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.EnhancedTracking"></a>

### *property* ContactPairForceConvergenceNormTracker.EnhancedTracking *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the EnhancedTracking.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.UseParentFrequencyRange"></a>

### *property* ContactPairForceConvergenceNormTracker.UseParentFrequencyRange *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the UseParentFrequencyRange.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.CoordinateSystem"></a>

### *property* ContactPairForceConvergenceNormTracker.CoordinateSystem *: [Ansys.ACT.Automation.Mechanical.CoordinateSystem](../../CoordinateSystem.md#CoordinateSystem) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the CoordinateSystem.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Spring"></a>

### *property* ContactPairForceConvergenceNormTracker.Spring *: [Ansys.ACT.Automation.Mechanical.Connections.Spring](../../Connections/Spring.md#Spring) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Spring.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Location"></a>

### *property* ContactPairForceConvergenceNormTracker.Location *: Ansys.ACT.Interfaces.Common.ISelectionInfo | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Location.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Children"></a>

### *property* ContactPairForceConvergenceNormTracker.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Comments"></a>

### *property* ContactPairForceConvergenceNormTracker.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](../../Comment.md#Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Images"></a>

### *property* ContactPairForceConvergenceNormTracker.Images *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Image](../../Image.md#Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* ContactPairForceConvergenceNormTracker.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Properties"></a>

### *property* ContactPairForceConvergenceNormTracker.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.VisibleProperties"></a>

### *property* ContactPairForceConvergenceNormTracker.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="ContactPairForceConvergenceNormTracker.ExportAnimation"></a>

### ContactPairForceConvergenceNormTracker.ExportAnimation(filePath: System.String, format: [Ansys.Mechanical.DataModel.Enums.GraphicsAnimationExportFormat](../../../../../Mechanical/DataModel/Enums/GraphicsAnimationExportFormat.md#GraphicsAnimationExportFormat), settings: [Ansys.Mechanical.Graphics.AnimationExportSettings](../../../../../Mechanical/Graphics/AnimationExportSettings.md#AnimationExportSettings))

Run the ExportAnimation action.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.ClearGeneratedData"></a>

### ContactPairForceConvergenceNormTracker.ClearGeneratedData()

Run the ClearGeneratedData action.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.EvaluateAllResults"></a>

### ContactPairForceConvergenceNormTracker.EvaluateAllResults()

Run the EvaluateAllResults action.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.RenameBasedOnDefinition"></a>

### ContactPairForceConvergenceNormTracker.RenameBasedOnDefinition()

Run the RenameBasedOnDefinition action.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Delete"></a>

### ContactPairForceConvergenceNormTracker.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.GetChildren"></a>

### ContactPairForceConvergenceNormTracker.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### ContactPairForceConvergenceNormTracker.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.AddComment"></a>

### ContactPairForceConvergenceNormTracker.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.AddImage"></a>

### ContactPairForceConvergenceNormTracker.AddImage(filePath: System.String)

Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Activate"></a>

### ContactPairForceConvergenceNormTracker.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.CopyTo"></a>

### ContactPairForceConvergenceNormTracker.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.Duplicate"></a>

### ContactPairForceConvergenceNormTracker.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.GroupAllSimilarChildren"></a>

### ContactPairForceConvergenceNormTracker.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.GroupSimilarObjects"></a>

### ContactPairForceConvergenceNormTracker.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.PropertyByName"></a>

### ContactPairForceConvergenceNormTracker.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.PropertyByAPIName"></a>

### ContactPairForceConvergenceNormTracker.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.CreateParameter"></a>

### ContactPairForceConvergenceNormTracker.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.GetParameter"></a>

### ContactPairForceConvergenceNormTracker.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="ContactPairForceConvergenceNormTracker.RemoveParameter"></a>

### ContactPairForceConvergenceNormTracker.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->