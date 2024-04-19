<a id="topologyelementaldensity"></a>

# TopologyElementalDensity

<a id="TopologyElementalDensity"></a>

### *class* TopologyElementalDensity

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a TopologyElementalDensity.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Summary |
|--------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`ClearGeneratedData`](#TopologyElementalDensity.ClearGeneratedData)           | Clears the result.                                                                |
| [`EvaluateAllResults`](#TopologyElementalDensity.EvaluateAllResults)           | Run the EvaluateAllResults action.                                                |
| [`ExportAnimation`](#TopologyElementalDensity.ExportAnimation)                 | Run the ExportAnimation action.                                                   |
| [`RenameBasedOnDefinition`](#TopologyElementalDensity.RenameBasedOnDefinition) | Run the RenameBasedOnDefinition action.                                           |
| [`Delete`](#TopologyElementalDensity.Delete)                                   | Run the Delete action.                                                            |
| [`GetChildren`](#id1)                                                          | Gets the list of children, filtered by type.                                      |
| [`GetChildren`](#id1)                                                          | Gets the list of children, filtered by type.                                      |
| [`AddComment`](#TopologyElementalDensity.AddComment)                           | Creates a new child Comment.                                                      |
| [`AddFigure`](#TopologyElementalDensity.AddFigure)                             | Creates a new child Figure.                                                       |
| [`AddImage`](#TopologyElementalDensity.AddImage)                               | Creates a new child Image.                                                        |
| [`Activate`](#TopologyElementalDensity.Activate)                               | Activate the current object.                                                      |
| [`CopyTo`](#TopologyElementalDensity.CopyTo)                                   | Copies all visible properties from this object to another.                        |
| [`Duplicate`](#TopologyElementalDensity.Duplicate)                             | Creates a copy of the current DataModelObject.                                    |
| [`GroupAllSimilarChildren`](#TopologyElementalDensity.GroupAllSimilarChildren) | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#TopologyElementalDensity.GroupSimilarObjects)         | Run the GroupSimilarObjects action.                                               |
| [`PropertyByName`](#TopologyElementalDensity.PropertyByName)                   | Get a property by its unique name.                                                |
| [`PropertyByAPIName`](#TopologyElementalDensity.PropertyByAPIName)             | Get a property by its API name.                                                   |
| [`CreateParameter`](#TopologyElementalDensity.CreateParameter)                 | Creates a new parameter for a Property.                                           |
| [`GetParameter`](#TopologyElementalDensity.GetParameter)                       | Gets the parameter corresponding to the given property.                           |
| [`RemoveParameter`](#TopologyElementalDensity.RemoveParameter)                 | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Summary |
|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| [`InternalObject`](#id0)                                                                                               | Gets the internal object. For advanced usage only.            |
| [`RetainedThreshold`](#TopologyElementalDensity.RetainedThreshold)                                                     | Gets or sets the RetainedThreshold.                           |
| [`DataModelObjectCategory`](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                  |
| [`Location`](#TopologyElementalDensity.Location)                                                                       | Gets or sets the Location.                                    |
| [`IterationNumber`](#TopologyElementalDensity.IterationNumber)                                                         | Gets the IterationNumber.                                     |
| [`IterationStep`](#TopologyElementalDensity.IterationStep)                                                             | Gets or sets the IterationStep.                               |
| [`Maximum`](#TopologyElementalDensity.Maximum)                                                                         | Gets the Maximum.                                             |
| [`Minimum`](#TopologyElementalDensity.Minimum)                                                                         | Gets the Minimum.                                             |
| [`PercentMassOfOriginal`](#TopologyElementalDensity.PercentMassOfOriginal)                                             | Gets the PercentMassOfOriginal.                               |
| [`PercentVolumeOfOriginal`](#TopologyElementalDensity.PercentVolumeOfOriginal)                                         | Gets the PercentVolumeOfOriginal.                             |
| [`FinalMass`](#TopologyElementalDensity.FinalMass)                                                                     | Gets the FinalMass.                                           |
| [`FinalVolume`](#TopologyElementalDensity.FinalVolume)                                                                 | Gets the FinalVolume.                                         |
| [`OriginalMass`](#TopologyElementalDensity.OriginalMass)                                                               | Gets the OriginalMass.                                        |
| [`OriginalVolume`](#TopologyElementalDensity.OriginalVolume)                                                           | Gets the OriginalVolume.                                      |
| [`ScopingMethod`](#TopologyElementalDensity.ScopingMethod)                                                             | Gets or sets the ScopingMethod.                               |
| [`ShowOptimizedRegion`](#TopologyElementalDensity.ShowOptimizedRegion)                                                 | Gets or sets the ShowOptimizedRegion.                         |
| [`CalculateTimeHistory`](#TopologyElementalDensity.CalculateTimeHistory)                                               | Gets or sets the CalculateTimeHistory.                        |
| [`ExclusionsParticipation`](#TopologyElementalDensity.ExclusionsParticipation)                                         | Gets or sets the ExclusionsParticipation.                     |
| [`Suppressed`](#TopologyElementalDensity.Suppressed)                                                                   | Gets or sets the Suppressed.                                  |
| [`Selection`](#TopologyElementalDensity.Selection)                                                                     | Gets or sets the Selection.                                   |
| [`Children`](#TopologyElementalDensity.Children)                                                                       | Gets the list of children.                                    |
| [`Comments`](#TopologyElementalDensity.Comments)                                                                       | Gets the list of associated comments.                         |
| [`Figures`](#TopologyElementalDensity.Figures)                                                                         | Gets the list of associated figures.                          |
| [`Images`](#TopologyElementalDensity.Images)                                                                           | Gets the list of associated images.                           |
| [`InternalObject`](#id0)                                                                                               | Gets the internal object. For advanced usage only.            |
| [`Properties`](#TopologyElementalDensity.Properties)                                                                   | Gets the list of properties for this object.                  |
| [`VisibleProperties`](#TopologyElementalDensity.VisibleProperties)                                                     | Gets the list of properties that are visible for this object. |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical.Results import TopologyElementalDensity
```

<a id="property-detail"></a>

## Property detail

<a id="TopologyElementalDensity.InternalObject"></a>

### *property* TopologyElementalDensity.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSResultAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.RetainedThreshold"></a>

### *property* TopologyElementalDensity.RetainedThreshold *: System.Double | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the RetainedThreshold.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.DataModelObjectCategory"></a>

### *property* TopologyElementalDensity.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Location"></a>

### *property* TopologyElementalDensity.Location *: Ansys.ACT.Interfaces.Common.ISelectionInfo | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Location.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.IterationNumber"></a>

### *property* TopologyElementalDensity.IterationNumber *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the IterationNumber.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.IterationStep"></a>

### *property* TopologyElementalDensity.IterationStep *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the IterationStep.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Maximum"></a>

### *property* TopologyElementalDensity.Maximum *: System.Double | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Maximum.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Minimum"></a>

### *property* TopologyElementalDensity.Minimum *: System.Double | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Minimum.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.PercentMassOfOriginal"></a>

### *property* TopologyElementalDensity.PercentMassOfOriginal *: System.Double | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the PercentMassOfOriginal.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.PercentVolumeOfOriginal"></a>

### *property* TopologyElementalDensity.PercentVolumeOfOriginal *: System.Double | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the PercentVolumeOfOriginal.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.FinalMass"></a>

### *property* TopologyElementalDensity.FinalMass *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the FinalMass.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.FinalVolume"></a>

### *property* TopologyElementalDensity.FinalVolume *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the FinalVolume.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.OriginalMass"></a>

### *property* TopologyElementalDensity.OriginalMass *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the OriginalMass.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.OriginalVolume"></a>

### *property* TopologyElementalDensity.OriginalVolume *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the OriginalVolume.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.ScopingMethod"></a>

### *property* TopologyElementalDensity.ScopingMethod *: [Ansys.Mechanical.DataModel.Enums.GeometryDefineByType](../../../../Mechanical/DataModel/Enums/GeometryDefineByType.md#GeometryDefineByType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ScopingMethod.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.ShowOptimizedRegion"></a>

### *property* TopologyElementalDensity.ShowOptimizedRegion *: [Ansys.Mechanical.DataModel.Enums.TopologyOptimizationResultShowType](../../../../Mechanical/DataModel/Enums/TopologyOptimizationResultShowType.md#TopologyOptimizationResultShowType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ShowOptimizedRegion.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.CalculateTimeHistory"></a>

### *property* TopologyElementalDensity.CalculateTimeHistory *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the CalculateTimeHistory.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.ExclusionsParticipation"></a>

### *property* TopologyElementalDensity.ExclusionsParticipation *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ExclusionsParticipation.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Suppressed"></a>

### *property* TopologyElementalDensity.Suppressed *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Suppressed.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Selection"></a>

### *property* TopologyElementalDensity.Selection *: [Ansys.ACT.Automation.Mechanical.OptimizationRegion](../OptimizationRegion.md#OptimizationRegion) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Selection.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Children"></a>

### *property* TopologyElementalDensity.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Comments"></a>

### *property* TopologyElementalDensity.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](../Comment.md#Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Figures"></a>

### *property* TopologyElementalDensity.Figures *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Figure](../Figure.md#Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Images"></a>

### *property* TopologyElementalDensity.Images *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Image](../Image.md#Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* TopologyElementalDensity.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Properties"></a>

### *property* TopologyElementalDensity.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.VisibleProperties"></a>

### *property* TopologyElementalDensity.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="TopologyElementalDensity.ClearGeneratedData"></a>

### TopologyElementalDensity.ClearGeneratedData()

Clears the result.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.EvaluateAllResults"></a>

### TopologyElementalDensity.EvaluateAllResults()

Run the EvaluateAllResults action.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.ExportAnimation"></a>

### TopologyElementalDensity.ExportAnimation(filePath: System.String, format: [Ansys.Mechanical.DataModel.Enums.GraphicsAnimationExportFormat](../../../../Mechanical/DataModel/Enums/GraphicsAnimationExportFormat.md#GraphicsAnimationExportFormat), settings: [Ansys.Mechanical.Graphics.AnimationExportSettings](../../../../Mechanical/Graphics/AnimationExportSettings.md#AnimationExportSettings))

Run the ExportAnimation action.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.RenameBasedOnDefinition"></a>

### TopologyElementalDensity.RenameBasedOnDefinition()

Run the RenameBasedOnDefinition action.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Delete"></a>

### TopologyElementalDensity.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.GetChildren"></a>

### TopologyElementalDensity.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### TopologyElementalDensity.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.AddComment"></a>

### TopologyElementalDensity.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.AddFigure"></a>

### TopologyElementalDensity.AddFigure()

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.AddImage"></a>

### TopologyElementalDensity.AddImage(filePath: System.String)

Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Activate"></a>

### TopologyElementalDensity.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.CopyTo"></a>

### TopologyElementalDensity.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.Duplicate"></a>

### TopologyElementalDensity.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.GroupAllSimilarChildren"></a>

### TopologyElementalDensity.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.GroupSimilarObjects"></a>

### TopologyElementalDensity.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.PropertyByName"></a>

### TopologyElementalDensity.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.PropertyByAPIName"></a>

### TopologyElementalDensity.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.CreateParameter"></a>

### TopologyElementalDensity.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.GetParameter"></a>

### TopologyElementalDensity.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="TopologyElementalDensity.RemoveParameter"></a>

### TopologyElementalDensity.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->