<a id="analysis"></a>

# Analysis

<a id="Analysis"></a>

### *class* Analysis

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> Defines a Analysis.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Methods

| Name | Summary |
|--------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------|
| [`AddSymmetryManufacturingConstraint`](#Analysis.AddSymmetryManufacturingConstraint)                         | Creates a new SymmetryManufacturingConstraint                                                                          |
| [`AddTemperature`](#Analysis.AddTemperature)                                                                 | Creates a new Temperature                                                                                              |
| [`AddTemperatureConstraint`](#Analysis.AddTemperatureConstraint)                                             | Creates a new TemperatureConstraint                                                                                    |
| [`AddThermalComplianceConstraint`](#Analysis.AddThermalComplianceConstraint)                                 | Creates a new ThermalComplianceConstraint                                                                              |
| [`AddUniformConstraint`](#Analysis.AddUniformConstraint)                                                     | Creates a new UniformConstraint                                                                                        |
| [`AddVelocity`](#Analysis.AddVelocity)                                                                       | Creates a new Velocity                                                                                                 |
| [`AddViscoelasticHeating`](#Analysis.AddViscoelasticHeating)                                                 | Creates a new ViscoelasticHeating                                                                                      |
| [`AddVoltage`](#Analysis.AddVoltage)                                                                         | Creates a new Voltage                                                                                                  |
| [`AddVoltageGround`](#Analysis.AddVoltageGround)                                                             | Creates a new VoltageGround                                                                                            |
| [`AddVolumeChargeDensity`](#Analysis.AddVolumeChargeDensity)                                                 | Creates a new VolumeChargeDensity                                                                                      |
| [`AddVolumeConstraint`](#Analysis.AddVolumeConstraint)                                                       | Creates a new VolumeConstraint                                                                                         |
| [`Delete`](#Analysis.Delete)                                                                                 | Run the Delete action.                                                                                                 |
| [`GetChildren`](#id1)                                                                                        | Gets the list of children, filtered by type.                                                                           |
| [`GetChildren`](#id1)                                                                                        | Gets the list of children, filtered by type.                                                                           |
| [`AddComment`](#Analysis.AddComment)                                                                         | Creates a new child Comment.                                                                                           |
| [`AddFigure`](#Analysis.AddFigure)                                                                           | Creates a new child Figure.                                                                                            |
| [`AddImage`](#Analysis.AddImage)                                                                             | Creates a new child Image.                                                                                             |
| [`Solve`](#id2)                                                                                              | Run the Solve action.                                                                                                  |
| [`Solve`](#id2)                                                                                              | Run the Solve action.                                                                                                  |
| [`ClearGeneratedData`](#Analysis.ClearGeneratedData)                                                         | Run the ClearGeneratedData action.                                                                                     |
| [`OpenSolverFilesDirectory`](#Analysis.OpenSolverFilesDirectory)                                             | Run the OpenSolverFilesDirectory action.                                                                               |
| [`FilterBasedOnEnvironment`](#Analysis.FilterBasedOnEnvironment)                                             | Enables interface filtering that only displays model-level items applicable to                                         |
| [`AddInitialVelocity`](#Analysis.AddInitialVelocity)                                                         | Creates a new child Initial Velocity.                                                                                  |
| [`AddSystemCouplingRegion`](#Analysis.AddSystemCouplingRegion)                                               | Creates a new SystemCouplingRegion                                                                                     |
| [`AddThermalCondition`](#Analysis.AddThermalCondition)                                                       | Creates a new child ThermalCondition.                                                                                  |
| [`AddBoltPretension`](#Analysis.AddBoltPretension)                                                           | Creates a new BoltPretension                                                                                           |
| [`AddOptimizationRegion`](#Analysis.AddOptimizationRegion)                                                   | Creates a new OptimizationRegion                                                                                       |
| [`AddAcousticTemperature`](#Analysis.AddAcousticTemperature)                                                 | Creates a new child ThermalCondition.                                                                                  |
| [`AddSourceConductor`](#Analysis.AddSourceConductor)                                                         | Creates a new child SourceConductor.                                                                                   |
| [`WriteSystemCouplingFiles`](#Analysis.WriteSystemCouplingFiles)                                             | Writes the system coupling files. Usage WriteSystemCouplingFiles(“C:Desktoptempscp1.scp”);                             |
| [`CreateAutomaticFarFieldRadiationSurfaces`](#Analysis.CreateAutomaticFarFieldRadiationSurfaces)             | Run the CreateAutomaticEquivalentSourceSurfaces action.                                                                |
| [`CreateAutomaticFSI`](#Analysis.CreateAutomaticFSI)                                                         | Run the CreateAutomaticFSI action.                                                                                     |
| [`CreateAutomaticFSIandFarFieldRadiationSurfaces`](#Analysis.CreateAutomaticFSIandFarFieldRadiationSurfaces) | Run the CreateAutomaticFSIandEquivalentSourceSurfaces action.                                                          |
| [`SelectBodiesWithoutPhysicsRegion`](#Analysis.SelectBodiesWithoutPhysicsRegion)                             | Run the SelectBodiesWithoutPhysicsRegion action to select the bodies that don’t belong to a Physics Region.            |
| [`SelectBodiesWithMultiplePhysicsRegion`](#Analysis.SelectBodiesWithMultiplePhysicsRegion)                   | Run the SelectBodiesWithMultiplePhysicsRegion action to select the bodies that belong to more than one Physics Region. |
| [`AddImportedLoadMAPDLResultsFile`](#Analysis.AddImportedLoadMAPDLResultsFile)                               | Creates a new Import Load for MAPDL Results File.                                                                      |
| [`AddImportedLoadFluidsResultsFile`](#Analysis.AddImportedLoadFluidsResultsFile)                             | Creates a new Import Load for Fluids Results File.                                                                     |
| [`AddImportedLoadExternalData`](#Analysis.AddImportedLoadExternalData)                                       | For Standalone Mode only. Creates a new Imported Load (External Data).                                                 |
| [`AddImportedRemoteLoadsGroup`](#Analysis.AddImportedRemoteLoadsGroup)                                       | Creates a new Import Remote Load Group.                                                                                |
| [`TransferDataFrom`](#Analysis.TransferDataFrom)                                                             | Transfer Data From action.                                                                                             |
| [`UnlinkDataFrom`](#Analysis.UnlinkDataFrom)                                                                 | Unlink Data From action.                                                                                               |
| [`ImportLoad`](#Analysis.ImportLoad)                                                                         | Import Load action.                                                                                                    |
| [`ExportNastranFile`](#Analysis.ExportNastranFile)                                                           | Export Nastran File.                                                                                                   |
| [`Duplicate`](#Analysis.Duplicate)                                                                           | Duplicate method.                                                                                                      |
| [`AddAcceleration`](#Analysis.AddAcceleration)                                                               | Creates a new Acceleration                                                                                             |
| [`AddAcousticAbsorptionElement`](#Analysis.AddAcousticAbsorptionElement)                                     | Creates a new AcousticAbsorptionElement                                                                                |
| [`AddAcousticAbsorptionSurface`](#Analysis.AddAcousticAbsorptionSurface)                                     | Creates a new AcousticAbsorptionSurface                                                                                |
| [`AddAcousticDiffuseSoundField`](#Analysis.AddAcousticDiffuseSoundField)                                     | Creates a new AcousticDiffuseSoundField                                                                                |
| [`AddAcousticFarFieldRadationSurface`](#Analysis.AddAcousticFarFieldRadationSurface)                         | Creates a new AcousticFarFieldRadationSurface                                                                          |
| [`AddAcousticFreeSurface`](#Analysis.AddAcousticFreeSurface)                                                 | Creates a new AcousticFreeSurface                                                                                      |
| [`AddAcousticImpedanceBoundary`](#Analysis.AddAcousticImpedanceBoundary)                                     | Creates a new AcousticImpedanceBoundary                                                                                |
| [`AddAcousticImpedanceSheet`](#Analysis.AddAcousticImpedanceSheet)                                           | Creates a new AcousticImpedanceSheet                                                                                   |
| [`AddAcousticIncidentWaveSource`](#Analysis.AddAcousticIncidentWaveSource)                                   | Creates a new AcousticIncidentWaveSource                                                                               |
| [`AddAcousticLowReducedFrequency`](#Analysis.AddAcousticLowReducedFrequency)                                 | Creates a new AcousticLowReducedFrequency                                                                              |
| [`AddAcousticMassSource`](#Analysis.AddAcousticMassSource)                                                   | Creates a new AcousticMassSource                                                                                       |
| [`AddAcousticMassSourceRate`](#Analysis.AddAcousticMassSourceRate)                                           | Creates a new AcousticMassSourceRate                                                                                   |
| [`AddAcousticPort`](#Analysis.AddAcousticPort)                                                               | Creates a new AcousticPort                                                                                             |
| [`AddAcousticPortInDuct`](#Analysis.AddAcousticPortInDuct)                                                   | Creates a new AcousticPortInDuct                                                                                       |
| [`AddAcousticPressure`](#Analysis.AddAcousticPressure)                                                       | Creates a new AcousticPressure                                                                                         |
| [`AddAcousticRadiationBoundary`](#Analysis.AddAcousticRadiationBoundary)                                     | Creates a new AcousticRadiationBoundary                                                                                |
| [`AddAcousticRigidWall`](#Analysis.AddAcousticRigidWall)                                                     | Creates a new AcousticRigidWall                                                                                        |
| [`AddAcousticStaticPressure`](#Analysis.AddAcousticStaticPressure)                                           | Creates a new AcousticStaticPressure                                                                                   |
| [`AddAcousticSurfaceAcceleration`](#Analysis.AddAcousticSurfaceAcceleration)                                 | Creates a new AcousticSurfaceAcceleration                                                                              |
| [`AddAcousticSurfaceVelocity`](#Analysis.AddAcousticSurfaceVelocity)                                         | Creates a new AcousticSurfaceVelocity                                                                                  |
| [`AddAcousticSymmetryPlane`](#Analysis.AddAcousticSymmetryPlane)                                             | Creates a new AcousticSymmetryPlane                                                                                    |
| [`AddAcousticThermoViscousBLIBoundary`](#Analysis.AddAcousticThermoViscousBLIBoundary)                       | Creates a new AcousticThermoViscousBLIBoundary                                                                         |
| [`AddAcousticTransferAdmittanceMatrix`](#Analysis.AddAcousticTransferAdmittanceMatrix)                       | Creates a new AcousticTransferAdmittanceMatrix                                                                         |
| [`AddAMOverhangConstraint`](#Analysis.AddAMOverhangConstraint)                                               | Creates a new AMOverhangConstraint                                                                                     |
| [`AddBearingLoad`](#Analysis.AddBearingLoad)                                                                 | Creates a new BearingLoad                                                                                              |
| [`AddBodyControl`](#Analysis.AddBodyControl)                                                                 | Creates a new BodyControl                                                                                              |
| [`AddCenterOfGravityConstraint`](#Analysis.AddCenterOfGravityConstraint)                                     | Creates a new CenterOfGravityConstraint                                                                                |
| [`AddCommandSnippet`](#Analysis.AddCommandSnippet)                                                           | Creates a new CommandSnippet                                                                                           |
| [`AddComplexityIndexConstraint`](#Analysis.AddComplexityIndexConstraint)                                     | Creates a new ComplexityIndexConstraint                                                                                |
| [`AddComplianceConstraint`](#Analysis.AddComplianceConstraint)                                               | Creates a new ComplianceConstraint                                                                                     |
| [`AddCompressionOnlySupport`](#Analysis.AddCompressionOnlySupport)                                           | Creates a new CompressionOnlySupport                                                                                   |
| [`AddConstraintEquation`](#Analysis.AddConstraintEquation)                                                   | Creates a new ConstraintEquation                                                                                       |
| [`AddContactStepControl`](#Analysis.AddContactStepControl)                                                   | Creates a new ContactStepControl                                                                                       |
| [`AddConvection`](#Analysis.AddConvection)                                                                   | Creates a new Convection                                                                                               |
| [`AddCoupling`](#Analysis.AddCoupling)                                                                       | Creates a new Coupling                                                                                                 |
| [`AddVoltageCoupling`](#Analysis.AddVoltageCoupling)                                                         | Creates a new Coupling                                                                                                 |
| [`AddCriterionConstraint`](#Analysis.AddCriterionConstraint)                                                 | Creates a new CriterionConstraint                                                                                      |
| [`AddCurrent`](#Analysis.AddCurrent)                                                                         | Creates a new Current                                                                                                  |
| [`AddCyclicManufacturingConstraint`](#Analysis.AddCyclicManufacturingConstraint)                             | Creates a new CyclicManufacturingConstraint                                                                            |
| [`AddCylindricalSupport`](#Analysis.AddCylindricalSupport)                                                   | Creates a new CylindricalSupport                                                                                       |
| [`AddDetonationPoint`](#Analysis.AddDetonationPoint)                                                         | Creates a new DetonationPoint                                                                                          |
| [`AddDisplacement`](#Analysis.AddDisplacement)                                                               | Creates a new Displacement                                                                                             |
| [`AddDisplacementConstraint`](#Analysis.AddDisplacementConstraint)                                           | Creates a new DisplacementConstraint                                                                                   |
| [`AddDynamicComplianceConstraint`](#Analysis.AddDynamicComplianceConstraint)                                 | Creates a new DynamicComplianceConstraint                                                                              |
| [`AddEarthGravity`](#Analysis.AddEarthGravity)                                                               | Creates a new EarthGravity                                                                                             |
| [`AddElasticSupport`](#Analysis.AddElasticSupport)                                                           | Creates a new ElasticSupport                                                                                           |
| [`AddElectricCharge`](#Analysis.AddElectricCharge)                                                           | Creates a new ElectricCharge                                                                                           |
| [`AddElementBirthAndDeath`](#Analysis.AddElementBirthAndDeath)                                               | Creates a new ElementBirthAndDeath                                                                                     |
| [`AddEMTransducer`](#Analysis.AddEMTransducer)                                                               | Creates a new EMTransducer                                                                                             |
| [`AddExtrusionManufacturingConstraint`](#Analysis.AddExtrusionManufacturingConstraint)                       | Creates a new ExtrusionManufacturingConstraint                                                                         |
| [`AddFixedRotation`](#Analysis.AddFixedRotation)                                                             | Creates a new FixedRotation                                                                                            |
| [`AddFixedSupport`](#Analysis.AddFixedSupport)                                                               | Creates a new FixedSupport                                                                                             |
| [`AddFluidSolidInterface`](#Analysis.AddFluidSolidInterface)                                                 | Creates a new FluidSolidInterface                                                                                      |
| [`AddForce`](#Analysis.AddForce)                                                                             | Creates a new Force                                                                                                    |
| [`AddFrictionlessSupport`](#Analysis.AddFrictionlessSupport)                                                 | Creates a new FrictionlessSupport                                                                                      |
| [`AddGeneralizedPlaneStrain`](#Analysis.AddGeneralizedPlaneStrain)                                           | Creates a new GeneralizedPlaneStrain                                                                                   |
| [`AddGeometryBasedAdaptivity`](#Analysis.AddGeometryBasedAdaptivity)                                         | Creates a new GeometryBasedAdaptivity                                                                                  |
| [`AddGlobalVonMisesStressConstraint`](#Analysis.AddGlobalVonMisesStressConstraint)                           | Creates a new GlobalVonMisesStressConstraint                                                                           |
| [`AddHeatFlow`](#Analysis.AddHeatFlow)                                                                       | Creates a new HeatFlow                                                                                                 |
| [`AddHeatFlux`](#Analysis.AddHeatFlux)                                                                       | Creates a new HeatFlux                                                                                                 |
| [`AddHousingConstraint`](#Analysis.AddHousingConstraint)                                                     | Creates a new HousingConstraint                                                                                        |
| [`AddHydrostaticPressure`](#Analysis.AddHydrostaticPressure)                                                 | Creates a new HydrostaticPressure                                                                                      |
| [`AddImpedanceBoundary`](#Analysis.AddImpedanceBoundary)                                                     | Creates a new ImpedanceBoundary                                                                                        |
| [`AddImportedCFDPressure`](#Analysis.AddImportedCFDPressure)                                                 | Creates a new ImportedCFDPressure                                                                                      |
| [`AddInternalHeatGeneration`](#Analysis.AddInternalHeatGeneration)                                           | Creates a new InternalHeatGeneration                                                                                   |
| [`AddJointLoad`](#Analysis.AddJointLoad)                                                                     | Creates a new JointLoad                                                                                                |
| [`AddLimitBoundary`](#Analysis.AddLimitBoundary)                                                             | Creates a new LimitBoundary                                                                                            |
| [`AddLinePressure`](#Analysis.AddLinePressure)                                                               | Creates a new LinePressure                                                                                             |
| [`AddLocalVonMisesStressConstraint`](#Analysis.AddLocalVonMisesStressConstraint)                             | Creates a new LocalVonMisesStressConstraint                                                                            |
| [`AddMagneticFluxParallel`](#Analysis.AddMagneticFluxParallel)                                               | Creates a new MagneticFluxParallel                                                                                     |
| [`AddMassConstraint`](#Analysis.AddMassConstraint)                                                           | Creates a new MassConstraint                                                                                           |
| [`AddMassFlowRate`](#Analysis.AddMassFlowRate)                                                               | Creates a new MassFlowRate                                                                                             |
| [`AddMemberSizeManufacturingConstraint`](#Analysis.AddMemberSizeManufacturingConstraint)                     | Creates a new MemberSizeManufacturingConstraint                                                                        |
| [`AddMoment`](#Analysis.AddMoment)                                                                           | Creates a new Moment                                                                                                   |
| [`AddMomentOfInertiaConstraint`](#Analysis.AddMomentOfInertiaConstraint)                                     | Creates a new MomentOfInertiaConstraint                                                                                |
| [`AddMorphingRegion`](#Analysis.AddMorphingRegion)                                                           | Creates a new MorphingRegion                                                                                           |
| [`AddNaturalFrequencyConstraint`](#Analysis.AddNaturalFrequencyConstraint)                                   | Creates a new NaturalFrequencyConstraint                                                                               |
| [`AddNodalDisplacement`](#Analysis.AddNodalDisplacement)                                                     | Creates a new NodalDisplacement                                                                                        |
| [`AddNodalForce`](#Analysis.AddNodalForce)                                                                   | Creates a new NodalForce                                                                                               |
| [`AddNodalOrientation`](#Analysis.AddNodalOrientation)                                                       | Creates a new NodalOrientation                                                                                         |
| [`AddNodalPressure`](#Analysis.AddNodalPressure)                                                             | Creates a new NodalPressure                                                                                            |
| [`AddNodalRotation`](#Analysis.AddNodalRotation)                                                             | Creates a new NodalRotation                                                                                            |
| [`AddNonlinearAdaptiveRegion`](#Analysis.AddNonlinearAdaptiveRegion)                                         | Creates a new NonlinearAdaptiveRegion                                                                                  |
| [`AddObjective`](#Analysis.AddObjective)                                                                     | Creates a new Objective                                                                                                |
| [`AddPatternRepetitionConstraint`](#Analysis.AddPatternRepetitionConstraint)                                 | Creates a new PatternRepetitionConstraint                                                                              |
| [`AddPerfectlyInsulated`](#Analysis.AddPerfectlyInsulated)                                                   | Creates a new PerfectlyInsulated                                                                                       |
| [`AddPhysicsRegion`](#Analysis.AddPhysicsRegion)                                                             | Creates a new PhysicsRegion                                                                                            |
| [`AddPipeIdealization`](#Analysis.AddPipeIdealization)                                                       | Creates a new child PipeIdealization.                                                                                  |
| [`AddPipePressure`](#Analysis.AddPipePressure)                                                               | Creates a new PipePressure                                                                                             |
| [`AddPipeTemperature`](#Analysis.AddPipeTemperature)                                                         | Creates a new PipeTemperature                                                                                          |
| [`AddPlasticHeating`](#Analysis.AddPlasticHeating)                                                           | Creates a new PlasticHeating                                                                                           |
| [`AddPressure`](#Analysis.AddPressure)                                                                       | Creates a new child Pressure.                                                                                          |
| [`AddPSDAcceleration`](#Analysis.AddPSDAcceleration)                                                         | Creates a new PSDAcceleration                                                                                          |
| [`AddPSDDisplacement`](#Analysis.AddPSDDisplacement)                                                         | Creates a new PSDDisplacement                                                                                          |
| [`AddPSDGAcceleration`](#Analysis.AddPSDGAcceleration)                                                       | Creates a new PSDGAcceleration                                                                                         |
| [`AddPSDVelocity`](#Analysis.AddPSDVelocity)                                                                 | Creates a new PSDVelocity                                                                                              |
| [`AddPullOutDirectionManufacturingConstraint`](#Analysis.AddPullOutDirectionManufacturingConstraint)         | Creates a new PullOutDirectionManufacturingConstraint                                                                  |
| [`AddPythonCodeEventBased`](#Analysis.AddPythonCodeEventBased)                                               | Creates a new PythonCodeEventBased                                                                                     |
| [`AddRadiation`](#Analysis.AddRadiation)                                                                     | Creates a new Radiation                                                                                                |
| [`AddReactionForceConstraint`](#Analysis.AddReactionForceConstraint)                                         | Creates a new ReactionForceConstraint                                                                                  |
| [`AddRemoteDisplacement`](#Analysis.AddRemoteDisplacement)                                                   | Creates a new RemoteDisplacement                                                                                       |
| [`AddRemoteForce`](#Analysis.AddRemoteForce)                                                                 | Creates a new RemoteForce                                                                                              |
| [`AddRotatingForce`](#Analysis.AddRotatingForce)                                                             | Creates a new RotatingForce                                                                                            |
| [`AddRotationalAcceleration`](#Analysis.AddRotationalAcceleration)                                           | Creates a new RotationalAcceleration                                                                                   |
| [`AddRotationalVelocity`](#Analysis.AddRotationalVelocity)                                                   | Creates a new RotationalVelocity                                                                                       |
| [`AddRSAcceleration`](#Analysis.AddRSAcceleration)                                                           | Creates a new RSAcceleration                                                                                           |
| [`AddRSDisplacement`](#Analysis.AddRSDisplacement)                                                           | Creates a new RSDisplacement                                                                                           |
| [`AddRSVelocity`](#Analysis.AddRSVelocity)                                                                   | Creates a new RSVelocity                                                                                               |
| [`AddSimplySupported`](#Analysis.AddSimplySupported)                                                         | Creates a new SimplySupported                                                                                          |
| [`AddSubstructureGenerationCondensedPart`](#Analysis.AddSubstructureGenerationCondensedPart)                 | Creates a new SubstructureGenerationCondensedPart                                                                      |
| [`AddSurfaceChargeDensity`](#Analysis.AddSurfaceChargeDensity)                                               | Creates a new SurfaceChargeDensity                                                                                     |
| [`Activate`](#Analysis.Activate)                                                                             | Activate the current object.                                                                                           |
| [`CopyTo`](#Analysis.CopyTo)                                                                                 | Copies all visible properties from this object to another.                                                             |
| [`GroupAllSimilarChildren`](#Analysis.GroupAllSimilarChildren)                                               | Run the GroupAllSimilarChildren action.                                                                                |
| [`GroupSimilarObjects`](#Analysis.GroupSimilarObjects)                                                       | Run the GroupSimilarObjects action.                                                                                    |
| [`PropertyByName`](#Analysis.PropertyByName)                                                                 | Get a property by its unique name.                                                                                     |
| [`PropertyByAPIName`](#Analysis.PropertyByAPIName)                                                           | Get a property by its API name.                                                                                        |
| [`CreateParameter`](#Analysis.CreateParameter)                                                               | Creates a new parameter for a Property.                                                                                |
| [`GetParameter`](#Analysis.GetParameter)                                                                     | Gets the parameter corresponding to the given property.                                                                |
| [`RemoveParameter`](#Analysis.RemoveParameter)                                                               | Removes the parameter from the parameter set corresponding to the given property.                                      |

### Properties

| Name | Summary |
|---------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------|
| [`CellId`](#Analysis.CellId)                                                                                        | Gets the CellId.                                              |
| [`SystemCaption`](#Analysis.SystemCaption)                                                                          | Gets the SystemCaption.                                       |
| [`InitialConditions`](InitialConditions.md#InitialConditions)                                                       | Get InitialConditions.                                        |
| [`ResultFileName`](#Analysis.ResultFileName)                                                                        | Get the full path and name of the result file.                |
| [`InternalObject`](#id0)                                                                                            | Gets the internal object. For advanced usage only.            |
| [`EnvironmentTemperature`](#Analysis.EnvironmentTemperature)                                                        | Gets or sets the EnvironmentTemperature.                      |
| [`AMProcessSimulation`](#Analysis.AMProcessSimulation)                                                              | Gets or sets the AMProcessSimulation.                         |
| [`AnalysisType`](../../../Mechanical/DataModel/Enums/GeometryImportPreference/AnalysisType.md#AnalysisType)         | Gets the AnalysisType.                                        |
| [`PhysicsType`](../../../Mechanical/DataModel/Enums/PhysicsType.md#PhysicsType)                                     | Gets the PhysicsType.                                         |
| [`Acoustics`](#Analysis.Acoustics)                                                                                  | Gets or sets the Acoustics.                                   |
| [`Electric`](#Analysis.Electric)                                                                                    | Gets the Electric.                                            |
| [`GenerateInputOnly`](#Analysis.GenerateInputOnly)                                                                  | Gets the GenerateInputOnly.                                   |
| [`Structural`](#Analysis.Structural)                                                                                | Gets or sets the Structural.                                  |
| [`Thermal`](#Analysis.Thermal)                                                                                      | Gets the Thermal.                                             |
| [`AnalysisSettings`](AnalysisSettings/AnalysisSettings.md#AnalysisSettings)                                         | Gets the AnalysisSettings.                                    |
| [`Solution`](Solution.md#Solution)                                                                                  | Gets the Solution.                                            |
| [`DataModelObjectCategory`](../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | Gets the current DataModelObject’s category.                  |
| [`Children`](#Analysis.Children)                                                                                    | Gets the list of children.                                    |
| [`Comments`](#Analysis.Comments)                                                                                    | Gets the list of associated comments.                         |
| [`Figures`](#Analysis.Figures)                                                                                      | Gets the list of associated figures.                          |
| [`Images`](#Analysis.Images)                                                                                        | Gets the list of associated images.                           |
| [`ReadOnly`](#Analysis.ReadOnly)                                                                                    | Gets or sets the ReadOnly.                                    |
| [`InternalObject`](#id0)                                                                                            | Gets the internal object. For advanced usage only.            |
| [`Properties`](#Analysis.Properties)                                                                                | Gets the list of properties for this object.                  |
| [`VisibleProperties`](#Analysis.VisibleProperties)                                                                  | Gets the list of properties that are visible for this object. |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Automation.Mechanical import Analysis
```

<a id="property-detail"></a>

## Property detail

<a id="Analysis.CellId"></a>

### *property* Analysis.CellId *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the CellId.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.SystemCaption"></a>

### *property* Analysis.SystemCaption *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the SystemCaption.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.InitialConditions"></a>

### *property* Analysis.InitialConditions *: System.Collections.Generic.IList[[Ansys.ACT.Automation.Mechanical.InitialCondition](InitialCondition.md#InitialCondition)] | [None](https://docs.python.org/3/library/constants.html#None)*

Get InitialConditions.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.ResultFileName"></a>

### *property* Analysis.ResultFileName *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Get the full path and name of the result file.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.InternalObject"></a>

### *property* Analysis.InternalObject *: Ansys.Common.Interop.DSObjectsAuto.IDSEnvironmentAuto | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.EnvironmentTemperature"></a>

### *property* Analysis.EnvironmentTemperature *: Ansys.Core.Units.Quantity | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the EnvironmentTemperature.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AMProcessSimulation"></a>

### *property* Analysis.AMProcessSimulation *: [Ansys.Mechanical.DataModel.Enums.AMProcessSimulationType](../../../Mechanical/DataModel/Enums/AMProcessSimulationType.md#AMProcessSimulationType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the AMProcessSimulation.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AnalysisType"></a>

### *property* Analysis.AnalysisType *: [Ansys.Mechanical.DataModel.Enums.AnalysisType](../../../Mechanical/DataModel/Enums/AnalysisType.md#AnalysisType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the AnalysisType.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.PhysicsType"></a>

### *property* Analysis.PhysicsType *: [Ansys.Mechanical.DataModel.Enums.PhysicsType](../../../Mechanical/DataModel/Enums/PhysicsType.md#PhysicsType) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the PhysicsType.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Acoustics"></a>

### *property* Analysis.Acoustics *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Acoustics.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Electric"></a>

### *property* Analysis.Electric *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Electric.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.GenerateInputOnly"></a>

### *property* Analysis.GenerateInputOnly *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the GenerateInputOnly.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Structural"></a>

### *property* Analysis.Structural *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the Structural.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Thermal"></a>

### *property* Analysis.Thermal *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Thermal.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AnalysisSettings"></a>

### *property* Analysis.AnalysisSettings *: [Ansys.ACT.Automation.Mechanical.AnalysisSettings.AnalysisSettings](AnalysisSettings/AnalysisSettings.md#AnalysisSettings) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the AnalysisSettings.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Solution"></a>

### *property* Analysis.Solution *: [Ansys.ACT.Automation.Mechanical.Solution](Solution.md#Solution) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the Solution.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.DataModelObjectCategory"></a>

### *property* Analysis.DataModelObjectCategory *: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory) | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the current DataModelObject’s category.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Children"></a>

### *property* Analysis.Children *: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of children.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Comments"></a>

### *property* Analysis.Comments *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Comment](Comment.md#Comment)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated comments.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Figures"></a>

### *property* Analysis.Figures *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Figure](Figure.md#Figure)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated figures.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Images"></a>

### *property* Analysis.Images *: System.Collections.Generic.IEnumerable[[Ansys.ACT.Automation.Mechanical.Image](Image.md#Image)] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of associated images.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.ReadOnly"></a>

### *property* Analysis.ReadOnly *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Gets or sets the ReadOnly.

<!-- !! processed by numpydoc !! -->

<a id="id0"></a>

### *property* Analysis.InternalObject *: System.Object | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the internal object. For advanced usage only.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Properties"></a>

### *property* Analysis.Properties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties for this object.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.VisibleProperties"></a>

### *property* Analysis.VisibleProperties *: System.Collections.Generic.IReadOnlyList[Ansys.ACT.Automation.Mechanical.Property] | [None](https://docs.python.org/3/library/constants.html#None)*

Gets the list of properties that are visible for this object.

<!-- !! processed by numpydoc !! -->

<a id="method-detail"></a>

## Method detail

<a id="Analysis.AddSymmetryManufacturingConstraint"></a>

### Analysis.AddSymmetryManufacturingConstraint()

Creates a new SymmetryManufacturingConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddTemperature"></a>

### Analysis.AddTemperature()

Creates a new Temperature

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddTemperatureConstraint"></a>

### Analysis.AddTemperatureConstraint()

Creates a new TemperatureConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddThermalComplianceConstraint"></a>

### Analysis.AddThermalComplianceConstraint()

Creates a new ThermalComplianceConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddUniformConstraint"></a>

### Analysis.AddUniformConstraint()

Creates a new UniformConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddVelocity"></a>

### Analysis.AddVelocity()

Creates a new Velocity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddViscoelasticHeating"></a>

### Analysis.AddViscoelasticHeating()

Creates a new ViscoelasticHeating

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddVoltage"></a>

### Analysis.AddVoltage()

Creates a new Voltage

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddVoltageGround"></a>

### Analysis.AddVoltageGround()

Creates a new VoltageGround

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddVolumeChargeDensity"></a>

### Analysis.AddVolumeChargeDensity()

Creates a new VolumeChargeDensity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddVolumeConstraint"></a>

### Analysis.AddVolumeConstraint()

Creates a new VolumeConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Delete"></a>

### Analysis.Delete()

Run the Delete action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.GetChildren"></a>

### Analysis.GetChildren(recurses: System.Boolean, children: System.Collections.Generic.IList[ChildrenType])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="id1"></a>

### Analysis.GetChildren(category: [Ansys.Mechanical.DataModel.Enums.DataModelObjectCategory](../../../Mechanical/DataModel/Enums/DataModelObjectCategory.md#DataModelObjectCategory), recurses: System.Boolean, children: System.Collections.Generic.IList[Ansys.Mechanical.DataModel.Interfaces.IDataModelObject])

Gets the list of children, filtered by type.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddComment"></a>

### Analysis.AddComment()

Creates a new child Comment.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddFigure"></a>

### Analysis.AddFigure()

Creates a new child Figure.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddImage"></a>

### Analysis.AddImage(filePath: System.String)

Creates a new child Image.
If a filePath is provided, the image will be loaded from that file,
if not, the image will be a screen capture of the Geometry window.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Solve"></a>

### Analysis.Solve(wait: System.Boolean)

Run the Solve action.

<!-- !! processed by numpydoc !! -->

<a id="id2"></a>

### Analysis.Solve(wait: System.Boolean, config: System.String)

Run the Solve action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.ClearGeneratedData"></a>

### Analysis.ClearGeneratedData()

Run the ClearGeneratedData action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.OpenSolverFilesDirectory"></a>

### Analysis.OpenSolverFilesDirectory()

Run the OpenSolverFilesDirectory action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.FilterBasedOnEnvironment"></a>

### Analysis.FilterBasedOnEnvironment()

Enables interface filtering that only displays model-level items applicable to
: the currently selected environment type.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddInitialVelocity"></a>

### Analysis.AddInitialVelocity()

Creates a new child Initial Velocity.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddSystemCouplingRegion"></a>

### Analysis.AddSystemCouplingRegion()

Creates a new SystemCouplingRegion

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddThermalCondition"></a>

### Analysis.AddThermalCondition()

Creates a new child ThermalCondition.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddBoltPretension"></a>

### Analysis.AddBoltPretension()

Creates a new BoltPretension

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddOptimizationRegion"></a>

### Analysis.AddOptimizationRegion()

Creates a new OptimizationRegion

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticTemperature"></a>

### Analysis.AddAcousticTemperature()

Creates a new child ThermalCondition.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddSourceConductor"></a>

### Analysis.AddSourceConductor()

Creates a new child SourceConductor.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.WriteSystemCouplingFiles"></a>

### Analysis.WriteSystemCouplingFiles(filename: System.String)

Writes the system coupling files. Usage WriteSystemCouplingFiles(“C:Desktoptempscp1.scp”);

<!-- !! processed by numpydoc !! -->

<a id="Analysis.CreateAutomaticFarFieldRadiationSurfaces"></a>

### Analysis.CreateAutomaticFarFieldRadiationSurfaces()

Run the CreateAutomaticEquivalentSourceSurfaces action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.CreateAutomaticFSI"></a>

### Analysis.CreateAutomaticFSI()

Run the CreateAutomaticFSI action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.CreateAutomaticFSIandFarFieldRadiationSurfaces"></a>

### Analysis.CreateAutomaticFSIandFarFieldRadiationSurfaces()

Run the CreateAutomaticFSIandEquivalentSourceSurfaces action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.SelectBodiesWithoutPhysicsRegion"></a>

### Analysis.SelectBodiesWithoutPhysicsRegion()

Run the SelectBodiesWithoutPhysicsRegion action to select the bodies that don’t belong to a Physics Region.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.SelectBodiesWithMultiplePhysicsRegion"></a>

### Analysis.SelectBodiesWithMultiplePhysicsRegion()

Run the SelectBodiesWithMultiplePhysicsRegion action to select the bodies that belong to more than one Physics Region.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddImportedLoadMAPDLResultsFile"></a>

### Analysis.AddImportedLoadMAPDLResultsFile()

Creates a new Import Load for MAPDL Results File.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddImportedLoadFluidsResultsFile"></a>

### Analysis.AddImportedLoadFluidsResultsFile()

Creates a new Import Load for Fluids Results File.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddImportedLoadExternalData"></a>

### Analysis.AddImportedLoadExternalData()

For Standalone Mode only. Creates a new Imported Load (External Data).

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddImportedRemoteLoadsGroup"></a>

### Analysis.AddImportedRemoteLoadsGroup()

Creates a new Import Remote Load Group.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.TransferDataFrom"></a>

### Analysis.TransferDataFrom(analysis: [Ansys.ACT.Automation.Mechanical.Analysis](#Analysis))

Transfer Data From action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.UnlinkDataFrom"></a>

### Analysis.UnlinkDataFrom(analysis: [Ansys.ACT.Automation.Mechanical.Analysis](#Analysis))

Unlink Data From action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.ImportLoad"></a>

### Analysis.ImportLoad(analysis: [Ansys.ACT.Automation.Mechanical.Analysis](#Analysis))

Import Load action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.ExportNastranFile"></a>

### Analysis.ExportNastranFile(exportOptions: [Ansys.ACT.Automation.Mechanical.NastranExportOptions](NastranExportOptions.md#NastranExportOptions))

Export Nastran File.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Duplicate"></a>

### Analysis.Duplicate()

Duplicate method.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcceleration"></a>

### Analysis.AddAcceleration()

Creates a new Acceleration

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticAbsorptionElement"></a>

### Analysis.AddAcousticAbsorptionElement()

Creates a new AcousticAbsorptionElement

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticAbsorptionSurface"></a>

### Analysis.AddAcousticAbsorptionSurface()

Creates a new AcousticAbsorptionSurface

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticDiffuseSoundField"></a>

### Analysis.AddAcousticDiffuseSoundField()

Creates a new AcousticDiffuseSoundField

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticFarFieldRadationSurface"></a>

### Analysis.AddAcousticFarFieldRadationSurface()

Creates a new AcousticFarFieldRadationSurface

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticFreeSurface"></a>

### Analysis.AddAcousticFreeSurface()

Creates a new AcousticFreeSurface

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticImpedanceBoundary"></a>

### Analysis.AddAcousticImpedanceBoundary()

Creates a new AcousticImpedanceBoundary

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticImpedanceSheet"></a>

### Analysis.AddAcousticImpedanceSheet()

Creates a new AcousticImpedanceSheet

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticIncidentWaveSource"></a>

### Analysis.AddAcousticIncidentWaveSource()

Creates a new AcousticIncidentWaveSource

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticLowReducedFrequency"></a>

### Analysis.AddAcousticLowReducedFrequency()

Creates a new AcousticLowReducedFrequency

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticMassSource"></a>

### Analysis.AddAcousticMassSource()

Creates a new AcousticMassSource

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticMassSourceRate"></a>

### Analysis.AddAcousticMassSourceRate()

Creates a new AcousticMassSourceRate

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticPort"></a>

### Analysis.AddAcousticPort()

Creates a new AcousticPort

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticPortInDuct"></a>

### Analysis.AddAcousticPortInDuct()

Creates a new AcousticPortInDuct

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticPressure"></a>

### Analysis.AddAcousticPressure()

Creates a new AcousticPressure

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticRadiationBoundary"></a>

### Analysis.AddAcousticRadiationBoundary()

Creates a new AcousticRadiationBoundary

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticRigidWall"></a>

### Analysis.AddAcousticRigidWall()

Creates a new AcousticRigidWall

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticStaticPressure"></a>

### Analysis.AddAcousticStaticPressure()

Creates a new AcousticStaticPressure

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticSurfaceAcceleration"></a>

### Analysis.AddAcousticSurfaceAcceleration()

Creates a new AcousticSurfaceAcceleration

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticSurfaceVelocity"></a>

### Analysis.AddAcousticSurfaceVelocity()

Creates a new AcousticSurfaceVelocity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticSymmetryPlane"></a>

### Analysis.AddAcousticSymmetryPlane()

Creates a new AcousticSymmetryPlane

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticThermoViscousBLIBoundary"></a>

### Analysis.AddAcousticThermoViscousBLIBoundary()

Creates a new AcousticThermoViscousBLIBoundary

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAcousticTransferAdmittanceMatrix"></a>

### Analysis.AddAcousticTransferAdmittanceMatrix()

Creates a new AcousticTransferAdmittanceMatrix

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddAMOverhangConstraint"></a>

### Analysis.AddAMOverhangConstraint()

Creates a new AMOverhangConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddBearingLoad"></a>

### Analysis.AddBearingLoad()

Creates a new BearingLoad

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddBodyControl"></a>

### Analysis.AddBodyControl()

Creates a new BodyControl

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCenterOfGravityConstraint"></a>

### Analysis.AddCenterOfGravityConstraint()

Creates a new CenterOfGravityConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCommandSnippet"></a>

### Analysis.AddCommandSnippet()

Creates a new CommandSnippet

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddComplexityIndexConstraint"></a>

### Analysis.AddComplexityIndexConstraint()

Creates a new ComplexityIndexConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddComplianceConstraint"></a>

### Analysis.AddComplianceConstraint()

Creates a new ComplianceConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCompressionOnlySupport"></a>

### Analysis.AddCompressionOnlySupport()

Creates a new CompressionOnlySupport

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddConstraintEquation"></a>

### Analysis.AddConstraintEquation()

Creates a new ConstraintEquation

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddContactStepControl"></a>

### Analysis.AddContactStepControl()

Creates a new ContactStepControl

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddConvection"></a>

### Analysis.AddConvection()

Creates a new Convection

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCoupling"></a>

### Analysis.AddCoupling()

Creates a new Coupling

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddVoltageCoupling"></a>

### Analysis.AddVoltageCoupling()

Creates a new Coupling

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCriterionConstraint"></a>

### Analysis.AddCriterionConstraint()

Creates a new CriterionConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCurrent"></a>

### Analysis.AddCurrent()

Creates a new Current

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCyclicManufacturingConstraint"></a>

### Analysis.AddCyclicManufacturingConstraint()

Creates a new CyclicManufacturingConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddCylindricalSupport"></a>

### Analysis.AddCylindricalSupport()

Creates a new CylindricalSupport

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddDetonationPoint"></a>

### Analysis.AddDetonationPoint()

Creates a new DetonationPoint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddDisplacement"></a>

### Analysis.AddDisplacement()

Creates a new Displacement

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddDisplacementConstraint"></a>

### Analysis.AddDisplacementConstraint()

Creates a new DisplacementConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddDynamicComplianceConstraint"></a>

### Analysis.AddDynamicComplianceConstraint()

Creates a new DynamicComplianceConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddEarthGravity"></a>

### Analysis.AddEarthGravity()

Creates a new EarthGravity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddElasticSupport"></a>

### Analysis.AddElasticSupport()

Creates a new ElasticSupport

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddElectricCharge"></a>

### Analysis.AddElectricCharge()

Creates a new ElectricCharge

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddElementBirthAndDeath"></a>

### Analysis.AddElementBirthAndDeath()

Creates a new ElementBirthAndDeath

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddEMTransducer"></a>

### Analysis.AddEMTransducer()

Creates a new EMTransducer

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddExtrusionManufacturingConstraint"></a>

### Analysis.AddExtrusionManufacturingConstraint()

Creates a new ExtrusionManufacturingConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddFixedRotation"></a>

### Analysis.AddFixedRotation()

Creates a new FixedRotation

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddFixedSupport"></a>

### Analysis.AddFixedSupport()

Creates a new FixedSupport

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddFluidSolidInterface"></a>

### Analysis.AddFluidSolidInterface()

Creates a new FluidSolidInterface

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddForce"></a>

### Analysis.AddForce()

Creates a new Force

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddFrictionlessSupport"></a>

### Analysis.AddFrictionlessSupport()

Creates a new FrictionlessSupport

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddGeneralizedPlaneStrain"></a>

### Analysis.AddGeneralizedPlaneStrain()

Creates a new GeneralizedPlaneStrain

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddGeometryBasedAdaptivity"></a>

### Analysis.AddGeometryBasedAdaptivity()

Creates a new GeometryBasedAdaptivity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddGlobalVonMisesStressConstraint"></a>

### Analysis.AddGlobalVonMisesStressConstraint()

Creates a new GlobalVonMisesStressConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddHeatFlow"></a>

### Analysis.AddHeatFlow()

Creates a new HeatFlow

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddHeatFlux"></a>

### Analysis.AddHeatFlux()

Creates a new HeatFlux

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddHousingConstraint"></a>

### Analysis.AddHousingConstraint()

Creates a new HousingConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddHydrostaticPressure"></a>

### Analysis.AddHydrostaticPressure()

Creates a new HydrostaticPressure

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddImpedanceBoundary"></a>

### Analysis.AddImpedanceBoundary()

Creates a new ImpedanceBoundary

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddImportedCFDPressure"></a>

### Analysis.AddImportedCFDPressure()

Creates a new ImportedCFDPressure

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddInternalHeatGeneration"></a>

### Analysis.AddInternalHeatGeneration()

Creates a new InternalHeatGeneration

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddJointLoad"></a>

### Analysis.AddJointLoad()

Creates a new JointLoad

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddLimitBoundary"></a>

### Analysis.AddLimitBoundary()

Creates a new LimitBoundary

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddLinePressure"></a>

### Analysis.AddLinePressure()

Creates a new LinePressure

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddLocalVonMisesStressConstraint"></a>

### Analysis.AddLocalVonMisesStressConstraint()

Creates a new LocalVonMisesStressConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddMagneticFluxParallel"></a>

### Analysis.AddMagneticFluxParallel()

Creates a new MagneticFluxParallel

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddMassConstraint"></a>

### Analysis.AddMassConstraint()

Creates a new MassConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddMassFlowRate"></a>

### Analysis.AddMassFlowRate()

Creates a new MassFlowRate

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddMemberSizeManufacturingConstraint"></a>

### Analysis.AddMemberSizeManufacturingConstraint()

Creates a new MemberSizeManufacturingConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddMoment"></a>

### Analysis.AddMoment()

Creates a new Moment

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddMomentOfInertiaConstraint"></a>

### Analysis.AddMomentOfInertiaConstraint()

Creates a new MomentOfInertiaConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddMorphingRegion"></a>

### Analysis.AddMorphingRegion()

Creates a new MorphingRegion

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddNaturalFrequencyConstraint"></a>

### Analysis.AddNaturalFrequencyConstraint()

Creates a new NaturalFrequencyConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddNodalDisplacement"></a>

### Analysis.AddNodalDisplacement()

Creates a new NodalDisplacement

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddNodalForce"></a>

### Analysis.AddNodalForce()

Creates a new NodalForce

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddNodalOrientation"></a>

### Analysis.AddNodalOrientation()

Creates a new NodalOrientation

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddNodalPressure"></a>

### Analysis.AddNodalPressure()

Creates a new NodalPressure

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddNodalRotation"></a>

### Analysis.AddNodalRotation()

Creates a new NodalRotation

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddNonlinearAdaptiveRegion"></a>

### Analysis.AddNonlinearAdaptiveRegion()

Creates a new NonlinearAdaptiveRegion

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddObjective"></a>

### Analysis.AddObjective()

Creates a new Objective

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPatternRepetitionConstraint"></a>

### Analysis.AddPatternRepetitionConstraint()

Creates a new PatternRepetitionConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPerfectlyInsulated"></a>

### Analysis.AddPerfectlyInsulated()

Creates a new PerfectlyInsulated

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPhysicsRegion"></a>

### Analysis.AddPhysicsRegion()

Creates a new PhysicsRegion

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPipeIdealization"></a>

### Analysis.AddPipeIdealization()

Creates a new child PipeIdealization.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPipePressure"></a>

### Analysis.AddPipePressure()

Creates a new PipePressure

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPipeTemperature"></a>

### Analysis.AddPipeTemperature()

Creates a new PipeTemperature

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPlasticHeating"></a>

### Analysis.AddPlasticHeating()

Creates a new PlasticHeating

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPressure"></a>

### Analysis.AddPressure()

Creates a new child Pressure.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPSDAcceleration"></a>

### Analysis.AddPSDAcceleration()

Creates a new PSDAcceleration

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPSDDisplacement"></a>

### Analysis.AddPSDDisplacement()

Creates a new PSDDisplacement

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPSDGAcceleration"></a>

### Analysis.AddPSDGAcceleration()

Creates a new PSDGAcceleration

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPSDVelocity"></a>

### Analysis.AddPSDVelocity()

Creates a new PSDVelocity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPullOutDirectionManufacturingConstraint"></a>

### Analysis.AddPullOutDirectionManufacturingConstraint()

Creates a new PullOutDirectionManufacturingConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddPythonCodeEventBased"></a>

### Analysis.AddPythonCodeEventBased()

Creates a new PythonCodeEventBased

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRadiation"></a>

### Analysis.AddRadiation()

Creates a new Radiation

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddReactionForceConstraint"></a>

### Analysis.AddReactionForceConstraint()

Creates a new ReactionForceConstraint

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRemoteDisplacement"></a>

### Analysis.AddRemoteDisplacement()

Creates a new RemoteDisplacement

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRemoteForce"></a>

### Analysis.AddRemoteForce()

Creates a new RemoteForce

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRotatingForce"></a>

### Analysis.AddRotatingForce()

Creates a new RotatingForce

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRotationalAcceleration"></a>

### Analysis.AddRotationalAcceleration()

Creates a new RotationalAcceleration

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRotationalVelocity"></a>

### Analysis.AddRotationalVelocity()

Creates a new RotationalVelocity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRSAcceleration"></a>

### Analysis.AddRSAcceleration()

Creates a new RSAcceleration

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRSDisplacement"></a>

### Analysis.AddRSDisplacement()

Creates a new RSDisplacement

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddRSVelocity"></a>

### Analysis.AddRSVelocity()

Creates a new RSVelocity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddSimplySupported"></a>

### Analysis.AddSimplySupported()

Creates a new SimplySupported

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddSubstructureGenerationCondensedPart"></a>

### Analysis.AddSubstructureGenerationCondensedPart()

Creates a new SubstructureGenerationCondensedPart

<!-- !! processed by numpydoc !! -->

<a id="Analysis.AddSurfaceChargeDensity"></a>

### Analysis.AddSurfaceChargeDensity()

Creates a new SurfaceChargeDensity

<!-- !! processed by numpydoc !! -->

<a id="Analysis.Activate"></a>

### Analysis.Activate()

Activate the current object.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.CopyTo"></a>

### Analysis.CopyTo(other: Ansys.ACT.Automation.Mechanical.DataModelObject)

Copies all visible properties from this object to another.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.GroupAllSimilarChildren"></a>

### Analysis.GroupAllSimilarChildren()

Run the GroupAllSimilarChildren action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.GroupSimilarObjects"></a>

### Analysis.GroupSimilarObjects()

Run the GroupSimilarObjects action.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.PropertyByName"></a>

### Analysis.PropertyByName(name: System.String)

Get a property by its unique name.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.PropertyByAPIName"></a>

### Analysis.PropertyByAPIName(name: System.String)

Get a property by its API name.
If multiple properties have the same API Name, only the first property with that name will be returned.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.CreateParameter"></a>

### Analysis.CreateParameter(propName: System.String)

Creates a new parameter for a Property.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.GetParameter"></a>

### Analysis.GetParameter(propName: System.String)

Gets the parameter corresponding to the given property.

<!-- !! processed by numpydoc !! -->

<a id="Analysis.RemoveParameter"></a>

### Analysis.RemoveParameter(propName: System.String)

Removes the parameter from the parameter set corresponding to the given property.

<!-- !! processed by numpydoc !! -->