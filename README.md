# tk-clipboard

A macOS clipboard manager based on the Clipy project, updated for Apple Silicon and macOS Tahoe.

## Overview

tk-clipboard is an unofficial fork of the Clipy clipboard manager.  
This fork focuses on keeping the application usable on modern Apple Silicon Macs and recent macOS versions.

## Changes

- Apple Silicon native build
- macOS Tahoe compatibility fixes
- Disabled the BartyCrouch build phase (not required for runtime)
- Fixed nib loading by explicitly using `Bundle.main`
- Updated build configuration for modern Xcode

## Status

Built and tested on Apple Silicon Macs running macOS Tahoe.

## Original Project

This project is based on the Clipy clipboard manager.

Original repository:  
https://github.com/Clipy/Clipy

## Notes

- This is an **unofficial fork**
- The name **Clipy** is not used as the product name of this fork
- This repository exists to keep the project usable on modern macOS environments

## Build

1. Clone this repository
2. Open `Clipy.xcworkspace` in Xcode
3. Build and run the project

## License

This project is based on Clipy and continues to follow the MIT License.  
See the `LICENSE` file for details.
