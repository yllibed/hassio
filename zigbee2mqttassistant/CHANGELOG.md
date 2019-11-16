# Version 0.3.105
* Changed the default value of `AutosetLastSeen` to `false`. <https://github.com/yllibed/Zigbee2MqttAssistant/issues/117>

# Version 0.3.95
* Added new `AllowJoinTimeout` setting to auto-off _allow join_ of Zigbee network. Default is 20 minutes.
* Removed old `zigbee2mqttassistant-aarch64` package from hass.io store.

# Version 0.3.90
* [Bug #92](https://github.com/yllibed/Zigbee2MqttAssistant/issues/92) Fix useless error in log when sending a command (`/set` topic) to a device with a slash (`/`) in its name

# Version 0.3.89
* Migrated from netcore2.2 to netcore3.0
* Now using _alpine_ image for containers (still official Microsoft images)
* Experimental support for ARM64/aarch64

# Version 0.3.88
* Improved compatibility with next version of Zigbee2Mqtt (edge version)
* Always fetch the css files locally instead of trying from the cloud first.
* Now prints the version information on start

# Version 0.3.87
* Removed useless warning in output log
* "Last_seen" now supports any format + new auto-set when not activated (can be disabled)
* Added support for last_seen in devices list Koenkk/zigbee2mqtt#1910
* Added support for various format of last_seen (epoch & ISO formats)
* Added ability to set last_seen feature when not activated on Z2M
* Added a protection against concurrent network scans

# Version 0.3.82
* Creation of a "dev" branch for testing prereleases. The `zigbee2mqttassistant` will only receive builds known to be good and tested. If you want the latest more buggy version, switch to `zigbee2mqttassistant-dev`.

# Version 0.3.1
* Fixed a bug in previous version (0.3.0) were many network could be launched at the same time.
* Added a manual network scan feature
* Reduced the network scan rate to 3 hours

# Version 0.3.0
* Added ability to configure polling schedule. [More information here](https://github.com/yllibed/Zigbee2MqttAssistant#settings).

# Version 0.2.0-dev.150
* Added ability to deactivate certificate check when using TLS (useful for self-signed certificates).

# Version 0.2.0-dev.144
* Improved the new network map to show inactive links as red.

# Version 0.2.0-dev.131
* Improved the new network map + fixed few glitches.

# Version 0.2.0-dev.120
* Added an interactive map visualizer
* Javascript files are now served locally, so it will work even if your browser is not connected to Internet.

# Version 0.2.0-dev.115
* Improved support for _dev_ version of Zigbee2Mqtt.
* Fixed glitches when using `/` in a device name.
* Improved logging by removing annoying useless messages.

# Version 0.2.0-dev.94
* Fixed warning `zigbee2mqtt/bridge/config/remove`.
* Now supports devices with a `/` in their name.
* Stop displaying the coordinator (Z2M edge) as a no-components device.

# Version 0.2.0-dev.66
* Added battery level informations + warning on low battery.
* Hide useless (unreliable) _offline_ indicator. Should come back when this will be fixed in _Zigbee2Mqtt_.
  https://github.com/Koenkk/zigbee-herdsman/issues/13
* Remove useless warnings in output log.
* Hide "route to coordinator" in device information until properly implemented..

# Version 0.2.0
* Added support for ARMv7 (Raspberry Pi).
