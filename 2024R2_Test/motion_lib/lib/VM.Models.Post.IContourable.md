# <a id="VM_Models_Post_IContourable"></a> Interface IContourable

Namespace: [VM.Models.Post](VM.Models.Post.md)  
Assembly: VM.Models.Post.dll  

```csharp
public interface IContourable : IEntity, IObject, IHasName, IHasIndex, IHasID
```

#### Implements

[IEntity](VM.Models.Post.IEntity.md), 
[IObject](VM.Models.Post.IObject.md), 
IHasName, 
[IHasIndex](VM.Models.Post.IHasIndex.md), 
IHasID

#### Extension Methods

[LinkPropertyItemCache.GetLinkProperties\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkProperties\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkPropertiesAndValues\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkPropertiesAndValues\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkedObjects<T\>\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkedObjects\_\_1\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_)

## Methods

### <a id="VM_Models_Post_IContourable_CanContour_VM_Models_ContourMappingType_"></a> CanContour\(ContourMappingType\)

```csharp
bool CanContour(ContourMappingType contourMappingType)
```

#### Parameters

`contourMappingType` ContourMappingType

#### Returns

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)
