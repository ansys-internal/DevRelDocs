# PropertyPerpendicular.Draw Method 
 


Draws the icon.


**Namespace:**&nbsp;<a href="b5e7d154-f6c2-cdc8-0dc3-9407b97f82b2">VM.Managed.DAFUL.Constraints</a><br />**Assembly:**&nbsp;VMDCP (in VMDCP.dll) Version: 24.1.0.0

## Syntax

**C#**<br />
``` C#
public virtual void Draw(
	Canvas canvas,
	TMatrix matTBase,
	TMatrix matTAct,
	bool bHide
)
```

**VB**<br />
``` VB
Public Overridable Sub Draw ( 
	canvas As Canvas,
	matTBase As TMatrix,
	matTAct As TMatrix,
	bHide As Boolean
)
```

**C++**<br />
``` C++
public:
virtual void Draw(
	Canvas^ canvas, 
	TMatrix^ matTBase, 
	TMatrix^ matTAct, 
	bool bHide
)
```

**F#**<br />
``` F#
abstract Draw : 
        canvas : Canvas * 
        matTBase : TMatrix * 
        matTAct : TMatrix * 
        bHide : bool -> unit 
override Draw : 
        canvas : Canvas * 
        matTBase : TMatrix * 
        matTAct : TMatrix * 
        bHide : bool -> unit 
```


#### Parameters
&nbsp;<dl><dt>canvas</dt><dd>Type: Canvas<br />
The canvas has icon information.</dd><dt>matTBase</dt><dd>Type: <a href="8970ea1a-9b2d-7e4e-a48a-089c3184b6ed">VM.Managed.TMatrix</a><br />
The base transformation.</dd><dt>matTAct</dt><dd>Type: <a href="8970ea1a-9b2d-7e4e-a48a-089c3184b6ed">VM.Managed.TMatrix</a><br />
The action transformation.</dd><dt>bHide</dt><dd>Type: System.Boolean<br />
The hide flag.</dd></dl>

## See Also


#### Reference
<a href="4396b5e0-0d60-e263-1288-c5e94da5838f">PropertyPerpendicular Class</a><br /><a href="b5e7d154-f6c2-cdc8-0dc3-9407b97f82b2">VM.Managed.DAFUL.Constraints Namespace</a><br />