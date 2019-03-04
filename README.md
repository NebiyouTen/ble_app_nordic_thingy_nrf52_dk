# Ble App Nordi _thingy Nrf52_dk

This project is developed on Nordic Thingy 52 and NRF52 dk. It allows NRF52 dk to retrive motion data from Nordic Thingy using Bluetooth. The NRF52 dk then displays the recived data using an 8x8 Bi-color LED Matrix. 


- BLE communication between Thingy 52 and NRF52 dk
- TWI/I2C communication between NRF52 dk and the LED matrix. 

## Requirements
- nRF52 SDK version 15.2.0
- nRF52822 DK PCA10040
- Nordic Thingy:52
- 8x8 Bi-Color LED Matrix

This project is adopted from and makes use of the following libraries. 
- The Nordic playground nrf52-ble-app-lbs app, https://github.com/NordicPlayground/nRF52-ble-app-lbs.
- Adafruit Bicolor LED Square Pixel Matrix with I2C Backpack library, https://www.adafruit.com/product/902.
