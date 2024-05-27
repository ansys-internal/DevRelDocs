# TemperatureConstraint

<a id="TemperatureConstraint"></a>

### *class* TemperatureConstraint

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a TemperatureConstraint.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Description |
|-------------------------------------------------------------------------------|-----------------------------------------------------------------------------------|
| [`RenameBasedOnDefinition`](#TemperatureConstraint.RenameBasedOnDefinition)   | Run the RenameBasedOnDefinition action.                                           |
| [`Delete`](#TemperatureConstraint.Delete)                                     | Run the Delete action.                                                            |
| [`GetChildren`](#id1)                                                         | Gets the list of children, filtered by type.                                      |
| [`GetChildren`](#id1)                                                         | Gets the list of children, filtered by type.                                      |
| [`Activate`](#TemperatureConstraint.Activate)                                 | Activate the current object.                                                      |
| [`CopyTo`](#TemperatureConstraint.CopyTo)                                     | Copies all visible properties from this object to another.                        |
| [`Duplicate`](#TemperatureConstraint.Duplicate)                               | Creates a copy of the current DataModelObject.                                    |
| [`GroupAllSimilarChildren`](#TemperatureConstraint.GroupAllSimilarChildren)   | Run the GroupAllSimilarChildren action.                                           |
| [`GroupSimilarObjects`](#TemperatureConstraint.GroupSimilarObjects)           | Run the GroupSimilarObjects action.                                               |
| [`PropertyByName`](#TemperatureConstraint.PropertyByName)                     | Get a property by its unique name.                                                |
| [`PropertyByAPIName`](#TemperatureConstraint.PropertyByAPIName)               | Get a property by its API name.                                                   |
| [`CreateParameter`](#TemperatureConstraint.CreateParameter)                   | Creates a new parameter for a Property.                                           |
| [`GetParameter`](#TemperatureConstraint.GetParameter)                         | Gets the parameter corresponding to the given property.                           |
| [`RemoveParameter`](#TemperatureConstraint.RemoveParameter)                   | Removes the parameter from the parameter set corresponding to the given property. |

### Properties

| Name | Description |
|---------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| [`InternalObject`](#id0)                                                                                            | Gets the internal object. For advanced usage only.                                       |
| [`TemperatureAbsMax`](#TemperatureConstraint.TemperatureAbsMax)                                                     | Gets or sets the TemperatureAbsMax.                                                      |
| [`ScopingMethod`](#TemperatureConstraint.ScopingMethod)                                                             | Gets or sets the ScopingMethod.                                                          |
| [`Location`](#TemperatureConstraint.Location)                                                                       | Gets or sets the Location.                                                               |
| [`DataModelObjectCategory`](../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                                             |
| [`EnvironmentSelection`](#TemperatureConstraint.EnvironmentSelection)                                               | Gets or Sets the EnvironmentSelection to an Analysis object or TopoEnvironmentType enum. |
| [`Suppressed`](#TemperatureConstraint.Suppressed)                                                                   | Gets or sets the Suppressed.                                                             |
| [`Children`](#TemperatureConstraint.Children)                                                                       | Gets the list of children.                                                               |
| [`InternalObject`](#id0)                                                                                            | Gets the internal object. For advanced usage only.                                       |
| [`Properties`](#TemperatureConstraint.Properties)                                                                   | Gets the list of properties for this object.                                             |
| [`VisibleProperties`](#TemperatureConstraint.VisibleProperties)                                                     | Gets the list of properties that are visible for this object.                            |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical import TemperatureConstraint
```

<a id="property-detail"></a>

## Property detail

<a id="TemperatureConstraint.InternalObject"></a>

### *property* TemperatureConstraint.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSTopoConstraintAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.TemperatureAbsMax"></a>

### *property* TemperatureConstraint.TemperatureAbsMax *: [Ansys.ACT.Mechanical.Fields.Field](../../Mechanical/Fields/Field.md#Field) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the TemperatureAbsMax.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.ScopingMethod"></a>

### *property* TemperatureConstraint.ScopingMethod *: [Ansys.Mechanical.DataModel.Enums.GeometryDefineByType](../../../Mechanical/DataModel/Enums/GeometryDefineByType.md#GeometryDefineByType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ScopingMethod.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.Location"></a>

### *property* TemperatureConstraint.Location *: Ansys.ACT.Interfaces.Common.ISelectionInfo | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Location.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.DataModelObjectCategory"></a>

### *property* TemperatureConstraint.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.EnvironmentSelection"></a>

### *property* TemperatureConstraint.EnvironmentSelection *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or Sets the EnvironmentSelection to an Analysis object or TopoEnvironmentType enum.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.Suppressed"></a>

### *property* TemperatureConstraint.Suppressed *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Suppressed.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.Children"></a>

### *property* TemperatureConstraint.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* TemperatureConstraint.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.Properties"></a>

### *property* TemperatureConstraint.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.VisibleProperties"></a>

### *property* TemperatureConstraint.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="TemperatureConstraint.RenameBasedOnDefinition"></a>

### TemperatureConstraint.RenameBasedOnDefinition()

Run the RenameBasedOnDefinition action.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.Delete"></a>

### TemperatureConstraint.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.GetChildren"></a>

### TemperatureConstraint.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### TemperatureConstraint.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.Activate"></a>

### TemperatureConstraint.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.CopyTo"></a>

### TemperatureConstraint.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.Duplicate"></a>

### TemperatureConstraint.Duplicate()

Creates a copy of the current DataModelObject.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.GroupAllSimilarChildren"></a>

### TemperatureConstraint.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.GroupSimilarObjects"></a>

### TemperatureConstraint.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.PropertyByName"></a>

### TemperatureConstraint.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.PropertyByAPIName"></a>

### TemperatureConstraint.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.CreateParameter"></a>

### TemperatureConstraint.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.GetParameter"></a>

### TemperatureConstraint.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="TemperatureConstraint.RemoveParameter"></a>

### TemperatureConstraint.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->