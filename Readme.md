# ZMK Hillside keyboards firmware

## Status

- ?? The Nice!view display works well on both sides.

## Next

- Restore the default keymap to the board definition.

- Take notes for default keymap as needed.

## Start of Future Readme

This is the default ZMK firmware for Hillside keyboards.

-   Hillside Dactyl 50
    -   A simple to start with QWERTY keymap using three main layers
        and one adjust layer.
    -   The configuration enables the nice!view display,
        but disables the LED's as they eat batteries.
    -   A hardware testing layer can be uncommented to enable easier one sided
        access to adjust layer type functions for hardware build testing.

The repo is a module that can be included into the main ZMK config.

### TODO

- link to D50 repo

## See also

### ZMK module repo setup

The user default files were created by following:

- [Configuration Overview](https://zmk.dev/docs/config)

The ZMK guides used for this module based configuration:

- [New keyboard shield guide](https://zmk.dev/docs/development/new-shields)
- [RGB Underglow](https://zmk.dev/docs/features/underglow#adding-rgb-underglow-to-a-board)
  Using the nice!nano two-part pin numbers, not the Arduino ones.

I also cribbed module repo structure off of sadekbaroudi's
[fingerpunch repo](https://github.com/sadekbaroudi/zmk-fingerpunch-keyboards).
