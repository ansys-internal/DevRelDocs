# ansys.meshing.prime.FileIO.get_abaqus_simulation_data

#### FileIO.get_abaqus_simulation_data(partId)

Get Simulation document generated by Abaqus import for a given part.

This method will return the JSON Simulation Document for a part if the part exists. Otherwise,
it returns an empty string.

* **Parameters:**
  **partId**
  : Part Id.
* **Returns:**
  [`str`](https://docs.python.org/3.11/library/stdtypes.html#str)
  : Returns the string containing a JSON document for simulation data.
* **Return type:**
  [`str`](https://docs.python.org/3.11/library/stdtypes.html#str)

### Notes

This API is a Beta. API Behavior and implementation may change in future.

### Examples

```pycon
>>> import json
>>> simdata = json.loads(file_io.get_abaqus_simulation_data(2)
```

<!-- !! processed by numpydoc !! -->