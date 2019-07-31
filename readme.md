# TLSR823x Family


The TLSR823x integrates a power-balanced 32-bit proprietary MCU, a high-performance BLE/2.4GHz Radio, SRAM, embedded flash or OTP, a general-purpose ADC, a quadrature decoder (QDEC), PWM, flexible I/O interfaces and other peripheral blocks required for Bluetooth Low Energy application development.

| Part Number      | Package | Size     | SRAM (KB) | Flash (KB) | Tx    | Rx                           | Power Consumption                                      | Protocol |
|------------------|---------|----------|-----------|------------|-------|------------------------------|--------------------------------------------------------|----------|
| TLSR8232F512ET32 | QFN32   | 5×5      | 16        | 512        | +8dBm | -92dBm@BLE1M                 | 13.6mA@Rx_fullchip 14.5mA@Tx0dBm_fullchip 1.35uA@sleep | BLE 5.0* |
| TLSR8232F128ET24 | QFN24   | 4×4      | 16        | 128        | +8dBm | -92dBm@BLE1M                 | 13.6mA@Rx_fullchip 14.5mA@Tx0dBm_fullchip 1.35uA@sleep | BLE 5.0* |
| TLSR8230ES16     | TSSOP16 | 4.96×4.4 | 8         | 16KB OTP   | +7dBm | -91.5dBm@BLE1M-88dBm@BLE2M   | 13.6mA@Rx_fullchip 14.5mA@Tx0dBm_fullchip 1.4uA@sleep  | BLE 5.0* |
| TLSR8231ET24     | QFN24   | 4×4      | 8         | 16KB OTP   | +7dBm | -91.5dBm@BLE1M-88dBm@BLE2M   | 13.6mA@Rx_fullchip 14.5mA@Tx0dBm_fullchip 1.4uA@sleep  | BLE 5.0* |
| TLSR8369ET24     | QFN24   | 4×4      | 8         | 16KB OTP   | +7dBm | -91.5dBm@2.4G1M-88dBm@2.4G2M | 13.6mA@Rx_fullchip 14.5mA@Tx0dBm_fullchip 1.4uA@sleep  | 2.4G     |
| TLSR8369ET40     | QFN40   | 6×6      | 8         | 16KB OTP   | +7dBm | -91.5dBm@2.4G1M-88dBm@2.4G2M | 13.6mA@Rx_fullchip 14.5mA@Tx0dBm_fullchip 1.4uA@sleep  | 2.4G     |


## TLSR823x Reference Design

| Reference Design   | Chipset  | Quick Guide                | SDK Download | SDK Development Manual | HW Design Document                |
|--------------------|----------|----------------------------|--------------|------------------------|-----------------------------------|
| BLE Generic        | TLSR8232 |                            | [SDK V1.2.0](http://wiki.telink-semi.cn/tools_and_sdk/BLE_SDK/823x_SDK/ble_sdk.zip)   |                        | [8232 Generic Ref](http://wiki.telink-semi.cn/doc/hw/TLSR8232_Developmentboard_TLSR8232DK32D.zip)                  |
| BLE Remote Control | TLSR8232 | [Remote Control Quick Guide](http://wiki.telink-semi.cn/doc/an/PS_18032600-E_Spec%20For%20Telink%20TLSR8232-based%20BLE%20Remote%20Control%20Demo.pdf) |              |                        | [8232 RCU Ref](http://wiki.telink-semi.cn/doc/hw/TLSR8232_RCU_TLSR8232RC32D.zip) [8266 Master Dongle](http://wiki.telink-semi.cn/doc/hw/TLSR8266_Dongle_TLSR8266DG32D.zip) |
| BLE OTP            | TLSR8230 |                            |              |                        |                                   |
| 2.4G Keyboard      | TLSR8369 |                            |              |                        |                                   |
| BLE Generic        | TLSR8230 |                            | [SDK V1.1.0](http://wiki.telink-semi.cn/telink_shenzhen/BlackHawk/blackhawk-BLE-SDK.zip)   |                        |                                   |
