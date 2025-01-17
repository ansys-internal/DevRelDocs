# SimulationConfiguration Class
 

**Note: This API is now obsolete.**

This class is to represent the simulation configuration.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;ObservableObject<br />&nbsp;&nbsp;&nbsp;&nbsp;LinkableBase<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href="61a8a328-b3bc-8c9a-50d7-bb860f7c67ef">VM.Managed.LinkContainer</a><br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;VM.Managed.SimulationConfiguration<br />
**Namespace:**&nbsp;<a href="05a7f2f9-3551-60b1-3652-371a61dfb10b">VM.Managed</a><br />**Assembly:**&nbsp;VMObjBase (in VMObjBase.dll) Version: 24.1.0.0

## Syntax

**C#**<br />
``` C#
[SerializableAttribute]
[ObsoleteAttribute]
public class SimulationConfiguration : LinkContainer, 
	IEnableManager
```

**VB**<br />
``` VB
<SerializableAttribute>
<ObsoleteAttribute>
Public Class SimulationConfiguration
	Inherits LinkContainer
	Implements IEnableManager
```

**C++**<br />
``` C++
[SerializableAttribute]
[ObsoleteAttribute]
public ref class SimulationConfiguration : public LinkContainer, 
	IEnableManager
```

**F#**<br />
``` F#
[<SerializableAttribute>]
[<ObsoleteAttribute>]
type SimulationConfiguration =  
    class
        inherit LinkContainer
        interface IEnableManager
    end
```

