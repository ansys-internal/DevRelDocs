# `DirectionalAxialForce`

<a id="ansys.mechanical.stubs.v241.Ansys.ACT.Automation.Mechanical.Results.BeamResults.DirectionalAxialForce"></a>

#### *class* Ansys.ACT.Automation.Mechanical.Results.BeamResults.DirectionalAxialForce

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

Defines a DirectionalAxialForce.

<!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|-----------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`Activate`](#DirectionalAxialForce.Activate)                               | Activate the current object.                                                      |
| [`AddAlert`](#DirectionalAxialForce.AddAlert)                               | Creates a new Alert                                                               |
| [`AddComment`](#DirectionalAxialForce.AddComment)                           | Creates a new child Comment.                                                      |
| [`AddConvergence`](#DirectionalAxialForce.AddConvergence)                   | Creates a new Convergence                                                         |
| [`AddFigure`](#DirectionalAxialForce.AddFigure)                             | Creates a new child Figure.                                                       |
| [`AddImage`](#DirectionalAxialForce.AddImage)                               | Creates a new child Image.                                                        |
| [`ClearGeneratedData`](#DirectionalAxialForce.ClearGeneratedData)           | Run the ClearGeneratedData action.                                                |
| [`CopyTo`](#DirectionalAxialForce.CopyTo)                                   | Copies all visible properties from this object to another.                        |
| [`CreateParameter`](#DirectionalAxialForce.CreateParameter)                 | CreateParameter method.                                                           |
| [`CreateResultsAtAllSets`](#DirectionalAxialForce.CreateResultsAtAllSets)   | Creates results at all sets for results under a solution.                         |
| [`Delete`](#DirectionalAxialForce.Delete)                                   | Run the Delete action.                                                            |
| [`Duplicate`](#DirectionalAxialForce.Duplicate)                             | Creates a copy of the current DataModelObject.                                    |
| [`DuplicateWithoutResults`](#DirectionalAxialForce.DuplicateWithoutResults) | Run the DuplicateWithoutResults action.                                           |
| [`EvaluateAllResults`](#DirectionalAxialForce.EvaluateAllResults)           | Run the EvaluateAllResults action.                                                |
| [`ExportAnimation`](#DirectionalAxialForce.ExportAnimation)                 | Run the ExportAnimation action.                                                   |
| [`ExportToTextFile`](#DirectionalAxialForce.ExportToTextFile)               | Run the ExportToTextFile action.                                                  |
| [`FetchRemoteResults`](#DirectionalAxialForce.FetchRemoteResults)           | Run the FetchRemoteResult action.                                                 |
| [`GetChildren`](#DirectionalAxialForce.GetChildren)                         | Gets the list of children, filtered by type.                                      |
| [`GetParameter`](#DirectionalAxialForce.GetParameter)                       | Gets the parameter corresponding to the given property.                           |
| [`GroupAllSimilarChildren`](#DirectionalAxialForce.GroupAllSimilarChildren) | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#DirectionalAxialForce.GroupSimilarObjects)         | Run the GroupSimilarObjects action.                                               |
| [`PromoteToNamedSelection`](#DirectionalAxialForce.PromoteToNamedSelection) | Run the PromoteToNamedSelection action.                                           |
| [`PropertyByAPIName`](#DirectionalAxialForce.PropertyByAPIName)             | Get a property by its API name.                                                   |
| [`PropertyByName`](#DirectionalAxialForce.PropertyByName)                   | Get a property by its unique name.                                                |
| [`RemoveParameter`](#DirectionalAxialForce.RemoveParameter)                 | Removes the parameter from the parameter set corresponding to the given property. |
| [`RenameBasedOnDefinition`](#DirectionalAxialForce.RenameBasedOnDefinition) | Run the RenameBasedOnDefinition action.                                           |

### Properties

| Name | Description |
|-------------------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| [`Average`](#DirectionalAxialForce.Average)                                                     | Gets the Average.                                                      |
| [`BeamResultType`](#DirectionalAxialForce.BeamResultType)                                       | Gets or sets the BeamResultType.                                       |
| [`By`](#DirectionalAxialForce.By)                                                               | Gets or sets the By.                                                   |
| [`CalculateTimeHistory`](#DirectionalAxialForce.CalculateTimeHistory)                           | Gets or sets the CalculateTimeHistory.                                 |
| [`Children`](#DirectionalAxialForce.Children)                                                   | Gets the list of children.                                             |
| [`CombinationNumber`](#DirectionalAxialForce.CombinationNumber)                                 | Gets or sets the Combination Number for a Solution Combination result. |
| [`Comments`](#DirectionalAxialForce.Comments)                                                   | Gets the list of associated comments.                                  |
| [`CoordinateSystem`](#DirectionalAxialForce.CoordinateSystem)                                   | Gets or sets the Coordinate System.                                    |
| [`CrackFrontNumber`](#DirectionalAxialForce.CrackFrontNumber)                                   | Gets or sets the CrackFrontNumber.                                     |
| [`DataModelObjectCategory`](#DirectionalAxialForce.DataModelObjectCategory)                     | Gets the current DataModelObject’s category.                           |
| [`DisplayOption`](#DirectionalAxialForce.DisplayOption)                                         | Gets or sets the DisplayOption.                                        |
| [`DisplayTime`](#DirectionalAxialForce.DisplayTime)                                             | Gets or sets the DisplayTime.                                          |
| [`DpfEvaluation`](#DirectionalAxialForce.DpfEvaluation)                                         | Gets or sets the DpfEvaluation.                                        |
| [`Figures`](#DirectionalAxialForce.Figures)                                                     | Gets the list of associated figures.                                   |
| [`GlobalIDs`](#DirectionalAxialForce.GlobalIDs)                                                 | Gets or sets the GlobalIDs.                                            |
| [`GraphControlsXAxis`](#DirectionalAxialForce.GraphControlsXAxis)                               | Gets or sets the GraphControlsXAxis.                                   |
| [`Identifier`](#DirectionalAxialForce.Identifier)                                               | Gets or sets the Identifier.                                           |
| [`Images`](#DirectionalAxialForce.Images)                                                       | Gets the list of associated images.                                    |
| [`InternalObject`](#DirectionalAxialForce.InternalObject)                                       | Gets the internal object. For advanced usage only.                     |
| [`IsSolved`](#DirectionalAxialForce.IsSolved)                                                   | Gets the IsSolved.                                                     |
| [`ItemType`](#DirectionalAxialForce.ItemType)                                                   | Gets or sets the ItemType.                                             |
| [`IterationNumber`](#DirectionalAxialForce.IterationNumber)                                     | Gets the IterationNumber.                                              |
| [`LoadStep`](#DirectionalAxialForce.LoadStep)                                                   | Gets the LoadStep.                                                     |
| [`LoadStepForMaximumOfMaximumValues`](#DirectionalAxialForce.LoadStepForMaximumOfMaximumValues) | Get the Load Step for the maximum of maximum values.                   |
| [`LoadStepForMaximumOfMinimumValues`](#DirectionalAxialForce.LoadStepForMaximumOfMinimumValues) | Get the Load Step for the maximum of minimum values.                   |
| [`LoadStepForMinimumOfMaximumValues`](#DirectionalAxialForce.LoadStepForMinimumOfMaximumValues) | Get the Load Step for the minimum of maximum values.                   |
| [`LoadStepForMinimumOfMinimumValues`](#DirectionalAxialForce.LoadStepForMinimumOfMinimumValues) | Get the Load Step for the minimum of minimum values.                   |
| [`LoadStepNumber`](#DirectionalAxialForce.LoadStepNumber)                                       | Gets or sets the LoadStepNumber.                                       |
| [`Location`](#DirectionalAxialForce.Location)                                                   | Gets or sets the Location.                                             |
| [`Maximum`](#DirectionalAxialForce.Maximum)                                                     | Gets the Maximum.                                                      |
| [`MaximumOccursOn`](#DirectionalAxialForce.MaximumOccursOn)                                     | Gets the MaximumOccursOn.                                              |
| [`MaximumOfMaximumOverTime`](#DirectionalAxialForce.MaximumOfMaximumOverTime)                   | Gets the MaximumOfMaximumOverTime.                                     |
| [`MaximumOfMinimumOverTime`](#DirectionalAxialForce.MaximumOfMinimumOverTime)                   | Gets the MaximumOfMinimumOverTime.                                     |
| [`Minimum`](#DirectionalAxialForce.Minimum)                                                     | Gets the Minimum.                                                      |
| [`MinimumOccursOn`](#DirectionalAxialForce.MinimumOccursOn)                                     | Gets the MinimumOccursOn.                                              |
| [`MinimumOfMaximumOverTime`](#DirectionalAxialForce.MinimumOfMaximumOverTime)                   | Gets the MinimumOfMaximumOverTime.                                     |
| [`MinimumOfMinimumOverTime`](#DirectionalAxialForce.MinimumOfMinimumOverTime)                   | Gets the MinimumOfMinimumOverTime.                                     |
| [`NamedSelections`](#DirectionalAxialForce.NamedSelections)                                     | Gets or sets the NamedSelections.                                      |
| [`Path`](#DirectionalAxialForce.Path)                                                           | Path property.                                                         |
| [`PlotData`](#DirectionalAxialForce.PlotData)                                                   | Gets the result table.                                                 |
| [`Properties`](#DirectionalAxialForce.Properties)                                               | Gets the list of properties for this object.                           |
| [`ScopingMethod`](#DirectionalAxialForce.ScopingMethod)                                         | Gets or sets the ScopingMethod.                                        |
| [`SetNumber`](#DirectionalAxialForce.SetNumber)                                                 | Gets or sets the Set Number.                                           |
| [`SolutionCombinationDriver`](#DirectionalAxialForce.SolutionCombinationDriver)                 | Gets or sets the SolutionCombinationDriver.                            |
| [`SolverComponentIDs`](#DirectionalAxialForce.SolverComponentIDs)                               | Gets or sets the SolverComponentIDs.                                   |
| [`Substep`](#DirectionalAxialForce.Substep)                                                     | Gets the Substep.                                                      |
| [`Suppressed`](#DirectionalAxialForce.Suppressed)                                               | Gets or sets the Suppressed.                                           |
| [`Surface`](#DirectionalAxialForce.Surface)                                                     | Surface property.                                                      |
| [`Time`](#DirectionalAxialForce.Time)                                                           | Gets the Time.                                                         |
| [`TimeForMaximumOfMaximumValues`](#DirectionalAxialForce.TimeForMaximumOfMaximumValues)         | Get the Time for the maximum of maximum values.                        |
| [`TimeForMaximumOfMinimumValues`](#DirectionalAxialForce.TimeForMaximumOfMinimumValues)         | Get the Time for the maximum of minimum values.                        |
| [`TimeForMinimumOfMaximumValues`](#DirectionalAxialForce.TimeForMinimumOfMaximumValues)         | Get the Time for the minimum of maximum values.                        |
| [`TimeForMinimumOfMinimumValues`](#DirectionalAxialForce.TimeForMinimumOfMinimumValues)         | Get the Time for the minimum of minimum values.                        |
| [`VisibleProperties`](#DirectionalAxialForce.VisibleProperties)                                 | Gets the list of properties that are visible for this object.          |
| [`WaterfallPanelShowTextOnMosaic`](#DirectionalAxialForce.WaterfallPanelShowTextOnMosaic)       | Gets or sets the Waterfall Panel Mosaic Text Property.                 |

<a id="property-detail"></a>

## Property detail

<a id="DirectionalAxialForce.Average"></a>

### *property* DirectionalAxialForce.Average *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Average.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.BeamResultType"></a>

### *property* DirectionalAxialForce.BeamResultType *: [Ansys.Mechanical.DataModel.Enums.TotalOrDirectional](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/TotalOrDirectional.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.TotalOrDirectional) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the BeamResultType.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.By"></a>

### *property* DirectionalAxialForce.By *: [Ansys.Mechanical.DataModel.Enums.SetDriverStyle](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/SetDriverStyle.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.SetDriverStyle) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the By.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.CalculateTimeHistory"></a>

### *property* DirectionalAxialForce.CalculateTimeHistory *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the CalculateTimeHistory.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Children"></a>

### *property* DirectionalAxialForce.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.CombinationNumber"></a>

### *property* DirectionalAxialForce.CombinationNumber *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Combination Number for a Solution Combination result.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Comments"></a>

### *property* DirectionalAxialForce.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](../../Comment.md#ansys.mechanical.stubs.v241.Ansys.ACT.Automation.Mechanical.Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.CoordinateSystem"></a>

### *property* DirectionalAxialForce.CoordinateSystem *: [Ansys.ACT.Automation.Mechanical.CoordinateSystem](../../CoordinateSystem.md#ansys.mechanical.stubs.v241.Ansys.ACT.Automation.Mechanical.CoordinateSystem) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Coordinate System.
Accepts/Returns None for Solution Coordinate System in the general case (if applicable).
Accepts/Returns None for Fiber Coordinate System for a result that is sub scoped by ply.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.CrackFrontNumber"></a>

### *property* DirectionalAxialForce.CrackFrontNumber *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the CrackFrontNumber.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.DataModelObjectCategory"></a>

### *property* DirectionalAxialForce.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/DataModelObjectCategory.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.DisplayOption"></a>

### *property* DirectionalAxialForce.DisplayOption *: [Ansys.Mechanical.DataModel.Enums.ResultAveragingType](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/ResultAveragingType.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.ResultAveragingType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the DisplayOption.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.DisplayTime"></a>

### *property* DirectionalAxialForce.DisplayTime *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the DisplayTime.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.DpfEvaluation"></a>

### *property* DirectionalAxialForce.DpfEvaluation *: [Ansys.Mechanical.DataModel.Enums.DpfEvaluationType](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/DpfEvaluationType.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.DpfEvaluationType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the DpfEvaluation.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Figures"></a>

### *property* DirectionalAxialForce.Figures *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Figure](../../Figure.md#ansys.mechanical.stubs.v241.Ansys.ACT.Automation.Mechanical.Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.GlobalIDs"></a>

### *property* DirectionalAxialForce.GlobalIDs *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the GlobalIDs.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.GraphControlsXAxis"></a>

### *property* DirectionalAxialForce.GraphControlsXAxis *: [Ansys.Mechanical.DataModel.Enums.GraphControlsXAxis](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/GraphControlsXAxis.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.GraphControlsXAxis) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the GraphControlsXAxis.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Identifier"></a>

### *property* DirectionalAxialForce.Identifier *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Identifier.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Images"></a>

### *property* DirectionalAxialForce.Images *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Image](../../Image.md#ansys.mechanical.stubs.v241.Ansys.ACT.Automation.Mechanical.Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.InternalObject"></a>

### *property* DirectionalAxialForce.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSResultAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.IsSolved"></a>

### *property* DirectionalAxialForce.IsSolved *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the IsSolved.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.ItemType"></a>

### *property* DirectionalAxialForce.ItemType *: [Ansys.Mechanical.DataModel.Enums.ResultFileItemType](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/ResultFileItemType.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.ResultFileItemType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ItemType.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.IterationNumber"></a>

### *property* DirectionalAxialForce.IterationNumber *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the IterationNumber.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.LoadStep"></a>

### *property* DirectionalAxialForce.LoadStep *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the LoadStep.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.LoadStepForMaximumOfMaximumValues"></a>

### *property* DirectionalAxialForce.LoadStepForMaximumOfMaximumValues *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Load Step for the maximum of maximum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.LoadStepForMaximumOfMinimumValues"></a>

### *property* DirectionalAxialForce.LoadStepForMaximumOfMinimumValues *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Load Step for the maximum of minimum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.LoadStepForMinimumOfMaximumValues"></a>

### *property* DirectionalAxialForce.LoadStepForMinimumOfMaximumValues *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Load Step for the minimum of maximum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.LoadStepForMinimumOfMinimumValues"></a>

### *property* DirectionalAxialForce.LoadStepForMinimumOfMinimumValues *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Load Step for the minimum of minimum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.LoadStepNumber"></a>

### *property* DirectionalAxialForce.LoadStepNumber *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the LoadStepNumber.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Location"></a>

### *property* DirectionalAxialForce.Location *: Ansys.ACT.Interfaces.Common.ISelectionInfo | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Location.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Maximum"></a>

### *property* DirectionalAxialForce.Maximum *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Maximum.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.MaximumOccursOn"></a>

### *property* DirectionalAxialForce.MaximumOccursOn *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumOccursOn.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.MaximumOfMaximumOverTime"></a>

### *property* DirectionalAxialForce.MaximumOfMaximumOverTime *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumOfMaximumOverTime.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.MaximumOfMinimumOverTime"></a>

### *property* DirectionalAxialForce.MaximumOfMinimumOverTime *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MaximumOfMinimumOverTime.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Minimum"></a>

### *property* DirectionalAxialForce.Minimum *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Minimum.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.MinimumOccursOn"></a>

### *property* DirectionalAxialForce.MinimumOccursOn *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumOccursOn.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.MinimumOfMaximumOverTime"></a>

### *property* DirectionalAxialForce.MinimumOfMaximumOverTime *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumOfMaximumOverTime.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.MinimumOfMinimumOverTime"></a>

### *property* DirectionalAxialForce.MinimumOfMinimumOverTime *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the MinimumOfMinimumOverTime.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.NamedSelections"></a>

### *property* DirectionalAxialForce.NamedSelections *: System.Collections.Generic.IEnumerable[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the NamedSelections.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Path"></a>

### *property* DirectionalAxialForce.Path *: [Ansys.ACT.Automation.Mechanical.Path](../../../../../../../v242/Ansys/ACT/Automation/Mechanical/Path.md#ansys.mechanical.stubs.v242.Ansys.ACT.Automation.Mechanical.Path) | [None](https://docs.python.org/3/library/constants.html#None)*

Path property.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.PlotData"></a>

### *property* DirectionalAxialForce.PlotData *: [Ansys.Mechanical.DataModel.Results.ResultDataTable](../../../../../../../v242/Ansys/Mechanical/DataModel/Results/ResultDataTable.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Results.ResultDataTable) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the result table.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Properties"></a>

### *property* DirectionalAxialForce.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.ScopingMethod"></a>

### *property* DirectionalAxialForce.ScopingMethod *: [Ansys.Mechanical.DataModel.Enums.GeometryDefineByType](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/GeometryDefineByType.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.GeometryDefineByType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ScopingMethod.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.SetNumber"></a>

### *property* DirectionalAxialForce.SetNumber *: System.UInt32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Set Number.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.SolutionCombinationDriver"></a>

### *property* DirectionalAxialForce.SolutionCombinationDriver *: [Ansys.Mechanical.DataModel.Enums.SolutionCombinationDriverStyle](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/SolutionCombinationDriverStyle.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.SolutionCombinationDriverStyle) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the SolutionCombinationDriver.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.SolverComponentIDs"></a>

### *property* DirectionalAxialForce.SolverComponentIDs *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the SolverComponentIDs.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Substep"></a>

### *property* DirectionalAxialForce.Substep *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Substep.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Suppressed"></a>

### *property* DirectionalAxialForce.Suppressed *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Suppressed.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Surface"></a>

### *property* DirectionalAxialForce.Surface *: [Ansys.ACT.Automation.Mechanical.Surface](../../../../../../../v242/Ansys/ACT/Automation/Mechanical/Surface.md#ansys.mechanical.stubs.v242.Ansys.ACT.Automation.Mechanical.Surface) | [None](https://docs.python.org/3/library/constants.html#None)*

Surface property.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Time"></a>

### *property* DirectionalAxialForce.Time *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Time.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.TimeForMaximumOfMaximumValues"></a>

### *property* DirectionalAxialForce.TimeForMaximumOfMaximumValues *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Time for the maximum of maximum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.TimeForMaximumOfMinimumValues"></a>

### *property* DirectionalAxialForce.TimeForMaximumOfMinimumValues *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Time for the maximum of minimum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.TimeForMinimumOfMaximumValues"></a>

### *property* DirectionalAxialForce.TimeForMinimumOfMaximumValues *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Time for the minimum of maximum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.TimeForMinimumOfMinimumValues"></a>

### *property* DirectionalAxialForce.TimeForMinimumOfMinimumValues *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Get the Time for the minimum of minimum values.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.VisibleProperties"></a>

### *property* DirectionalAxialForce.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.WaterfallPanelShowTextOnMosaic"></a>

### *property* DirectionalAxialForce.WaterfallPanelShowTextOnMosaic *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Waterfall Panel Mosaic Text Property.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="DirectionalAxialForce.Activate"></a>

### DirectionalAxialForce.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.AddAlert"></a>

### DirectionalAxialForce.AddAlert()

Creates a new Alert

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.AddComment"></a>

### DirectionalAxialForce.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.AddConvergence"></a>

### DirectionalAxialForce.AddConvergence()

Creates a new Convergence

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.AddFigure"></a>

### DirectionalAxialForce.AddFigure()

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.AddImage"></a>

### DirectionalAxialForce.AddImage(filePath: System.String)

```text
Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.
```

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.ClearGeneratedData"></a>

### DirectionalAxialForce.ClearGeneratedData()

Run the ClearGeneratedData action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.CopyTo"></a>

### DirectionalAxialForce.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.CreateParameter"></a>

### DirectionalAxialForce.CreateParameter(propName: System.String)

CreateParameter method.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.CreateResultsAtAllSets"></a>

### DirectionalAxialForce.CreateResultsAtAllSets()

Creates results at all sets for results under a solution.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Delete"></a>

### DirectionalAxialForce.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.Duplicate"></a>

### DirectionalAxialForce.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.DuplicateWithoutResults"></a>

### DirectionalAxialForce.DuplicateWithoutResults()

Run the DuplicateWithoutResults action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.EvaluateAllResults"></a>

### DirectionalAxialForce.EvaluateAllResults()

Run the EvaluateAllResults action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.ExportAnimation"></a>

### DirectionalAxialForce.ExportAnimation(filePath: System.String, format: [Ansys.Mechanical.DataModel.Enums.GraphicsAnimationExportFormat](../../../../../../../v242/Ansys/Mechanical/DataModel/Enums/GraphicsAnimationExportFormat.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.DataModel.Enums.GraphicsAnimationExportFormat), settings: [Ansys.Mechanical.Graphics.AnimationExportSettings](../../../../../../../v242/Ansys/Mechanical/Graphics/AnimationExportSettings.md#ansys.mechanical.stubs.v242.Ansys.Mechanical.Graphics.AnimationExportSettings))

Run the ExportAnimation action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.ExportToTextFile"></a>

### DirectionalAxialForce.ExportToTextFile(filePath: System.String)

Run the ExportToTextFile action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.FetchRemoteResults"></a>

### DirectionalAxialForce.FetchRemoteResults()

Run the FetchRemoteResult action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.GetChildren"></a>

### DirectionalAxialForce.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.GetParameter"></a>

### DirectionalAxialForce.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.GroupAllSimilarChildren"></a>

### DirectionalAxialForce.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.GroupSimilarObjects"></a>

### DirectionalAxialForce.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.PromoteToNamedSelection"></a>

### DirectionalAxialForce.PromoteToNamedSelection()

Run the PromoteToNamedSelection action.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.PropertyByAPIName"></a>

### DirectionalAxialForce.PropertyByAPIName(name: System.String)

```text
Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.
```

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.PropertyByName"></a>

### DirectionalAxialForce.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.RemoveParameter"></a>

### DirectionalAxialForce.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="DirectionalAxialForce.RenameBasedOnDefinition"></a>

### DirectionalAxialForce.RenameBasedOnDefinition()

Run the RenameBasedOnDefinition action.

<!-- !! processed by numpydoc !! -->

