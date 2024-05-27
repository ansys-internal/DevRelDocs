# Class Entity

Namespace: [VM.Models.FE.Mesh](VM.Models.FE.Mesh.md)  
Assembly: VM.Models.FE.Mesh.dll  

```csharp
public abstract class Entity : IEntity
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[Entity](VM.Models.FE.Mesh.Entity.md)

#### Derived

[Element](VM.Models.FE.Mesh.Elements.Element.md), 
[HasMultipleNodes](VM.Models.FE.Mesh.HasMultipleNodes.md), 
[Material](VM.Models.FE.Mesh.Materials.Material.md), 
[Node](VM.Models.FE.Mesh.Node.md), 
[Solid](VM.Models.FE.Mesh.Properties.Solid.md)

#### Implements

[IEntity](VM.Models.FE.Mesh.IEntity.md)

#### Extension Methods

[LinkPropertyItemCache.GetLinkProperties\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkProperties\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkPropertiesAndValues\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkPropertiesAndValues\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkedObjects<T\>\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkedObjects\_\_1\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_)

## Constructors

### Entity\(\)

```csharp
protected Entity()
```

## Properties

### Id

```csharp
[Column(IsPrimaryKey = true)]
public int Id { get; set; }
```

#### Property Value

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

## Methods

### Equals\(object\)

```csharp
public override bool Equals(object obj)
```

#### Parameters

`obj` [object](https://learn.microsoft.com/dotnet/api/system.object)

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### FromByteArray<T\>\(byte\[\]\)

```csharp
protected static T FromByteArray<T>(byte[] arr)
```

#### Parameters

`arr` [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

#### Returns

 T

#### Type Parameters

`T` 

### GetHashCode\(\)

```csharp
public override int GetHashCode()
```

#### Returns

 [int](https://learn.microsoft.com/dotnet/api/system.int32)

### ToByteArray<T\>\(T\)

```csharp
protected static byte[] ToByteArray<T>(T value)
```

#### Parameters

`value` T

#### Returns

 [byte](https://learn.microsoft.com/dotnet/api/system.byte)\[\]

#### Type Parameters

`T` 

