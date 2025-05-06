# ILA1016
## Hardware Description


## Software Description
- sigrok is an open-source suite of software projects -- all focused on supporting signal analysis tools. The project includes:

- PulseView -- A logic analyzer front end with a simple GUI.
- sigrok-cli -- A command line interface for sigrok -- useful for scripting tests or running on a headless machine.
- fx2grok -- A collection of open-source hardware LA layouts, schematics, and BOM's.
With an eye towards logic analyzers, this tutorial will focus mostly on PulseView.

## Get the Software

- Download the latest PulseView release from sigrok's Downloads page. Here are direct links for the latest Windows, Mac,    and Linux downloads:

  - [Windowsx](https://sigrok.org/wiki/Windows#Windows_installers)
  - [Mac OS X](https://sigrok.org/wiki/Mac_OS_X)
  - [Linux](https://sigrok.org/wiki/Downloads#Binaries_and_distribution_packages)

- Windows users can run the installer executable (pulseview-NIGHTLY-32bit-static-release-installer.exe) to install the software on your machine. The Mac installer is a binary disk image (DMG), which can be dragged into your Applications folder, for example.

## Setting up the Software/Hardware

- With PulseView open, plug in your USB Logic Analyzer. You should see faint red and green LEDs illuminate under the sticker.

  - Click the "\" dropdown menu.
  - Select fx2lafw (generic driver for FX2 based LAs) from the dropdown.
  - Select USB for the interface
  - Click Scan for devices using driver above
  - Select "Logic with 8 channels" and click "OK"