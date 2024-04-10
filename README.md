# RubberDucky With a Raspberry Pi Pico

This repository contains payloads for Windows and Linux using a Raspberry Pi Pico configured as a RubberDucky.

## Setup

To configure your Raspberry Pi Pico, follow these steps:

1. Copy `flash_Nuke` onto your Raspberry Pi Pico.
2. Copy `adafruit-circuitpython` onto your Raspberry Pi Pico.
3. Replace the automatically created `code.py` with the one from this repository.
4. Delete the existing `lib` directory on the Raspberry Pi Pico and replace it with the one from this repository.

## Payload Structure

Payloads are written in Ducky Script. Here's the basic structure:

1. `REM` - Used for comments.
2. `DELAY` - Adds a delay in milliseconds.
3. `STRING` - Inserts the string you want.
4. `ENTER` - Simulates pressing the Enter key.
5. `GUI` - Simulates pressing the Windows key.

Other keys like `ALT` or `CONTROL` can be found in the `Keycode.py` file.

**Note:** This RubberDucky is configured to work with a Spanish keyboard!

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) before making any changes.

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.
