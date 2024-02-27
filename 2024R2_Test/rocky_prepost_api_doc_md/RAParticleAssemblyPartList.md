# RAParticleAssemblyPartList

<!-- Make "generated" the current module for all API classes so that we can cross-reference them
without adding the full package path. -->
<!-- The empty parenthesis is to suppress documenting the constructor (API classes generally aren't
instantiated by the user). -->

### *class* RAParticleAssemblyPartList

Rocky API wrapper for the parts list in a single Particle Assembly.

To get the [`RAParticleAssemblyPartList`](#generated.RAParticleAssemblyPartList) from a `RAParticleAssembly`, use:

```python
assembly_parts = particle_assembly.GetAssemblyParts()
```

[`RAParticleAssemblyPartList`](#generated.RAParticleAssemblyPartList) contains methods to add, remove and retrieve individual
assembly parts. It corresponds to the list of entries on a Particle Assembly’s “Shape” tab
on the Rocky UI.

The following examples add, remove and access individual entries in the assembly parts list:

```python
# Add new items
assembly_part_1 = assembly_parts.New()

# Access and modify items
assembly_part_2 = assembly_parts[0]
assembly_part_2.SetParticle('Particle 1')

# Remove items
assembly_parts.Remove(assembly_part_2)
del assembly_parts[0]
assembly_parts.Clear()
```

The [`RAParticleAssemblyPartList`](#generated.RAParticleAssemblyPartList) is a list of [`RAParticleAssemblyPart`](RAParticleAssemblyPart.md#generated.RAParticleAssemblyPart).

**Methods:**

| [`Clear`](#generated.RAParticleAssemblyPartList.Clear)()       | Remove all items from the list.   |
|----------------------------------------------------------------|-----------------------------------|
| [`New`](#generated.RAParticleAssemblyPartList.New)()           | Add a new item.                   |
| [`Remove`](#generated.RAParticleAssemblyPartList.Remove)(item) | Remove an item from the list.     |

#### Clear()

Remove all items from the list.

#### New()

Add a new item. Returns the newly created item.

#### Remove(item: T)

Remove an item from the list.