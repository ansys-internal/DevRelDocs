<a id="meshcontrolworksheet"></a>

# MeshControlWorksheet

<a id="MeshControlWorksheet"></a>

### *class* MeshControlWorksheet

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> MeshControlWorksheet class.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Summary |
|--------------------------------------------------------------------|------------------------------------------------|
| [`AddRow`](#MeshControlWorksheet.AddRow)                           | Add a row to the MeshControlWorksheet          |
| [`DeleteRow`](#MeshControlWorksheet.DeleteRow)                     | Delete a row from the MeshControlWorksheet     |
| [`GetActiveState`](#MeshControlWorksheet.GetActiveState)           | Gets the Active State property at row index    |
| [`SetActiveState`](#MeshControlWorksheet.SetActiveState)           | Sets the Active State property at row index    |
| [`GetNamedSelectionId`](#MeshControlWorksheet.GetNamedSelectionId) | Gets the ID of the NamedSelection at row index |
| [`GetNamedSelection`](#MeshControlWorksheet.GetNamedSelection)     | Gets the NamedSelection at row index           |
| [`SetNamedSelectionId`](#MeshControlWorksheet.SetNamedSelectionId) | Sets the NamedSelection by ID at row index     |
| [`SetNamedSelection`](#MeshControlWorksheet.SetNamedSelection)     | Sets the NamedSelection at row index           |
| [`GenerateMesh`](#MeshControlWorksheet.GenerateMesh)               | Geneate Mesh                                   |
| [`ClearGenerateMesh`](#MeshControlWorksheet.ClearGenerateMesh)     | Clear Mesh                                     |
| [`GenerateAtRow`](#MeshControlWorksheet.GenerateAtRow)             | Generate Mesh At Row                           |
| [`DeleteAllRows`](#MeshControlWorksheet.DeleteAllRows)             | Delete All Rows                                |

### Properties

| Name | Summary |
|------------------------------------------------|------------------------------|
| [`RowCount`](#MeshControlWorksheet.RowCount)   | Gets the number of entries   |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical import MeshControlWorksheet
```

<a id="property-detail"></a>

## Property detail

<a id="MeshControlWorksheet.RowCount"></a>

### *property* MeshControlWorksheet.RowCount *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the number of entries

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="MeshControlWorksheet.AddRow"></a>

### MeshControlWorksheet.AddRow()

Add a row to the MeshControlWorksheet

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.DeleteRow"></a>

### MeshControlWorksheet.DeleteRow(index: System.Int32)

Delete a row from the MeshControlWorksheet

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.GetActiveState"></a>

### MeshControlWorksheet.GetActiveState(index: System.Int32)

Gets the Active State property at row index

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.SetActiveState"></a>

### MeshControlWorksheet.SetActiveState(index: System.Int32, value: System.Boolean)

Sets the Active State property at row index

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.GetNamedSelectionId"></a>

### MeshControlWorksheet.GetNamedSelectionId(index: System.Int32)

Gets the ID of the NamedSelection at row index

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.GetNamedSelection"></a>

### MeshControlWorksheet.GetNamedSelection(index: System.Int32)

Gets the NamedSelection at row index

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.SetNamedSelectionId"></a>

### MeshControlWorksheet.SetNamedSelectionId(index: System.Int32, value: System.UInt32)

Sets the NamedSelection by ID at row index

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.SetNamedSelection"></a>

### MeshControlWorksheet.SetNamedSelection(index: System.Int32, value: [Ansys.ACT.Automation.Mechanical.NamedSelection](NamedSelection.md#NamedSelection))

Sets the NamedSelection at row index

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.GenerateMesh"></a>

### MeshControlWorksheet.GenerateMesh()

Geneate Mesh

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.ClearGenerateMesh"></a>

### MeshControlWorksheet.ClearGenerateMesh()

Clear Mesh

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.GenerateAtRow"></a>

### MeshControlWorksheet.GenerateAtRow(index: System.Int32)

Generate Mesh At Row

<!-- !! processed by numpydoc !! -->

<a id="MeshControlWorksheet.DeleteAllRows"></a>

### MeshControlWorksheet.DeleteAllRows()

Delete All Rows

<!-- !! processed by numpydoc !! -->