# PickerDirection.FilteringReference Method 
 

**Namespace:**&nbsp;<a href="7d099b5d-f450-9a78-d003-8c80108e5410">VM.Managed.Picker.Core</a><br />**Assembly:**&nbsp;VMAppCore (in VMAppCore.dll) Version: 24.1.23299.31577

## Syntax

**C#**<br />
``` C#
public override bool FilteringReference(
	UIntPtr pOwner,
	UIntPtr pTarget
)
```

**VB**<br />
``` VB
Public Overrides Function FilteringReference ( 
	pOwner As UIntPtr,
	pTarget As UIntPtr
) As Boolean
```

**C++**<br />
``` C++
public:
virtual bool FilteringReference(
	UIntPtr pOwner, 
	UIntPtr pTarget
) override
```

**F#**<br />
``` F#
abstract FilteringReference : 
        pOwner : UIntPtr * 
        pTarget : UIntPtr -> bool 
override FilteringReference : 
        pOwner : UIntPtr * 
        pTarget : UIntPtr -> bool 
```


#### Parameters
&nbsp;<dl><dt>pOwner</dt><dd>Type: System.UIntPtr<br /></dd><dt>pTarget</dt><dd>Type: System.UIntPtr<br /></dd></dl>

#### Return Value
Type: Boolean

## See Also


#### Reference
<a href="81e4795b-ba76-2d49-d162-34bfefe13d98">PickerDirection Class</a><br /><a href="7d099b5d-f450-9a78-d003-8c80108e5410">VM.Managed.Picker.Core Namespace</a><br />