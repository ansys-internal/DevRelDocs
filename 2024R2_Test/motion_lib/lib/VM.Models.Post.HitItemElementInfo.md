# <a id="VM_Models_Post_HitItemElementInfo"></a> Class HitItemElementInfo

Namespace: [VM.Models.Post](VM.Models.Post.md)  
Assembly: VM.Models.Post.dll  

```csharp
public sealed class HitItemElementInfo : HitItemInfo, IObservableObject, IDisposableObject
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
ObservableObject ← 
[HitItemInfo](VM.Models.Post.HitItemInfo.md) ← 
[HitItemElementInfo](VM.Models.Post.HitItemElementInfo.md)

#### Implements

IObservableObject, 
IDisposableObject

#### Inherited Members

[HitItemInfo.SetHitItem\(IHitItem\)](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_SetHitItem\_VM\_Models\_Post\_IHitItem\_), 
[HitItemInfo.DistanceAlongRay](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_DistanceAlongRay), 
[HitItemInfo.ElementID](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_ElementID), 
[HitItemInfo.ElementIndex](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_ElementIndex), 
[HitItemInfo.HitItem](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_HitItem), 
[HitItemInfo.HitItemType](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_HitItemType), 
[HitItemInfo.IntersectionPoint](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_IntersectionPoint), 
[HitItemInfo.IsSelected](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_IsSelected), 
[HitItemInfo.NodeID](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_NodeID), 
[HitItemInfo.NodeIndex](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_NodeIndex), 
[HitItemInfo.PartID](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_PartID), 
[HitItemInfo.PartIndex](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_PartIndex), 
[HitItemInfo.TypeOfHitItemInfo](VM.Models.Post.HitItemInfo.md\#VM\_Models\_Post\_HitItemInfo\_TypeOfHitItemInfo), 
ObservableObject.Dispose\(\), 
ObservableObject.RaisePropertyChanged\(string\), 
ObservableObject.RaisePropertyChanged\(string, object, object\), 
ObservableObject.IsDisposed, 
ObservableObject.TryDisposing, 
ObservableObject.Disposed, 
ObservableObject.Disposing, 
ObservableObject.PropertyChanged

#### Extension Methods

[LinkPropertyItemCache.GetLinkProperties\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkProperties\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkPropertiesAndValues\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkPropertiesAndValues\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkedObjects<T\>\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkedObjects\_\_1\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_)

## Constructors

### <a id="VM_Models_Post_HitItemElementInfo__ctor_VM_Models_Post_IHitItem_"></a> HitItemElementInfo\(IHitItem\)

```csharp
public HitItemElementInfo(IHitItem ptr)
```

#### Parameters

`ptr` [IHitItem](VM.Models.Post.IHitItem.md)

## Properties

### <a id="VM_Models_Post_HitItemElementInfo_ElementType"></a> ElementType

```csharp
[SaveProperty(false)]
public ElementType ElementType { get; set; }
```

#### Property Value

 [ElementType](VM.Models.Post.ElementType.md)

### <a id="VM_Models_Post_HitItemElementInfo_SelectionOption"></a> SelectionOption

```csharp
public SelectionOption SelectionOption { get; set; }
```

#### Property Value

 [SelectionOption](VM.Models.Post.SelectionOption.md)

### <a id="VM_Models_Post_HitItemElementInfo_TypeOfHitItemInfo"></a> TypeOfHitItemInfo

```csharp
public override HitItemInfoType TypeOfHitItemInfo { get; }
```

#### Property Value

 [HitItemInfoType](VM.Models.Post.HitItemInfoType.md)

## Methods

### <a id="VM_Models_Post_HitItemElementInfo_ChangeIdInfo_System_Int32_System_Int32_VM_Models_Post_ElementType_"></a> ChangeIdInfo\(int, int, ElementType\)

```csharp
public void ChangeIdInfo(int id, int index, ElementType elementType)
```

#### Parameters

`id` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`index` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`elementType` [ElementType](VM.Models.Post.ElementType.md)
