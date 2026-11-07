# Bear-Buddy Controller Board

## (a) Description

This PCB is the main board for the TomatoCube Bear-Buddy DIY Desktop Companion kit, powered by the ESP32-C3 SuperMini module. Designed for hands-on STEM learning, the kit lets users solder and assemble their own desktop companion, then explore physical computing through a set of on-board peripherals: an LED, an infrared (IR) sensor, tactile switches and a NeoPixel output driving a 5x5 RGB matrix. Bear-Buddy can be programmed with MicroBlocks block coding or CircuitPython.

<img src="images/Bear-Buddy DIY Tabletop Toy.png" width="600" height="auto"/>



## (b) Instructions

Please refer to the **Bear-Buddy Quick Start Guide** for soldering, assembly and first-use instructions.

👉 [Bear-Buddy Quick Start Guide](https://github.com/TomatoCube18/Docs/tree/main/Box%2010%20-%20Bear-Buddy%20DIY%20Desk%20Companion)

For a step-by-step visual walkthrough of the build, see the [Bear-Buddy Animated Assembly Guide](https://tomatocube.com/file_dir/workshop_BearBuddy/Files_v1/Misc/AssemblyGuide/).

## (c) Firmware

Bear-Buddy firmware is loaded straight from your web browser - no software installation needed.

Open the loader:
👉 [TomatoCube ESP32-C3 Firmware Updater](https://tomatocube.com/file_dir/misc_files/ESP32-C3_Flasher/)

1. Which board do you have? - choose the 5x5 NeoPixel matrix version (Bear-Buddy).
2. What should it run? - choose your firmware:
   * MicroBlocks - if you are starting out with block coding
   * CircuitPython - if you are ready to write Python code
3. Flash it
   * Tick Erase everything first when switching between firmware types. Note: this deletes any programs and files saved on the board.
   * Hold Boot button and Toggle the Reset button to enter firmware uploader mode.
   * Press Flash firmware.
   * Select your board's serial port in the pop-up and click Connect.
4. Wait for the progress bar to reach 100%.
5. Press the Reset button (or unplug and replug) to start the new firmware.
