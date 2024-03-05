# <a id="VM_Models_Post_HitItemNodeInfo"></a> Class HitItemNodeInfo

Namespace: [VM.Models.Post](VM.Models.Post.md)  
Assembly: VM.Models.Post.dll  

```csharp
public sealed class HitItemNodeInfo : HitItemInfo, IObservableObject, IDisposableObject
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
ObservableObject ← 
[HitItemInfo](VM.Models.Post.HitItemInfo.md) ← 
[HitItemNodeInfo](VM.Models.Post.HitItemNodeInfo.md)

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

### <a id="VM_Models_Post_HitItemNodeInfo__ctor_VM_Models_Post_IHitItem_"></a> HitItemNodeInfo\(IHitItem\)

```csharp
public HitItemNodeInfo(IHitItem ptr)
```

#### Parameters

`ptr` [IHitItem](VM.Models.Post.IHitItem.md)

## Properties

### <a id="VM_Models_Post_HitItemNodeInfo_SelectionOption"></a> SelectionOption

```csharp
public SelectionOption SelectionOption { get; set; }
```

#### Property Value

 [SelectionOption](VM.Models.Post.SelectionOption.md)

### <a id="VM_Models_Post_HitItemNodeInfo_TypeOfHitItemInfo"></a> TypeOfHitItemInfo

```csharp
public override HitItemInfoType TypeOfHitItemInfo { get; }
```

#### Property Value

 [HitItemInfoType](VM.Models.Post.HitItemInfoType.md)

## Methods

### <a id="VM_Models_Post_HitItemNodeInfo_ChangeIdInfo_System_Int32_System_Int32_"></a> ChangeIdInfo\(int, int\)

```csharp
public void ChangeIdInfo(int id, int index)
```

#### Parameters

`id` [int](https://learn.microsoft.com/dotnet/api/system.int32)

`index` [int](https://learn.microsoft.com/dotnet/api/system.int32)
