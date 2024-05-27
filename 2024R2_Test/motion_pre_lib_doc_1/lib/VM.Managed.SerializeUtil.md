# Class SerializeUtil

Namespace: [VM.Managed](VM.Managed.md)  
Assembly: VMObjBase.dll  

SerializeUtil

```csharp
public class SerializeUtil
```

#### Inheritance

[object](https://learn.microsoft.com/dotnet/api/system.object) ← 
[SerializeUtil](VM.Managed.SerializeUtil.md)

#### Extension Methods

[LinkPropertyItemCache.GetLinkProperties\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkProperties\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkPropertiesAndValues\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkPropertiesAndValues\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_), 
[LinkPropertyItemCache.GetLinkedObjects<T\>\(object, LinkPropertyType\)](VM.Models.Pre.Cache.LinkPropertyItemCache.md\#VM\_Models\_Pre\_Cache\_LinkPropertyItemCache\_GetLinkedObjects\_\_1\_System\_Object\_VM\_Models\_Pre\_LinkPropertyType\_)

## Constructors

### SerializeUtil\(\)

```csharp
public SerializeUtil()
```

## Methods

### Deserial<T\>\(string, Type\)

Deserialize data

```csharp
public static T Deserial<T>(string xml, Type type)
```

#### Parameters

`xml` [string](https://learn.microsoft.com/dotnet/api/system.string)

The object xml

`type` [Type](https://learn.microsoft.com/dotnet/api/system.type)

The deserialized explicit type

#### Returns

 T

#### Type Parameters

`T` 

The object type

### Deserial<T\>\(string\)

```csharp
public static T Deserial<T>(string xml)
```

#### Parameters

`xml` [string](https://learn.microsoft.com/dotnet/api/system.string)

The object xml

#### Returns

 T

#### Type Parameters

`T` 

The object type

### Serial<T\>\(T\)

Serialize data

```csharp
public static string Serial<T>(T obj)
```

#### Parameters

`obj` T

The object

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

The new <xref href="System.String" data-throw-if-not-resolved="false"></xref> object.

#### Type Parameters

`T` 

The object type

### Serial\(ObjectBase\)

```csharp
public static string Serial(ObjectBase obj)
```

#### Parameters

`obj` ObjectBase

#### Returns

 [string](https://learn.microsoft.com/dotnet/api/system.string)

### SerialXmlDoc<T\>\(T\)

Serialize data

```csharp
public static XmlDocument SerialXmlDoc<T>(T obj)
```

#### Parameters

`obj` T

The object

#### Returns

 [XmlDocument](https://learn.microsoft.com/dotnet/api/system.xml.xmldocument)

The new <xref href="System.Xml.XmlDocument" data-throw-if-not-resolved="false"></xref> object.

#### Type Parameters

`T` 

The object type

