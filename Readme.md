# Hillside Dactyl 50 ZMK firmware

> [!Note]
> -   The commit history might change while I finish publishing this board.
>     I wouldn't fork this yet.
> -   The board this is for isn't public yet.


This is the default ZMK firmware for the Hillside Dactyl 50 keyboard.
It features:

-   A simple QWERTY keymap using three main layers
    and one adjust layer. Providing an easy starting layout.
-   The configuration enables the nice!view display and the bare LED.
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

I also cribbed module repo structure from sadekbaroudi's
[fingerpunch repo](https://github.com/sadekbaroudi/zmk-fingerpunch-keyboards).
