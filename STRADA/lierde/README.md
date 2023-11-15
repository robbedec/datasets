# Dataset description

Dataset description to reproduce the results from the paper "Fully automatic camera for personalized highlight generation of sport events". All personal information was removed and IDs linked to somebody's sensor and transponder categorically randomized.

## Received sensor values

Contains for each sensor value:
- A UTC timestamp (ts_received)
- The location of the pole which received it (recording_metadata)
- The pseudo ID to identiy the sensor (device_id_anon)

file: [sensor-values-lierde-anon.csv](./sensor-values-lierde-anon.csv)

## Timing transponder lap times

Contains for each passing at the finish:
- A UTC timestamp (timestamp)
- The pseudo ID to identiy the transponder (code_anon)

file: [transponder-lierde-anon.csv](./transponder-lierde-anon.csv)

## Sensor-transponder pairs

Indicates which timing transponder and sensors were mounted on the same bike.
Contains:
- A link to the key of the transponder (code_anon)
- A link to the key of the sensor (device_id_anon)

file: [transponder-sensor-pairs-anon.csv](./transponder-sensor-pairs-anon.csv)
