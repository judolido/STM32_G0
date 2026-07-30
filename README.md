# STM32_G0
A custom dev board based on an STM32G070RBT6 or any other similar MCU with the same pinout.

No debugger/programming chip is present on the board. A Nucleo board's ST-Link (or an equivalent, e.g. a $5 AliExpress USB stick 🙂) should be used instead. Some non-official ST-Link clones may fail to correctly identify the MCU, or may even be unable to program it if the MCU is from a newer generation.

Some SD cards may not work correctly, since certain required pull-up resistors are not present on the board. Please refer to your specific SD card's documentation to determine compatibility.
