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
