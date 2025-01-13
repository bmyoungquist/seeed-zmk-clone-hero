# Clone Hero Controller Firmware
This repository contains the source code and pre-built firmware for a clone her controller.

You will need A [Seeed Studio XIAO nRF52840](https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html?srsltid=AfmBOor7jsrTZo_FE_zGTQSJWiMt5fpo-N5JF-2KJujgZ6OPShxYm69q). Buy the non-"sense" board as you don't need the extra features.

To flash the board, plug it into your PC and double tap the RST button. You should hear a click when pressing the button. After double tapping the button, the board should show up as a drive in your file explorer. Download and copy the `clone_hero_controller-seeeduino_xiao_ble-zmk.uf2` file from the [latest release](https://github.com/bmyoungquist/seeed-zmk-clone-hero/releases) onto the board.

The GPIO pins are mapped to buttons from the first fret all the way down to the star button in a linear fashion, GPIO-0 being the green/first fret button and the star button being GPIO-8.