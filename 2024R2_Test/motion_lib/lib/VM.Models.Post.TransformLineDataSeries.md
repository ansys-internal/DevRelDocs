# <a id="VM_Models_Post_TransformLineDataSeries"></a> Class TransformLineDataSeries

Namespace: [VM.Models.Post](VM.Models.Post.md)  
Assembly: VM.Models.Post.dll  

```csharp
public sealed class TransformLineDataSeries : HasOriginalSeries, IObservableObject, IDisposableObject, ISeries, IObject, IHasName
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
ObservableObject ← 
[ObjectBase](VM.Models.Post.ObjectBase.md) ← 
[LineDataSeriesBase](VM.Models.Post.LineDataSeriesBase.md) ← 
[HasOriginalSeries](VM.Models.Post.HasOriginalSeries.md) ← 
[TransformLineDataSeries](VM.Models.Post.TransformLineDataSeries.md)

#### Implements

IObservableObject, 
IDisposableObject, 
[ISeries](VM.Models.Post.ISeries.md), 
[IObject](VM.Models.Post.IObject.md), 
IHasName

#### Inherited Members

[HasOriginalSeries.NeedSavePoints](VM.Models.Post.HasOriginalSeries.md\#VM\_Models\_Post\_HasOriginalSeries\_NeedSavePoints), 
[HasOriginalSeries.OriginalSeriesID](VM.Models.Post.HasOriginalSeries.md\#VM\_Models\_Post\_HasOriginalSeries\_OriginalSeriesID), 
[HasOriginalSeries.ParentDocument](VM.Models.Post.HasOriginalSeries.md\#VM\_Models\_Post\_HasOriginalSeries\_ParentDocument), 
[LineDataSeriesBase.Separators](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Separators), 
[LineDataSeriesBase.ChangeParent\(int\)](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_ChangeParent\_System\_Int32\_), 
[LineDataSeriesBase.Initialize\(Action\)](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Initialize\_System\_Action\_), 
[LineDataSeriesBase.Color](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Color), 
[LineDataSeriesBase.Expression](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Expression), 
[LineDataSeriesBase.ID](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_ID), 
[LineDataSeriesBase.InnerExpression](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_InnerExpression), 
[LineDataSeriesBase.IsRefresh](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_IsRefresh), 
[LineDataSeriesBase.LineSeriesType](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_LineSeriesType), 
[LineDataSeriesBase.LineStrokeDash](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_LineStrokeDash), 
[LineDataSeriesBase.LineStyle](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_LineStyle), 
[LineDataSeriesBase.NeedSavePoints](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_NeedSavePoints), 
[LineDataSeriesBase.ParentDocument](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_ParentDocument), 
[LineDataSeriesBase.ParentID](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_ParentID), 
[LineDataSeriesBase.PointMarker](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_PointMarker), 
[LineDataSeriesBase.Points](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Points), 
[LineDataSeriesBase.RelatedSeries](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_RelatedSeries), 
[LineDataSeriesBase.ResultDocumentFilePath](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_ResultDocumentFilePath), 
[LineDataSeriesBase.SeriesType](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_SeriesType), 
[LineDataSeriesBase.Target](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Target), 
[LineDataSeriesBase.TargetName](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_TargetName), 
[LineDataSeriesBase.Thickness](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Thickness), 
[LineDataSeriesBase.Unit](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_Unit), 
[LineDataSeriesBase.XAxisID](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_XAxisID), 
[LineDataSeriesBase.XDimension](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_XDimension), 
[LineDataSeriesBase.XUnit](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_XUnit), 
[LineDataSeriesBase.YAxisID](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_YAxisID), 
[LineDataSeriesBase.YDimension](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_YDimension), 
[LineDataSeriesBase.YUnit](VM.Models.Post.LineDataSeriesBase.md\#VM\_Models\_Post\_LineDataSeriesBase\_YUnit), 
[ObjectBase.GetUnstructGridModel\(\)](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_GetUnstructGridModel), 
[ObjectBase.SetName\(string\)](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_SetName\_System\_String\_), 
[ObjectBase.UpdateAnimation\(UpdateActionType\)](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_UpdateAnimation\_VM\_Models\_Post\_UpdateActionType\_), 
[ObjectBase.AnalysisResult](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_AnalysisResult), 
[ObjectBase.AnalysisResultID](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_AnalysisResultID), 
[ObjectBase.AnalysisResultType](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_AnalysisResultType), 
[ObjectBase.DisplayName](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_DisplayName), 
[ObjectBase.FullName](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_FullName), 
[ObjectBase.Name](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_Name), 
[ObjectBase.ParentDocument](VM.Models.Post.ObjectBase.md\#VM\_Models\_Post\_ObjectBase\_ParentDocument), 
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

## Properties

### <a id="VM_Models_Post_TransformLineDataSeries_Align"></a> Align

```csharp
[SaveProperty(false)]
public AlignType Align { get; set; }
```

#### Property Value

 [AlignType](VM.Models.Post.AlignType.md)

### <a id="VM_Models_Post_TransformLineDataSeries_AlignBase"></a> AlignBase

```csharp
[SaveProperty(false)]
public double AlignBase { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="VM_Models_Post_TransformLineDataSeries_Base"></a> Base

```csharp
[SaveProperty(false)]
public double Base { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="VM_Models_Post_TransformLineDataSeries_Coefficient"></a> Coefficient

```csharp
[SaveProperty(false)]
public double Coefficient { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="VM_Models_Post_TransformLineDataSeries_IsDecibel"></a> IsDecibel

```csharp
[SaveProperty(false)]
public bool IsDecibel { get; set; }
```

#### Property Value

 [bool](https://learn.microsoft.com/dotnet/api/system.boolean)

### <a id="VM_Models_Post_TransformLineDataSeries_LineSeriesType"></a> LineSeriesType

```csharp
public override LineSeriesType LineSeriesType { get; }
```

#### Property Value

 [LineSeriesType](VM.Models.Post.LineSeriesType.md)

### <a id="VM_Models_Post_TransformLineDataSeries_OffsetX"></a> OffsetX

```csharp
[SaveProperty(false)]
public double OffsetX { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="VM_Models_Post_TransformLineDataSeries_OffsetY"></a> OffsetY

```csharp
[SaveProperty(false)]
public double OffsetY { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="VM_Models_Post_TransformLineDataSeries_ScaleX"></a> ScaleX

```csharp
[SaveProperty(false)]
public double ScaleX { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="VM_Models_Post_TransformLineDataSeries_ScaleY"></a> ScaleY

```csharp
[SaveProperty(false)]
public double ScaleY { get; set; }
```

#### Property Value

 [double](https://learn.microsoft.com/dotnet/api/system.double)

### <a id="VM_Models_Post_TransformLineDataSeries_Sign"></a> Sign

```csharp
[SaveProperty(false)]
public SignType Sign { get; set; }
```

#### Property Value

 [SignType](VM.Models.Post.SignType.md)

### <a id="VM_Models_Post_TransformLineDataSeries_SourceSeriesID"></a> SourceSeriesID

```csharp
[SaveProperty(false)]
public string SourceSeriesID { get; init; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="VM_Models_Post_TransformLineDataSeries_TargetSeriesID"></a> TargetSeriesID

```csharp
public string TargetSeriesID { get; }
```

#### Property Value

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### <a id="VM_Models_Post_TransformLineDataSeries_TransformType"></a> TransformType

```csharp
[SaveProperty(false)]
public TransformType TransformType { get; set; }
```

#### Property Value

 [TransformType](VM.Models.Post.TransformType.md)
