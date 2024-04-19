<a id="solveprocesssettings"></a>

# SolveProcessSettings

<a id="SolveProcessSettings"></a>

### *class* SolveProcessSettings

Bases: [`object`](https://docs.python.org/3/library/functions.html#object)

> The class representing solve process settings.

> <!-- !! processed by numpydoc !! -->

<a id="overview"></a>

## Overview

### Properties

| Name | Summary |
|---------------------------------------------------|-----------------------------------------------------------------------------------|
| [`DistributeSolution`](index.md#id37)             | Whether to run the solution in distributed mode.                                  |
| [`MaxNumberOfCores`](index.md#id38)               | The maximum number of cores the solver will use.                                  |
| [`NumberOfGPUDevices`](index.md#id39)             | The number of GPU devices.                                                        |
| [`AdditionalCommandLineArguments`](index.md#id40) | Any additional command line arguments to give to the solver.                      |
| [`CustomExecutablePath`](index.md#id41)           | The custom executable path for user programmable features in the solver.          |
| [`LicenseQueuing`](index.md#id42)                 | Whether license queueing is active.                                               |
| [`UseSharedLicense`](index.md#id43)               | Whether the solver will use a shared license.                                     |
| [`SolveInSynchronousMode`](index.md#id44)         | Whether the solve will be in synchronous mode.                                    |
| [`ManualSolverMemorySettings`](index.md#id45)     | Returns the manual solver memory settings.                                        |
| [`ManualLinuxSettings`](index.md#id46)            | Returns the manual linux settings.                                                |
| [`GPUAccelerationDevice`](index.md#id47)          | The GPU Acceleration device the solver will use.                                  |
| [`HybridParallel`](index.md#id48)                 | Whether to run the solution in hybrid parallel.                                   |
| [`ThreadsPerProcess`](index.md#id49)              | The threads per process the solver will use.                                      |
| [`NumberOfProcesses`](index.md#id50)              | The number of processes the solver will use.                                      |
| [`DCSAutoDownloadResults`](index.md#id51)         | Whether results need to be automatically downloaded for DCS job after completion. |

<a id="import-detail"></a>

## Import detail

```python
from ansys.mechanical.stubs.Ansys.ACT.Mechanical.Application.SolveProcessSettings import SolveProcessSettings
```

<a id="property-detail"></a>

## Property detail

<a id="SolveProcessSettings.DistributeSolution"></a>

### *property* SolveProcessSettings.DistributeSolution *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Whether to run the solution in distributed mode.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.MaxNumberOfCores"></a>

### *property* SolveProcessSettings.MaxNumberOfCores *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

The maximum number of cores the solver will use.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.NumberOfGPUDevices"></a>

### *property* SolveProcessSettings.NumberOfGPUDevices *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

The number of GPU devices.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.AdditionalCommandLineArguments"></a>

### *property* SolveProcessSettings.AdditionalCommandLineArguments *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

Any additional command line arguments to give to the solver.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.CustomExecutablePath"></a>

### *property* SolveProcessSettings.CustomExecutablePath *: System.String | [None](https://docs.python.org/3/library/constants.html#None)*

The custom executable path for user programmable features in the solver.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.LicenseQueuing"></a>

### *property* SolveProcessSettings.LicenseQueuing *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Whether license queueing is active.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.UseSharedLicense"></a>

### *property* SolveProcessSettings.UseSharedLicense *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Whether the solver will use a shared license.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.SolveInSynchronousMode"></a>

### *property* SolveProcessSettings.SolveInSynchronousMode *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Whether the solve will be in synchronous mode.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.ManualSolverMemorySettings"></a>

### *property* SolveProcessSettings.ManualSolverMemorySettings *: [Ansys.ACT.Mechanical.Application.SolveProcessSettings.SolverMemorySettings](SolverMemorySettings.md#SolverMemorySettings) | [None](https://docs.python.org/3/library/constants.html#None)*

Returns the manual solver memory settings.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.ManualLinuxSettings"></a>

### *property* SolveProcessSettings.ManualLinuxSettings *: [Ansys.ACT.Mechanical.Application.SolveProcessSettings.LinuxSettings](LinuxSettings.md#LinuxSettings) | [None](https://docs.python.org/3/library/constants.html#None)*

Returns the manual linux settings.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.GPUAccelerationDevice"></a>

### *property* SolveProcessSettings.GPUAccelerationDevice *: [Ansys.Mechanical.DataModel.Enums.GPUAccelerationDevicesType](../../../../Mechanical/DataModel/Enums/GPUAccelerationDevicesType.md#GPUAccelerationDevicesType) | [None](https://docs.python.org/3/library/constants.html#None)*

The GPU Acceleration device the solver will use.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.HybridParallel"></a>

### *property* SolveProcessSettings.HybridParallel *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Whether to run the solution in hybrid parallel.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.ThreadsPerProcess"></a>

### *property* SolveProcessSettings.ThreadsPerProcess *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

The threads per process the solver will use.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.NumberOfProcesses"></a>

### *property* SolveProcessSettings.NumberOfProcesses *: System.Int32 | [None](https://docs.python.org/3/library/constants.html#None)*

The number of processes the solver will use.

<!-- !! processed by numpydoc !! -->

<a id="SolveProcessSettings.DCSAutoDownloadResults"></a>

### *property* SolveProcessSettings.DCSAutoDownloadResults *: System.Boolean | [None](https://docs.python.org/3/library/constants.html#None)*

Whether results need to be automatically downloaded for DCS job after completion.

<!-- !! processed by numpydoc !! -->