# ObjectTag

<a id="ObjectTag"></a>

### *class* ObjectTag

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> An instance of an ObjectTag.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|-------------------------------------------|----------------------------------|
| [`AddObject`](#ObjectTag.AddObject)       | Add an object to this tag.       |
| [`RemoveObject`](#ObjectTag.RemoveObject) | Remove an object from this tag.  |
| [`ClearObjects`](#ObjectTag.ClearObjects) | Clear all objects from this tag. |

### Properties

| Name | Description |
|---------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`Name`](#ObjectTag.Name)       | The name of the tag. If the tag exists in ObjectTags, attempting to set the name to a value of another tag in that collection will lead to an exception.   |
| [`Objects`](#ObjectTag.Objects) | The list of objects which use this tag.                                                                                                                    |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.Mechanical.Application import ObjectTag
```

<a id="property-detail"></a>

## Property detail

<a id="ObjectTag.Name"></a>

### *property* ObjectTag.Name *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

The name of the tag. If the tag exists in ObjectTags, attempting to set the name to a value of another tag in that collection will lead to an exception.

<!-- !! processed by numpydoc !! -->

<a id="ObjectTag.Objects"></a>

### *property* ObjectTag.Objects *: System.Collections.Generic.IEnumerable[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

The list of objects which use this tag.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="ObjectTag.AddObject"></a>

### ObjectTag.AddObject(obj: Ansys.Mechanical.DataModel.Interfaces.IDataModelObject)

Add an object to this tag.

<!-- !! processed by numpydoc !! -->

<a id="ObjectTag.RemoveObject"></a>

### ObjectTag.RemoveObject(obj: Ansys.Mechanical.DataModel.Interfaces.IDataModelObject)

Remove an object from this tag.

<!-- !! processed by numpydoc !! -->

<a id="ObjectTag.ClearObjects"></a>

### ObjectTag.ClearObjects()

Clear all objects from this tag.

<!-- !! processed by numpydoc !! -->