# Sub-GHz Signal Files 📡

This folder contains Sub-GHz radio signal captures for the Flipper Zero. These files can be transmitted using the Flipper's Sub-GHz radio module.

## ⚠️ Legal Warning

**IMPORTANT**: Only transmit these signals where you have legal authorization. Many frequencies are regulated, and unauthorized transmission may be illegal in your jurisdiction.

## Contents

### Ceiling Fan Controls (Harbor Breeze FAN-11T)
- **Fan-High.sub** - Set fan to high speed
- **Fan-Low.sub** - Set fan to low speed
- **Fan-Medium.sub** - Set fan to medium speed
- **Fan-off.sub** - Turn fan off
- **Light-Toggle.sub** - Toggle fan light on/off

### Gate/Garage Door Openers
- **came.sub** - CAME protocol gate opener
- **doorhan.sub** - Doorhan protocol gate opener
- **nice_flo.sub** - Nice Flo protocol gate opener
- **princeton.sub** - Princeton protocol remote

## Usage

1. Copy `.sub` files to your Flipper Zero's SD card in the `subghz` folder
2. Navigate to **Sub-GHz** app on your Flipper
3. Select **Saved** from the menu
4. Choose the signal file you want to transmit
5. Press **Send** to transmit

## Frequency Information

Most files use common ISM band frequencies:
- 315 MHz (North America)
- 433 MHz (Europe, Asia)
- 868 MHz (Europe)
- 915 MHz (North America)

## Sources

- ErikLentz/Flipper-Finds
- Official Flipper Zero SD card examples
- Community signal captures

## Disclaimer

Only use these files for educational purposes and on systems you own or have permission to test.
