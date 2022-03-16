# OpenBar examples for STM32 boards

This example is used to show an OpenBar project configured in a standard way
and using git submodules.

Its purpose is to create a minimal firmware for an STM32F407G-DISC1 board.

## Usage

```bash
# Clone the repository (with submodules)
git clone --recurse-submodules https://github.com/openbar/stm32-examples

# Move to the freshly cloned directory
cd stm32-examples

# Configure the build
make stm32f407g-disc1_defconfig

# Build the firmware
make

# Optionally, flash the firmware
make flash
```

## Further Reading

For more information about the OpenBar project, the specifications of
the `openbar` build system, and to discover some examples, please visit
the project documentation:

> https://openbar.github.io

## License

The `stm32-examples` is released under the [Unlicense](LICENSE.md).

## Credits

The `stm32-examples` is using the [`libopencm3`][libopencm3] project.

[libopencm3]: https://github.com/libopencm3