The SimulationConfiguration type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="4e4ad5d8-7cef-de54-4448-faf1ec30b4b9">SimulationConfiguration</a></td><td>
Initializes a new instance of the SimulationConfiguration class.</td></tr></table>&nbsp;
<a href="#simulationconfiguration-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="ae0abafd-8361-1706-a99c-43c209d1c837">AppendDateTime</a></td><td>
Gets or sets a value indicating whether [append date time].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="35a53aae-cf82-a3e1-2246-4827eac41ddb">AutoSolverProgressBar</a></td><td>
Gets or sets a value indicating whether [auto solver progress bar].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="c40d9cef-9725-350a-52b3-d604633d5c27">CheckedLevel</a></td><td>
Gets or sets the checked level.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="f678a02c-1c9f-d74c-7f56-1f96ef3cadea">CriterionSubType</a></td><td>
Gets or sets the type of the criterion sub.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="d24503d4-da4b-121c-6501-5553a9bdf744">CriterionType</a></td><td>
Gets or sets the type of the criterion.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="09f09550-317d-4614-646c-cf41029287bd">CriterionValue</a></td><td>
Gets or sets the criterion value.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="01a0cdfc-23dd-d010-8be4-07602628b88c">DisableEntities</a></td><td>
Gets the disable entity container.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="3d29f711-0ba7-d921-59b3-cbf330edb810">DynamicAnalysisParameter</a></td><td>
Gets or sets the dynamic analysis parameter.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="7a4ca105-eebf-68a8-0adb-a08aecbcab3a">DynamicSimulationStep</a></td><td>
Gets or sets the dynamic simulation step.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="8b09dcc7-22b2-7797-13c5-a7e0262b6a33">EigenvalueAnalysisParameter</a></td><td>
Gets or sets the eigenvalue analysis parameter.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="3196b993-370a-adb4-48c0-af31f27494cb">ExportICFPath</a></td><td>
Gets or sets the export ICF path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="e0f83b4a-d053-44fb-14ce-c0d78cfc3e87">ExtraConfigs</a></td><td>
Gets or sets the extra configuration.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="a501b65f-e001-90b5-1e9e-759c3f9f930a">GeometryPrecisionLevel</a></td><td>
Gets or sets the geometry precision level.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="30f3dc8c-3004-6f6c-eed7-6b182f0d5ef1">GINFFilePath</a></td><td>
Gets or sets the GINF file path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="8c9c4460-5b9b-854c-1e69-ee71a093bd8f">ImportICFPath</a></td><td>
Gets or sets the import ICF path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="759eb4ac-4bf6-265a-35dc-fdba2ba7a6f8">IncludeEigenvalue</a></td><td>
Gets or sets a value indicating whether [include eigenvalue].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="d9eae165-6cc3-8cee-822b-8c8d0aad5ae9">IncludeStatic</a></td><td>
Gets or sets a value indicating whether [include static].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="93e7f5d0-c865-e428-6076-481b78acf58f">IsUseExportICF</a></td><td>
Gets or sets a value indicating whether this instance is use export ICF.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="4909d84e-1ce4-a18b-085e-317b196288c6">IsUseImportICF</a></td><td>
Gets or sets a value indicating whether this instance is use import ICF.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="12d3077d-38da-acca-c3f2-afa009578724">IsUseMotionStep</a></td><td>
Gets or sets a value indicating whether this instance is use motion step.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="0a1fcd69-48ee-b77a-911c-bcda7bb650b8">IsUsePLT</a></td><td>
Gets or sets a value indicating whether this instance is use the simulation step of plt.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="99aaba7e-0f49-d3bf-e96d-34d198260d36">JacobianEvalOption</a></td><td>
Gets or sets the jacobian eval option.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="2b8e11ca-c832-0d11-0fae-61690256fd5c">JacobianType</a></td><td>
Gets or sets the type of the jacobian.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="aa869fab-72ef-cb88-f803-927da5e9b260">LevelOfFlexibleBodyForSuperSolver</a></td><td>
Gets or sets the level of flexible body for super solver.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="15552b12-ebe1-68b5-fcb0-ebca8de5a2d6">LinearSolverType</a></td><td>
Gets or sets the type of the linear solver.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="60ee0470-43fd-3993-0f81-b1e7f9c9e168">MemoryOptimizationType</a></td><td>
Gets or sets the type of the memory optimization.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="90e28ec7-6ea5-7014-7629-e24bd475169c">MeshDataForOutputType</a></td><td>
Gets or sets the type of the mesh data for output.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="d7c06992-0bdf-4c04-5e39-818108edc87c">MeshFreeAnalysisLevelGroup</a></td><td> **Obsolete. **
Gets or sets analysis level group for MeshFree</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="6fa871f2-6561-fbb3-3582-0973984d2ec7">MotionStepForPositionAnalysis</a></td><td /></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="87221f52-c1b8-6495-c363-0c0731bc0238">Name</a></td><td>
Gets or sets the name.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="18b2908e-6cc6-7059-166e-d665658eb8ef">NodalCoordinateType</a></td><td>
Gets or sets the type of the nodal coordinate.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="d04a9052-e595-3500-08b3-5bcbdef5ee4a">NodalOutputEntities</a></td><td>
Gets the nodal output entity container.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="db2afea0-f938-f380-5f65-b9cb525b8918">NodalOutputs</a></td><td>
Gets the nodal output container.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="375eb335-3051-4316-73de-9427af806b48">NumOfCore</a></td><td>
Gets or sets the number of core.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="d3de043d-49eb-ec3d-a5cd-b4256ef23bfe">OutOfCore</a></td><td>
Gets or sets a value indicating whether [out of core].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="0d8e0cbd-f13c-f9ef-1a3f-3278a6384355">ResultPath</a></td><td>
Gets or sets the result path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="3ddcd652-eec8-8c2c-b410-c6bef05adfab">ShowAdvancedOption</a></td><td>
Gets or sets a value indicating whether [show advanced option].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="386e5475-12f1-25da-5e33-a2338bd9819b">SimulationParameter</a></td><td>
Gets or sets the simulation parameter.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="2efab525-ee0e-1e78-5b71-0811990ee462">SimulationStepPLT</a></td><td>
Gets or sets the simulation step of plt.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="252847da-05f9-8768-22f2-cfc8335d5df1">SimulationType</a></td><td>
Gets or sets the type of the simulation.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="db0fd7b7-3d3f-d3f0-c44b-6bc87adf1bdf">SolvingSpeedOption</a></td><td>
Gets or sets a value indicating whether [solving speed option].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="4a20cbde-a0f3-41d1-f4a7-478c404ada3d">StaticAnalysisParameter</a></td><td>
Gets or sets the static analysis parameter.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="0743b929-163c-97a5-a842-08ae96a00d1c">StaticSimulationStep</a></td><td>
Gets or sets the static simulation step.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="0eeb50f8-ca44-81a5-586a-dcd69633a930">SynchronizeMaximumStepSize</a></td><td>
Gets or sets a value indicating whether [synchronize maximum step size].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="646fbccd-a459-43c2-6b7f-5992258675a0">UseLocalRefinement</a></td><td>
Gets or sets a value indicating whether [use local refinement].</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="8f8d275b-b778-4eba-7e63-0daba3193513">UseMeshFreeAllBodySettings</a></td><td> **Obsolete. **
Gets or sets whether use all body settings for MeshFree</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="3cf0b157-80c8-a941-38b3-8cb992c11043">UserTetraPath</a></td><td>
Gets or sets the user tetra path.</td></tr></table>&nbsp;
<a href="#simulationconfiguration-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="95dd1c53-6900-6553-6b08-83037e06f17f">AddToolkitSettingValue</a></td><td>
Adds the toolkit setting.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="cbbd9135-ac89-8b1d-3df5-386892cbef25">Clone</a></td><td>
Clones the specified STR name.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="d7581bc8-4f9a-eba5-d795-b4d725dbb1fd">ContainsToolkitSetting</a></td><td>
Determines whether contains toolkit setting with the specified STR key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="7d41c937-013c-37bc-661c-4ec0d7c95cf2">ContainsToolkitSettingValue</a></td><td>
Determines whether contains toolkit setting with the specified toolkit key.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="1e51131a-1713-0806-c670-61235538c863">DeserializeConfiguration</a></td><td>
Deserializes the configuration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="d817aea5-9cac-d9bc-2f5c-a49ce6cca5b0">InitializeConfig</a></td><td>
Initializes the config.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="5676c71e-8f31-d900-372b-c82b4023fd08">IsEnabled</a></td><td>
Determines whether the specified ob is enabled.</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="0af44a49-0ebb-2356-618c-2ec4308ffebb">LinkRequestUpdate</a></td><td>
Request for update the linked object.
 (Overrides <a href="ad69a423-f18e-aedb-9e6e-94966b715eb0">LinkContainer.LinkRequestUpdate(Object, LinkEventArgs)</a>.)</td></tr><tr><td>![Protected method](media/protmethod.gif "Protected method")</td><td><a href="738c9ab4-92ac-2e10-a526-fcd00d8b0a02">OnDeserialization</a></td><td>
Called when [deserialization].
 (Overrides <a href="64076d3c-3baa-043e-784b-5e010de1a6ec">LinkContainer.OnDeserialization(Object)</a>.)</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="100d0a16-e8fa-4cb4-0a5e-325424c72f09">PostDeserialize</a></td><td>
Posts the deserialize.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="3492d516-eaf7-30e4-8059-34f58643e8f6">RemoveToolkitSettingValue</a></td><td>
Removes the toolkit setting.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="7f2df55d-96e7-6775-8ca5-395dbe6b852f">Replace</a></td><td>
Replaces the specified configuration.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="2f422a41-7805-433a-b410-4bb999e13b30">ReplaceToolkitSettingValue</a></td><td>
Replaces the toolkit setting.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="48a9870b-be37-653c-232f-7bea3c7a5cfc">SetEnable</a></td><td>
Sets the enable.</td></tr></table>&nbsp;
<a href="#simulationconfiguration-class">Back to Top</a>

## See Also


#### Reference
<a href="05a7f2f9-3551-60b1-3652-371a61dfb10b">VM.Managed Namespace</a><br />