# ReferenceSetFace.GetGeometryNavigatorInformation Method 
 

Gets the geometry information for model navigator .

**Namespace:**&nbsp;<a href="8790c1b2-b85d-f406-6b72-1668fe47b24f">VM.Managed.DAFUL</a><br />**Assembly:**&nbsp;VMDFBase (in VMDFBase.dll) Version: 24.1.0.0

## Syntax

**C#**<br />
``` C#
public bool GetGeometryNavigatorInformation(
	XmlDocument xmlDom,
	XmlElement xmlEle
)
```

**VB**<br />
``` VB
Public Function GetGeometryNavigatorInformation ( 
	xmlDom As XmlDocument,
	xmlEle As XmlElement
) As Boolean
```

**C++**<br />
``` C++
public:
virtual bool GetGeometryNavigatorInformation(
	XmlDocument^ xmlDom, 
	XmlElement^ xmlEle
) sealed
```

**F#**<br />
``` F#
abstract GetGeometryNavigatorInformation : 
        xmlDom : XmlDocument * 
        xmlEle : XmlElement -> bool 
override GetGeometryNavigatorInformation : 
        xmlDom : XmlDocument * 
        xmlEle : XmlElement -> bool 
```


#### Parameters
&nbsp;<dl><dt>xmlDom</dt><dd>Type: System.Xml.XmlDocument<br />The XmlDocument information.</dd><dt>xmlEle</dt><dd>Type: System.Xml.XmlElement<br />The XmlElement information.</dd></dl>

#### Return Value
Type: Boolean<br />`true` if success; otherwise, `false`.

#### Implements
<a href="15c1aaad-5225-ead7-dc5c-f307724ebf54">IGeometricalComponent.GetGeometryNavigatorInformation(XmlDocument, XmlElement)</a><br />

## See Also


#### Reference
<a href="a8104da4-85cd-6700-fb45-bdfd60dc5da8">ReferenceSetFace Class</a><br /><a href="8790c1b2-b85d-f406-6b72-1668fe47b24f">VM.Managed.DAFUL Namespace</a><br />