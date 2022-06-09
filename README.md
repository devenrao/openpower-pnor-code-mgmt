# openpower-pnor-code-mgmt
OpenPower PNOR (Processor NOR) Code Management provides a set of host software
management applications for OpenPower systems. The host firmware is stored on
the PNOR chip.
More information can be found at
[Software Architecture](https://github.com/openbmc/phosphor-dbus-interfaces/blob/master/yaml/xyz/openbmc_project/Software/README.md)
or
[Host Code Update](https://github.com/openbmc/docs/blob/master/code-update/host-code-update.md)

## To Build
To build this package, do the following steps:

1. `meson build`
2. `ninja -C build`

To clean the repository run `rm -r build`.
