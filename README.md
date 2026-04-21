# VZBot 330

This repository documents my real-world VZBot 330 project, including build notes, firmware issues, power changes, CAN bus migration, bed leveling improvements, fixes, and future upgrades.

This is not an official guide and not a polished “happy path” build. It is a practical reference based on what I actually ran into while getting the printer working reliably.

## What this repo covers

* Mechanical build notes
* Firmware and Klipper setup issues
* OrcaSlicer adjustments
* Power supply changes
* USB communication problems
* CAN bus setup with Waveshare CAN HAT
* Beacon setup and bed scanning
* PT1000 / sensor-related fixes
* Future upgrades such as enclosure, noise reduction, and refinement

## Current hardware context

This project is based on my VZBot 330 setup using:

* Raspberry Pi 3B+
* Waveshare 2-Channel CAN HAT
* Meanwell RSP500 power supplies
* Beacon probe
* Mellow kit hardware

## Important

These files are shared as a working reference, not as a universal copy-paste solution.

You may need to adapt:

* printer configuration
* MCU IDs / UUIDs
* CAN settings
* bed size / offsets
* slicer settings
* hardware-specific values

Always verify values before applying them to your own machine.

## Repository structure

* `build/` → assembly notes and build issues
* `firmware/` → Klipper, Mainsail, slicer, and config notes
* `power/` → PSU changes and power-related debugging
* `canbus/` → CAN setup, wiring, notes, and commands
* `bed-leveling/` → Beacon setup and first-layer improvements
* `fixes/` → issue-specific fixes and replacements
* `upgrades/` → future improvements and modifications
* `assets/` → images, diagrams, and supporting media

## Related video

This repo supports the VZBot 330 videos published on the Performance Forge Projects YouTube channel.

## Goal

The goal of this repo is simple:
to save other builders time, frustration, and unnecessary trial and error.

If the documentation around this project improves over time, great. Until then, this repo is my attempt to make the process clearer and more usable.
