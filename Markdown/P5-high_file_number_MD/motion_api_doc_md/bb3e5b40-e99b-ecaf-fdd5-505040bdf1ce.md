# RacewayBuilder.LinkRequestDestroying Method 
 

Request for destroying the linked object.

**Namespace:**&nbsp;<a href="d9db19a5-2df6-b933-3d4e-2c38d80febf4">VM.Managed.DAFUL.GearTrain.CAD</a><br />**Assembly:**&nbsp;VMDGearTrain (in VMDGearTrain.dll) Version: 24.1.0.0

## Syntax

**C#**<br />
``` C#
protected override void LinkRequestDestroying(
	Object objNotifier,
	LinkEventArgs arg
)
```

**VB**<br />
``` VB
Protected Overrides Sub LinkRequestDestroying ( 
	objNotifier As Object,
	arg As LinkEventArgs
)
```

**C++**<br />
``` C++
protected:
virtual void LinkRequestDestroying(
	Object^ objNotifier, 
	LinkEventArgs^ arg
) override
```

**F#**<br />
``` F#
abstract LinkRequestDestroying : 
        objNotifier : Object * 
        arg : LinkEventArgs -> unit 
override LinkRequestDestroying : 
        objNotifier : Object * 
        arg : LinkEventArgs -> unit 
```


#### Parameters
&nbsp;<dl><dt>objNotifier</dt><dd>Type: System.Object<br />The linked object.</dd><dt>arg</dt><dd>Type: <a href="fce56426-d69f-2183-7b9b-55717442720f">VM.Managed.LinkEventArgs</a><br />The <a href="fce56426-d69f-2183-7b9b-55717442720f">LinkEventArgs</a> instance containing the event data.</dd></dl>

## See Also


#### Reference
<a href="617f94d3-d641-39c4-04c7-78fa019c88ed">RacewayBuilder Class</a><br /><a href="d9db19a5-2df6-b933-3d4e-2c38d80febf4">VM.Managed.DAFUL.GearTrain.CAD Namespace</a><br />