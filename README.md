# ESP32_WROVER_iot_module
This board is ESP32 WROVER developer module.<br>
<img src="https://github.com/Nanraka/ESP32_WROVER_iot_module/assets/64336110/bead5d89-8143-4f17-aad9-fab2aac88c69" width="320px">

# Features
Unlike other boards, this board is designed to be used for IoT applications.<br>
There are no peripheral parts such as writing ICs, sensors, or tact switches, but a universal pattern is implemented, so that any necessary parts can be added.<br>

# How to use
Since this board is not equipped with a write IC, the following two procedures are used for writing.
1. Prepare a usb serial converter by yourself and connect Tx, Rx, Vcc, and GND on the board. Make sure that the logic voltage of the usb serial converter is 3.3v.
2. Press and hold the reset and boot buttons on the board.
3. Press the write button on the ArduinoIDE.
4. Release the reset button.
5. Release the boot button.
