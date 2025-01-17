# IReadableForceMarkerImpl.ReadableActionMarker Method 
 

Readables the action marker.

**Namespace:**&nbsp;<a href="dffdd925-1fae-3344-2d62-28ef99dd387b">VM.Managed.DAFUL.Force</a><br />**Assembly:**&nbsp;VMDFB (in VMDFB.dll) Version: 24.1.0.0

## Syntax

**C#**<br />
``` C#
public static void ReadableActionMarker(
	Marker actionMarker,
	ref bool bReadablePos,
	ref bool bReadableOri
)
```

**VB**<br />
``` VB
Public Shared Sub ReadableActionMarker ( 
	actionMarker As Marker,
	ByRef bReadablePos As Boolean,
	ByRef bReadableOri As Boolean
)
```

**C++**<br />
``` C++
public:
static void ReadableActionMarker(
	Marker^ actionMarker, 
	bool% bReadablePos, 
	bool% bReadableOri
)
```

**F#**<br />
``` F#
static member ReadableActionMarker : 
        actionMarker : Marker * 
        bReadablePos : bool byref * 
        bReadableOri : bool byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>actionMarker</dt><dd>Type: <a href="661f5522-74b1-7999-d5ac-588cf206bd7a">VM.Managed.DAFUL.Marker</a><br />The action marker.</dd><dt>bReadablePos</dt><dd>Type: System.Boolean<br />if set to `true` [b readable pos].</dd><dt>bReadableOri</dt><dd>Type: System.Boolean<br />if set to `true` [b readable ori].</dd></dl>

## See Also


#### Reference
<a href="3e3c4ffc-2df6-737c-02fe-a940a01895bc">IReadableForceMarkerImpl Class</a><br /><a href="dffdd925-1fae-3344-2d62-28ef99dd387b">VM.Managed.DAFUL.Force Namespace</a><br />