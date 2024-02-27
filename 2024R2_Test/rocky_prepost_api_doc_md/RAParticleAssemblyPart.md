# RAParticleAssemblyPart

<!-- Make "generated" the current module for all API classes so that we can cross-reference them
without adding the full package path. -->
<!-- The empty parenthesis is to suppress documenting the constructor (API classes generally aren't
instantiated by the user). -->

### *class* RAParticleAssemblyPart

Rocky API wrapper for a single entry in a single Particle Assembly’s part list.

Access this wrapper from a given `RAParticleAssembly` with:

```python
assembly_parts = particle_assembly.GetAssemblyParts()
assembly_part_1 = assembly_parts.New()
assembly_part_1.SetParticle('Particle 1')
assembly_part_1.SetPositionX(0.75, 'm')
```

**Methods:**

| [`GetAngle`](#generated.RAParticleAssemblyPart.GetAngle)([unit])                     | Get the value of "Angle".      |
|--------------------------------------------------------------------------------------|--------------------------------|
| [`GetAvailableParticles`](#generated.RAParticleAssemblyPart.GetAvailableParticles)() | Get all available Particles.   |
| [`GetParticle`](#generated.RAParticleAssemblyPart.GetParticle)()                     | Get the "Particle".            |
| [`GetPositionX`](#generated.RAParticleAssemblyPart.GetPositionX)([unit])             | Get the value of "Position X". |
| [`GetPositionY`](#generated.RAParticleAssemblyPart.GetPositionY)([unit])             | Get the value of "Position Y". |
| [`GetPositionZ`](#generated.RAParticleAssemblyPart.GetPositionZ)([unit])             | Get the value of "Position Z". |
| [`GetRotationX`](#generated.RAParticleAssemblyPart.GetRotationX)([unit])             | Get the value of "Rotation X". |
| [`GetRotationY`](#generated.RAParticleAssemblyPart.GetRotationY)([unit])             | Get the value of "Rotation Y". |
| [`GetRotationZ`](#generated.RAParticleAssemblyPart.GetRotationZ)([unit])             | Get the value of "Rotation Z". |
| [`GetScale`](#generated.RAParticleAssemblyPart.GetScale)([unit])                     | Get the value of "Scale".      |
| [`SetAngle`](#generated.RAParticleAssemblyPart.SetAngle)(value[, unit])              | Set the value of "Angle".      |
| [`SetParticle`](#generated.RAParticleAssemblyPart.SetParticle)(value)                | Set the "Particle".            |
| [`SetPositionX`](#generated.RAParticleAssemblyPart.SetPositionX)(value[, unit])      | Set the value of "Position X". |
| [`SetPositionY`](#generated.RAParticleAssemblyPart.SetPositionY)(value[, unit])      | Set the value of "Position Y". |
| [`SetPositionZ`](#generated.RAParticleAssemblyPart.SetPositionZ)(value[, unit])      | Set the value of "Position Z". |
| [`SetRotationX`](#generated.RAParticleAssemblyPart.SetRotationX)(value[, unit])      | Set the value of "Rotation X". |
| [`SetRotationY`](#generated.RAParticleAssemblyPart.SetRotationY)(value[, unit])      | Set the value of "Rotation Y". |
| [`SetRotationZ`](#generated.RAParticleAssemblyPart.SetRotationZ)(value[, unit])      | Set the value of "Rotation Z". |
| [`SetScale`](#generated.RAParticleAssemblyPart.SetScale)(value[, unit])              | Set the value of "Scale".      |

#### GetAngle(unit: Optional[str] = None)

Get the value of “Angle”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “dega”.

#### GetAvailableParticles()

Get all available Particles.

* **Return type:**
  List[[`RAParticle`](RAParticle.md#generated.RAParticle)]
  A list of [`RAParticle`](RAParticle.md#generated.RAParticle).

#### GetParticle()

Get the “Particle”.

* **Return type:**
  [`RAParticle`](RAParticle.md#generated.RAParticle)

#### GetPositionX(unit: Optional[str] = None)

Get the value of “Position X”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “m”.

#### GetPositionY(unit: Optional[str] = None)

Get the value of “Position Y”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “m”.

#### GetPositionZ(unit: Optional[str] = None)

Get the value of “Position Z”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “m”.

#### GetRotationX(unit: Optional[str] = None)

Get the value of “Rotation X”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “m”.

#### GetRotationY(unit: Optional[str] = None)

Get the value of “Rotation Y”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “m”.

#### GetRotationZ(unit: Optional[str] = None)

Get the value of “Rotation Z”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “m”.

#### GetScale(unit: Optional[str] = None)

Get the value of “Scale”.

* **Parameters:**
  **unit** – The unit for the returned value. If no unit is provided, the returned value will be in “-“.

#### SetAngle(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Angle”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “dega”.

#### SetParticle(value)

Set the “Particle”.

:param unicode, [`RAParticle`](RAParticle.md#generated.RAParticle) value:
: Either the API object wrapping the desired entity or its name.

#### SetPositionX(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Position X”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “m”.

#### SetPositionY(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Position Y”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “m”.

#### SetPositionZ(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Position Z”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “m”.

#### SetRotationX(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Rotation X”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “m”.

#### SetRotationY(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Rotation Y”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “m”.

#### SetRotationZ(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Rotation Z”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “m”.

#### SetScale(value: Union[str, float], unit: Optional[str] = None)

Set the value of “Scale”.

* **Parameters:**
  * **value** – The value to set. This value can be an expression with input variables or float type.
  * **unit** – The unit for value. If no unit is provided, value is assumed to be in “-“.