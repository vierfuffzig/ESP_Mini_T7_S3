# ESP_GPS Logger by Rp6Conrad
### Fork for the ESP32 S3R8 (no display stuff yet...)

![Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTUtx4nv62XWIkPTiRHOSiNqyi3qSTORdZkLUKNVpO7VA&s=10)

Build environment:

- Arduino IDE **2.0.2**
- esp32 by espressif **2.0.3**
- ArduinoJson by Benoit **6.17.2**
- LittleFs_esp32 by lorol **1.0.5**
- TFT_eSPI by Bodmer **2.4.72** - requires defining display driver in library's User_Setup.h plus defining user setup in User_Setup_Select.h
- in `~\user\AppData\Local\Arduino15\packages\esp32\hardware\esp32\1.0.6\libraries\SD\library.properties` Change `SD(esp32)`to `SD`
