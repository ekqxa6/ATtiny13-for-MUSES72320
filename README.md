# MUSES72320

> MUSES72320 and ATtiny13


## Building and flash firmware

Firmware of this module is developed using AVR-GCC toolchain. To build the firmware execute the `make` command.

To flash the compiled firmware, use the following set of commands:

    make fuse
    make flash

The `make fuse` command can use to set up the fuse-bits of the MCU and it needs to execute only once.

## License

This is an open-source hardware project. Compiled firmware, PCB designs, schematic, and source codes related to this project are available at this repository. 

The firmware of this project is licensed under the terms of [MIT license](https://github.com/dilshan/mcp4141-digital-pot/blob/master/LICENSE). Hardware design and related content are licensed under [Creative Commons - Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)) license.
