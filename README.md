
# BLE_TOOL

 * BLE_TOOL: is in directory qscanner and is a QT program. Open the .pro file with qt-creator.
 * ble_tool_nrf52_fw: contains firmware for the NRF52 platform that runs a "lisp" interpreter and some BLE services.

## Getting started

   1. execute the get_lispbm.sh script in the ble_tool_nrf52_fw directory.
   2. execute the setup_fw_build.sh script in the BLE_S root directory.
   3. go into ble_tool_nrf_fw_build (created in step 2.) and run make
   4. run make flash (if you have the luxurious nordic semicondocturs board with  built in programmer) otherwise use the flash_stlink.sh script.
   

## Videos on the topic of this repository

[background](https://youtu.be/drmXdoRu3AQ)

[Implementing get_char and put_char on nrf52](https://youtu.be/auHo9wq7pX4)

[lispBM porting effort](https://youtu.be/cXSavxC3th0)

[A first attempt at get_char and put_char over BLEUart](https://youtu.be/WUHqMYLLUQ0)
