# IDesignModelerGeoFeature

### *class* IDesignModelerGeoFeature

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a DesignModeler custom feature.

> <!-- !! processed by numpydoc !! -->

## Overview

### Methods

| [`AddProblematicGeometry`](#IDesignModelerGeoFeature.AddProblematicGeometry)   | AddProblematicGeometry method.   |
|--------------------------------------------------------------------------------|----------------------------------|

### Properties

| [`MaterialType`](#IDesignModelerGeoFeature.MaterialType)   | Gets or sets the material type used to generate the feature.       |
|------------------------------------------------------------|--------------------------------------------------------------------|
| [`Bodies`](#IDesignModelerGeoFeature.Bodies)               | Gets or sets the list of bodies or parts generated by the feature. |

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Interfaces.DesignModeler import IDesignModelerGeoFeature
```

## Property detail

### *property* IDesignModelerGeoFeature.MaterialType *: Ansys.ACT.Interfaces.Geometry.MaterialTypeEnum | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the material type used to generate the feature.

<!-- !! processed by numpydoc !! -->

### *property* IDesignModelerGeoFeature.Bodies *: System.Collections.Generic.IEnumerable[Ansys.ACT.Interfaces.Geometry.IBaseGeoBodyOrPart] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the list of bodies or parts generated by the feature.

<!-- !! processed by numpydoc !! -->

## Method detail

### IDesignModelerGeoFeature.AddProblematicGeometry(entities: System.Collections.Generic.IEnumerable[[Ansys.ACT.Interfaces.DesignModeler.IPSGeoEntity](IPSGeoEntity.md#IPSGeoEntity)], message: System.String)

AddProblematicGeometry method.

<!-- !! processed by numpydoc !! -->