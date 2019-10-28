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
