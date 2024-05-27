# SectionPlanes

<a id="SectionPlanes"></a>

### *class* SectionPlanes

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Represents the collection of section planes used by graphics

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|---------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [`Add`](#SectionPlanes.Add)           | Adds the given SectionPlane object to the collection to modify the view. Currently only 6 SectionPlane objects in the collection can be activated at once.   |
| [`Clear`](#SectionPlanes.Clear)       | Clears the collection of all SectionPlane objects.                                                                                                           |
| [`Remove`](#SectionPlanes.Remove)     | Removes the requested SectionPlane from the collection.                                                                                                      |
| [`RemoveAt`](#SectionPlanes.RemoveAt) | Removes the SectionPlane at the given index.                                                                                                                 |

### Properties

| Name | Description |
|---------------------------------------------------------|------------------------------------------------------------|
| [`ShowWholeElement`](#SectionPlanes.ShowWholeElement)   | Gets or Sets the Element Visibility of the Section Plane   |
| [`Capping`](#SectionPlanes.Capping)                     | Gets or Sets the Capping style of the Section Plane        |
| [`Count`](#SectionPlanes.Count)                         | The number of section planes in the collection.            |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.Mechanical.Graphics import SectionPlanes
```

<a id="property-detail"></a>

## Property detail

<a id="SectionPlanes.ShowWholeElement"></a>

### *property* SectionPlanes.ShowWholeElement *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or Sets the Element Visibility of the Section Plane

<!-- !! processed by numpydoc !! -->

<a id="SectionPlanes.Capping"></a>

### *property* SectionPlanes.Capping *: [Ansys.Mechanical.DataModel.Enums.SectionPlaneCappingType](../DataModel/Enums/SectionPlaneCappingType.md#SectionPlaneCappingType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or Sets the Capping style of the Section Plane

<!-- !! processed by numpydoc !! -->

<a id="SectionPlanes.Count"></a>

### *property* SectionPlanes.Count *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

The number of section planes in the collection.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="SectionPlanes.Add"></a>

### SectionPlanes.Add(sectionPlane: [Ansys.Mechanical.Graphics.SectionPlane](SectionPlane.md#SectionPlane))

Adds the given SectionPlane object to the collection to modify the view. Currently only 6 SectionPlane objects in the collection can be activated at once.

<!-- !! processed by numpydoc !! -->

<a id="SectionPlanes.Clear"></a>

### SectionPlanes.Clear()

Clears the collection of all SectionPlane objects.

<!-- !! processed by numpydoc !! -->

<a id="SectionPlanes.Remove"></a>

### SectionPlanes.Remove(sectionPlane: [Ansys.Mechanical.Graphics.SectionPlane](SectionPlane.md#SectionPlane))

Removes the requested SectionPlane from the collection.

<!-- !! processed by numpydoc !! -->

<a id="SectionPlanes.RemoveAt"></a>

### SectionPlanes.RemoveAt(index: System.Int32)

Removes the SectionPlane at the given index.

<!-- !! processed by numpydoc !! -->