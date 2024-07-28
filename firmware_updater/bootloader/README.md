# Selfbus Bootloader

**The Bootloader is used to update the firmware of Selfbus devices.**

Information on usage [Wiki Selfbus Firmware-Updater](https://selfbus.org/wiki/software/tools/7-selfbus-bus-updater-tool).

Flashing an Selfbus ARM-controller [Wiki Flashen der Module und Controller](https://selfbus.org/wiki/software/tools/8-how-to-flash-modules-and-controllers).

## File name abbreviations

| abbr.       | Meaning                                                                                                                                                                                                                                                        |
|-------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| aprog       | for Devices with an non Selfbus "standard" programming button e.g. [Schaltaktor 6-fach strommessend 230V 16A 6TE](https://selfbus.org/wiki/devices/outputs/22-switching-actuator-6x-current-sensing-230v-16a-6mount-units).                                    |
| gnax        | for Devices with the [lpc1115_io16_FM (gnax)](https://github.com/selfbus/hardware-merged/tree/main/controller_lpc1115/lpc1115_io16_FM) controller e.g. [UP Raumtemperaturregler](https://selfbus.org/wiki/devices/sensors/64-in-wall-ambient-temp-controller). |
| (lpc11xx)   | legacy (removed from project name)                                                                                                                                                                                                                                                         |