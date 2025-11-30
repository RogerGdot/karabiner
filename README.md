# Keychron Cross-Platform Keyboard Layout

A Karabiner-Elements configuration for Keychron keyboards that provides consistent key mapping across macOS and Windows/PC environments.

## Overview

This keyboard layout eliminates the need to manually adjust your workflow when switching between Mac and PC. All keys behave identically regardless of which operating system you're using, making cross-platform work seamless and efficient.

## Features

* Unified key mapping for Mac and PC
* No mental context switching required when changing between systems
* Optimized for Keychron mechanical keyboards
* Simple installation and configuration

## Requirements

* macOS with [Karabiner-Elements](https://karabiner-elements.pqrs.org/) installed
* Keychron keyboard (tested on K-series models)

## Installation

1. Install Karabiner-Elements if you haven't already:
   ```bash
   brew install --cask karabiner-elements
   ```

2. Clone this repository or download the configuration file

3. Copy the configuration to your Karabiner config directory:
   ```bash
   cp keychron-crossplatform.json ~/.config/karabiner/assets/complex_modifications/
   ```

4. Open Karabiner-Elements preferences

5. Navigate to "Complex Modifications" tab

6. Click "Add rule" and enable the Keychron Cross-Platform layout

## Key Mappings

The layout ensures that common shortcuts and key positions work identically on both platforms:

* Command/Windows key behaves consistently
* Option/Alt key positioning matches across systems
* Function keys work as expected on both platforms
* Special keys (media controls, brightness, etc.) are unified

## Usage

Once installed and activated, simply use your keyboard normally. The layout handles all platform differences automatically. When you switch from your Mac to a PC (or vice versa), your muscle memory remains intact.

## Customization

You can modify the configuration file to suit your specific needs. The file uses Karabiner's JSON format for complex modifications.

## Compatibility

Tested and working with:
* Keychron K2, K3, K6, K8 series
* macOS 11.0 and later
* Karabiner-Elements 14.0 and later

## Contributing

Feel free to submit issues or pull requests if you have improvements or find bugs.

## License

MIT License

## Acknowledgments

* [Karabiner-Elements](https://karabiner-elements.pqrs.org/) for providing the powerful keyboard customization framework
* Keychron for making excellent cross-platform mechanical keyboards

## Support

If you encounter any issues, please open an issue on GitHub with:
* Your Keychron model
* macOS version
* Karabiner-Elements version
* Description of the problem
