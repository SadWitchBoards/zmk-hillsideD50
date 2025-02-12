# ZMK for Hillside Dactyl 50 0.1.0-alpha.1

This is firmware for the Hillside D50. 
But it is bare-bones, only sufficient to:

- send key press signals from a hybrid D50 right to a 52 left.
- test nice!view on the left.

## Status

- It works as the right-hand side of a D50 right 52 left pairing.
- The keymap is QWERTY but with several debug keys on the base and adjust layers
- The Nice!view display works well on both sides.

## Next

- Restore the default keymap to the board definition.

- Take notes for default keymap as needed.
- Otherwise, nothing current. Use as is until get a left D50 board.

## Start of Future non-hybrid content

This is the default ZMK firmware for the Hillside D50 ergonomic keyboard.
It provides a simple to start with QWERTY layout,
  enables the nice!view display, but disables the LED's.

### TODO

- link to D50 repo


## See also

The user default files were created by following:

- [Configuration Overview](https://zmk.dev/docs/config)

The ZMK guides used for this module based configuration:

- [New keyboard shield guide](https://zmk.dev/docs/development/new-shields)
- [RGB Underglow](https://zmk.dev/docs/features/underglow#adding-rgb-underglow-to-a-board)
  Using the nice!nano two-part pin numbers, not the Arduino ones.
