# iButton Keys 🔑

This folder contains iButton (1-Wire) key files for the Flipper Zero. iButton keys are used in access control systems and are common in building entry systems.

## Contents

### iButton Files
- **Cyfral.ibtn** - Cyfral protocol key example
- **Dallas.ibtn** - Dallas/Maxim 1-Wire protocol key example  
- **Metakom.ibtn** - Metakom protocol key example

## Usage

1. Copy `.ibtn` files to your Flipper Zero's SD card in the `ibutton` folder
2. Navigate to **iButton** app on your Flipper
3. Select **Saved** from the menu
4. Choose the key you want to emulate
5. Hold the Flipper's iButton probe against a compatible reader

## Protocols

- **Dallas/Maxim** - Most common 1-Wire protocol (DS1990A, etc.)
- **Cyfral** - Russian access control system protocol
- **Metakom** - Another Russian access control protocol

## ⚠️ Legal Notice

These are example files for educational and testing purposes only. Only use on systems you own or have explicit permission to test. Unauthorized access is illegal.

## Sources

- Official Flipper Zero SD card examples
- Community contributions

## Additional Resources

For more information about iButton technology:
- [Maxim/Dallas 1-Wire Protocol](https://www.maximintegrated.com/en/products/ibutton-one-wire.html)
- [Flipper Zero Documentation](https://docs.flipperzero.one/)
