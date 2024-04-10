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

Contributions are welcome! Please read the [contributing guidelines] before making any changes.

## License

This project is licensed under the terms of the MIT license. See the [LICENSE](LICENSE) file for details.

# Contributing to RubberDucky

We would love for you to contribute to RubberDucky! Here are some guidelines for doing so:

## Code of Conduct

When participating in this project, we ask that you follow our code of conduct.

## Contribution Process

1. Fork the repository and create a new branch for your changes.
2. Make your changes in your branch.
3. Submit a pull request with your changes.
4. Wait for us to review your pull request. We might ask you to make some changes.
5. Once your pull request is approved, it will be merged into the main branch.

## Code Standards

Please make sure to follow our code standards. This includes things like using comments and adhering to certain naming conventions.

## Testing

If you're contributing with code, we ask that you include tests that demonstrate that your code works as expected.

Thank you for contributing to RubberDucky!
