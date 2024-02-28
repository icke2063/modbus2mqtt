
## [2024.02.1] - 2024-02-28 Feature Release

- Read input register

- Basic support of big and little endian registers

- Read multi-byte value in big and little endian order

- Fix the default value of length to 1 ( as in the readme)


## [2023.10.6] - 2023-10-22 Bugfix Release

- Fixed pollms was ignored

## [2023.10.5] - 2023-10-22 Bugfix Release

- Fixed missing message retain

- Fixed invalid topic for missing root prefix issue


## [2023.10.3] - 2023-10-22 New Features

- Support rpc topic for changing coil states (see examples/Unipi-Neuron example)

- Modbus polling interval can now be configured using pollms (default is 1000)

- Supports publishing the state of multiple coils (see examples/Unipi-Neuron example)

- Each modbus source will publish "online = true|false" to indicate the poller state

- Modbus sources can be disabled without removing their configuration by setting enabled: false

- The mqtt client id can be now specified using clientid (default is modbus2mqtt)

- The root topic_prefix has become optional which means each source can start at a different path


## [2023.10.2] - 2023-10-02 First Release
