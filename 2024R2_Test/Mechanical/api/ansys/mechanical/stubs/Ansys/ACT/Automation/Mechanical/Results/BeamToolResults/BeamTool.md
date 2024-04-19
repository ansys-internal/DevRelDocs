<a id="beamtool"></a>

# BeamTool

<a id="BeamTool"></a>

### *class* BeamTool

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a BeamTool.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Summary |
|--------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`EvaluateAllResults`](#BeamTool.EvaluateAllResults)               | Run the EvaluateAllResults action.                                                |
| [`AddDirectionalDeformation`](#BeamTool.AddDirectionalDeformation) | Creates a new DirectionalDeformation                                              |
| [`AddDirectStress`](#BeamTool.AddDirectStress)                     | Creates a new DirectStress                                                        |
| [`AddMaximumBendingStress`](#BeamTool.AddMaximumBendingStress)     | Creates a new MaximumBendingStress                                                |
| [`AddMaximumCombinedStress`](#BeamTool.AddMaximumCombinedStress)   | Creates a new MaximumCombinedStress                                               |
| [`AddMinimumBendingStress`](#BeamTool.AddMinimumBendingStress)     | Creates a new MinimumBendingStress                                                |
| [`AddMinimumCombinedStress`](#BeamTool.AddMinimumCombinedStress)   | Creates a new MinimumCombinedStress                                               |
| [`AddTotalDeformation`](#BeamTool.AddTotalDeformation)             | Creates a new TotalDeformation                                                    |
| [`Delete`](#BeamTool.Delete)                                       | Run the Delete action.                                                            |
| [`GetChildren`](#id1)                                              | Gets the list of children, filtered by type.                                      |
| [`GetChildren`](#id1)                                              | Gets the list of children, filtered by type.                                      |
| [`AddComment`](#BeamTool.AddComment)                               | Creates a new child Comment.                                                      |
| [`AddFigure`](#BeamTool.AddFigure)                                 | Creates a new child Figure.                                                       |
| [`AddImage`](#BeamTool.AddImage)                                   | Creates a new child Image.                                                        |
| [`Activate`](#BeamTool.Activate)                                   | Activate the current object.                                                      |
| [`CopyTo`](#BeamTool.CopyTo)                                       | Copies all visible properties from this object to another.                        |
| [`Duplicate`](#BeamTool.Duplicate)                                 | Creates a copy of the current DataModelObject.                                    |
| [`GroupAllSimilarChildren`](#BeamTool.GroupAllSimilarChildren)     | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#BeamTool.GroupSimilarObjects)             | Run the GroupSimilarObjects action.                                               |
| [`PropertyByName`](#BeamTool.PropertyByName)                       | Get a property by its unique name.                                                |
| [`PropertyByAPIName`](#BeamTool.PropertyByAPIName)                 | Get a property by its API name.                                                   |
| [`CreateParameter`](#BeamTool.CreateParameter)                     | Creates a new parameter for a Property.                                           |
| [`GetParameter`](#BeamTool.GetParameter)                           | Gets the parameter corresponding to the given property.                           |
| [`RemoveParameter`](#BeamTool.RemoveParameter)                     | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Summary |
|---------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| [`InternalObject`](#id0)                                                                                                  | Gets the internal object. For advanced usage only.            |
| [`Location`](#BeamTool.Location)                                                                                          | Gets or sets the Location.                                    |
| [`DataModelObjectCategory`](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                  |
| [`Children`](#BeamTool.Children)                                                                                          | Gets the list of children.                                    |
| [`Comments`](#BeamTool.Comments)                                                                                          | Gets the list of associated comments.                         |
| [`Figures`](#BeamTool.Figures)                                                                                            | Gets the list of associated figures.                          |
| [`Images`](#BeamTool.Images)                                                                                              | Gets the list of associated images.                           |
| [`InternalObject`](#id0)                                                                                                  | Gets the internal object. For advanced usage only.            |
| [`Properties`](#BeamTool.Properties)                                                                                      | Gets the list of properties for this object.                  |
| [`VisibleProperties`](#BeamTool.VisibleProperties)                                                                        | Gets the list of properties that are visible for this object. |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical.Results.BeamToolResults import BeamTool
```

<a id="property-detail"></a>

## Property detail

<a id="BeamTool.InternalObject"></a>

### *property* BeamTool.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSBeamToolAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Location"></a>

### *property* BeamTool.Location *: Ansys.ACT.Interfaces.Common.ISelectionInfo | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Location.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.DataModelObjectCategory"></a>

### *property* BeamTool.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Children"></a>

### *property* BeamTool.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Comments"></a>

### *property* BeamTool.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](../../Comment.md#Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Figures"></a>

### *property* BeamTool.Figures *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Figure](../../Figure.md#Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Images"></a>

### *property* BeamTool.Images *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Image](../../Image.md#Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* BeamTool.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Properties"></a>

### *property* BeamTool.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.VisibleProperties"></a>

### *property* BeamTool.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="BeamTool.EvaluateAllResults"></a>

### BeamTool.EvaluateAllResults()

Run the EvaluateAllResults action.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddDirectionalDeformation"></a>

### BeamTool.AddDirectionalDeformation()

Creates a new DirectionalDeformation

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddDirectStress"></a>

### BeamTool.AddDirectStress()

Creates a new DirectStress

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddMaximumBendingStress"></a>

### BeamTool.AddMaximumBendingStress()

Creates a new MaximumBendingStress

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddMaximumCombinedStress"></a>

### BeamTool.AddMaximumCombinedStress()

Creates a new MaximumCombinedStress

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddMinimumBendingStress"></a>

### BeamTool.AddMinimumBendingStress()

Creates a new MinimumBendingStress

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddMinimumCombinedStress"></a>

### BeamTool.AddMinimumCombinedStress()

Creates a new MinimumCombinedStress

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddTotalDeformation"></a>

### BeamTool.AddTotalDeformation()

Creates a new TotalDeformation

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Delete"></a>

### BeamTool.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.GetChildren"></a>

### BeamTool.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### BeamTool.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddComment"></a>

### BeamTool.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddFigure"></a>

### BeamTool.AddFigure()

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.AddImage"></a>

### BeamTool.AddImage(filePath: System.String)

Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Activate"></a>

### BeamTool.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.CopyTo"></a>

### BeamTool.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.Duplicate"></a>

### BeamTool.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.GroupAllSimilarChildren"></a>

### BeamTool.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.GroupSimilarObjects"></a>

### BeamTool.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.PropertyByName"></a>

### BeamTool.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.PropertyByAPIName"></a>

### BeamTool.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.CreateParameter"></a>

### BeamTool.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.GetParameter"></a>

### BeamTool.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="BeamTool.RemoveParameter"></a>

### BeamTool.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->