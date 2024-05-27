# ContactDataTable

<a id="ContactDataTable"></a>

### *class* ContactDataTable

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a ContactDataTable.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`ExportTextFile`](#ContactDataTable.ExportTextFile)                   | Run the ExportTextFile action.                                                    |
| [`Delete`](#ContactDataTable.Delete)                                   | Run the Delete action.                                                            |
| [`GetChildren`](#id1)                                                  | Gets the list of children, filtered by type.                                      |
| [`GetChildren`](#id1)                                                  | Gets the list of children, filtered by type.                                      |
| [`AddComment`](#ContactDataTable.AddComment)                           | Creates a new child Comment.                                                      |
| [`AddFigure`](#ContactDataTable.AddFigure)                             | Creates a new child Figure.                                                       |
| [`Activate`](#ContactDataTable.Activate)                               | Activate the current object.                                                      |
| [`CopyTo`](#ContactDataTable.CopyTo)                                   | Copies all visible properties from this object to another.                        |
| [`Duplicate`](#ContactDataTable.Duplicate)                             | Creates a copy of the current DataModelObject.                                    |
| [`GroupAllSimilarChildren`](#ContactDataTable.GroupAllSimilarChildren) | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#ContactDataTable.GroupSimilarObjects)         | Run the GroupSimilarObjects action.                                               |
| [`PropertyByName`](#ContactDataTable.PropertyByName)                   | Get a property by its unique name.                                                |
| [`PropertyByAPIName`](#ContactDataTable.PropertyByAPIName)             | Get a property by its API name.                                                   |
| [`CreateParameter`](#ContactDataTable.CreateParameter)                 | Creates a new parameter for a Property.                                           |
| [`GetParameter`](#ContactDataTable.GetParameter)                       | Gets the parameter corresponding to the given property.                           |
| [`RemoveParameter`](#ContactDataTable.RemoveParameter)                 | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Description |
|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| [`InternalObject`](#id0)                                                                                               | Gets the internal object. For advanced usage only.            |
| [`DataModelObjectCategory`](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                  |
| [`Children`](#ContactDataTable.Children)                                                                               | Gets the list of children.                                    |
| [`Comments`](#ContactDataTable.Comments)                                                                               | Gets the list of associated comments.                         |
| [`Figures`](#ContactDataTable.Figures)                                                                                 | Gets the list of associated figures.                          |
| [`InternalObject`](#id0)                                                                                               | Gets the internal object. For advanced usage only.            |
| [`Properties`](#ContactDataTable.Properties)                                                                           | Gets the list of properties for this object.                  |
| [`VisibleProperties`](#ContactDataTable.VisibleProperties)                                                             | Gets the list of properties that are visible for this object. |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical.Results import ContactDataTable
```

<a id="property-detail"></a>

## Property detail

<a id="ContactDataTable.InternalObject"></a>

### *property* ContactDataTable.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSContactDataTableAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.DataModelObjectCategory"></a>

### *property* ContactDataTable.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.Children"></a>

### *property* ContactDataTable.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.Comments"></a>

### *property* ContactDataTable.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](../Comment.md#Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.Figures"></a>

### *property* ContactDataTable.Figures *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Figure](../Figure.md#Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* ContactDataTable.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.Properties"></a>

### *property* ContactDataTable.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.VisibleProperties"></a>

### *property* ContactDataTable.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="ContactDataTable.ExportTextFile"></a>

### ContactDataTable.ExportTextFile(fileName: System.String)

Run the ExportTextFile action.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.Delete"></a>

### ContactDataTable.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.GetChildren"></a>

### ContactDataTable.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### ContactDataTable.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.AddComment"></a>

### ContactDataTable.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.AddFigure"></a>

### ContactDataTable.AddFigure()

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.Activate"></a>

### ContactDataTable.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.CopyTo"></a>

### ContactDataTable.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.Duplicate"></a>

### ContactDataTable.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.GroupAllSimilarChildren"></a>

### ContactDataTable.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.GroupSimilarObjects"></a>

### ContactDataTable.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.PropertyByName"></a>

### ContactDataTable.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.PropertyByAPIName"></a>

### ContactDataTable.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.CreateParameter"></a>

### ContactDataTable.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.GetParameter"></a>

### ContactDataTable.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="ContactDataTable.RemoveParameter"></a>

### ContactDataTable.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->