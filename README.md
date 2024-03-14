# axp2101testing
Investigating the AXP2101 power mgmt IC on the M5Stack Core2 V1.1

The Core2 V1.1 does not turn on automatically when used as a dedicated controller for a device with an external battery.
The user must also press and hold the ON button on the side of the CORE2 when used as the controller for the Safecast.org bGeigie Zen.

This repo holds various attempts to configure the registers to automatically turn on when the slider switch is closed to feed VBAT
from the battery while the USB power is not available.
