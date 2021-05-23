## OLED

- 7pin SPI引脚，正面看，从左到右依次为GND、VCC、D0、D1、RES、DC、CS
```
    3V      ---  VCC
    G       ---  GND
    D7      ---  D1
    D5      ---  D0
    D2orD8  ---  CS
    D1      ---  DC
    RST     ---  RES
 ```

 - 4pin IIC引脚，正面看，从左到右依次为GND、VCC、SCL、SDA
 ```
    3.3V        ---  VCC
    G (GND)     ---  GND
    D1(GPIO5)   ---  SCL
    D2(GPIO4)   ---  SDA
```