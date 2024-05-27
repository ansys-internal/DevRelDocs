# ContactSizing

<a id="ContactSizing"></a>

### *class* ContactSizing

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a ContactSizing.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|---------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`GenerateMesh`](#ContactSizing.GenerateMesh)                       | Generate the Mesh.                                                                |
| [`RenameBasedOnDefinition`](#ContactSizing.RenameBasedOnDefinition) | Run the RenameBasedOnDefinition action.                                           |
| [`Delete`](#ContactSizing.Delete)                                   | Run the Delete action.                                                            |
| [`GetChildren`](#id1)                                               | Gets the list of children, filtered by type.                                      |
| [`GetChildren`](#id1)                                               | Gets the list of children, filtered by type.                                      |
| [`AddComment`](#ContactSizing.AddComment)                           | Creates a new child Comment.                                                      |
| [`AddFigure`](#ContactSizing.AddFigure)                             | Creates a new child Figure.                                                       |
| [`AddImage`](#ContactSizing.AddImage)                               | Creates a new child Image.                                                        |
| [`Activate`](#ContactSizing.Activate)                               | Activate the current object.                                                      |
| [`CopyTo`](#ContactSizing.CopyTo)                                   | Copies all visible properties from this object to another.                        |
| [`Duplicate`](#ContactSizing.Duplicate)                             | Creates a copy of the current DataModelObject.                                    |
| [`GroupAllSimilarChildren`](#ContactSizing.GroupAllSimilarChildren) | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#ContactSizing.GroupSimilarObjects)         | Run the GroupSimilarObjects action.                                               |
| [`PropertyByName`](#ContactSizing.PropertyByName)                   | Get a property by its unique name.                                                |
| [`PropertyByAPIName`](#ContactSizing.PropertyByAPIName)             | Get a property by its API name.                                                   |
| [`CreateParameter`](#ContactSizing.CreateParameter)                 | Creates a new parameter for a Property.                                           |
| [`GetParameter`](#ContactSizing.GetParameter)                       | Gets the parameter corresponding to the given property.                           |
| [`RemoveParameter`](#ContactSizing.RemoveParameter)                 | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Description |
|------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| [`InternalObject`](#id0)                                                                                               | Gets the internal object. For advanced usage only.            |
| [`Relevance`](Relevance.md#Relevance)                                                                                  | Gets or sets the Relevance.                                   |
| [`Type`](#ContactSizing.Type)                                                                                          | Gets or sets the Type.                                        |
| [`ElementSize`](#ContactSizing.ElementSize)                                                                            | Gets or sets the ElementSize.                                 |
| [`ContactRegion`](../Connections/ContactRegion.md#ContactRegion)                                                       | Gets or sets the ContactRegion.                               |
| [`DataModelObjectCategory`](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                  |
| [`ScopingMethod`](#ContactSizing.ScopingMethod)                                                                        | Gets or sets the ScopingMethod.                               |
| [`Suppressed`](#ContactSizing.Suppressed)                                                                              | Gets or sets the Suppressed.                                  |
| [`Children`](#ContactSizing.Children)                                                                                  | Gets the list of children.                                    |
| [`Comments`](#ContactSizing.Comments)                                                                                  | Gets the list of associated comments.                         |
| [`Figures`](#ContactSizing.Figures)                                                                                    | Gets the list of associated figures.                          |
| [`Images`](#ContactSizing.Images)                                                                                      | Gets the list of associated images.                           |
| [`InternalObject`](#id0)                                                                                               | Gets the internal object. For advanced usage only.            |
| [`Properties`](#ContactSizing.Properties)                                                                              | Gets the list of properties for this object.                  |
| [`VisibleProperties`](#ContactSizing.VisibleProperties)                                                                | Gets the list of properties that are visible for this object. |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical.MeshControls import ContactSizing
```

<a id="property-detail"></a>

## Property detail

<a id="ContactSizing.InternalObject"></a>

### *property* ContactSizing.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSMeshControlAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Relevance"></a>

### *property* ContactSizing.Relevance *: System.Double | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Relevance.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Type"></a>

### *property* ContactSizing.Type *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Type.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.ElementSize"></a>

### *property* ContactSizing.ElementSize *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ElementSize.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.ContactRegion"></a>

### *property* ContactSizing.ContactRegion *: [Ansys.ACT.Automation.Mechanical.Connections.ContactRegion](../Connections/ContactRegion.md#ContactRegion) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ContactRegion.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.DataModelObjectCategory"></a>

### *property* ContactSizing.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.ScopingMethod"></a>

### *property* ContactSizing.ScopingMethod *: [Ansys.Mechanical.DataModel.Enums.GeometryDefineByType](../../../../Mechanical/DataModel/Enums/GeometryDefineByType.md#GeometryDefineByType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ScopingMethod.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Suppressed"></a>

### *property* ContactSizing.Suppressed *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Suppressed.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Children"></a>

### *property* ContactSizing.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Comments"></a>

### *property* ContactSizing.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](../Comment.md#Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Figures"></a>

### *property* ContactSizing.Figures *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Figure](../Figure.md#Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Images"></a>

### *property* ContactSizing.Images *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Image](../Image.md#Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* ContactSizing.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Properties"></a>

### *property* ContactSizing.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.VisibleProperties"></a>

### *property* ContactSizing.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="ContactSizing.GenerateMesh"></a>

### ContactSizing.GenerateMesh()

Generate the Mesh.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.RenameBasedOnDefinition"></a>

### ContactSizing.RenameBasedOnDefinition()

Run the RenameBasedOnDefinition action.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Delete"></a>

### ContactSizing.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.GetChildren"></a>

### ContactSizing.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### ContactSizing.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.AddComment"></a>

### ContactSizing.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.AddFigure"></a>

### ContactSizing.AddFigure()

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.AddImage"></a>

### ContactSizing.AddImage(filePath: System.String)

Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Activate"></a>

### ContactSizing.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.CopyTo"></a>

### ContactSizing.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.Duplicate"></a>

### ContactSizing.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.GroupAllSimilarChildren"></a>

### ContactSizing.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.GroupSimilarObjects"></a>

### ContactSizing.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.PropertyByName"></a>

### ContactSizing.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.PropertyByAPIName"></a>

### ContactSizing.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.CreateParameter"></a>

### ContactSizing.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.GetParameter"></a>

### ContactSizing.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="ContactSizing.RemoveParameter"></a>

### ContactSizing.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->