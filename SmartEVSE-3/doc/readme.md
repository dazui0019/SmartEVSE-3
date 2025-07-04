# 设备

## RFID

使用[1-Wire RFID Reader](https://wiki.teltonika-gps.com/view/1-Wire_RFID_Reader)读取rfid卡。

### 接线

- `PIN_SW_IN` --> `1-wire data`

## 屏幕

[ST7565 LCD](https://www.ladyada.net/learn/lcd/st7565.html)

### 接线

- `PIN_LCD_SDO_B3`  --> `LCD_MOSI`
- `PIN_LCD_A0_B2`   --> `LCD_A0`
- `PIN_LCD_CLK`     --> `LCD_SCLK`
- `PIN_LCD_LED`     --> `LCD_LED`
- `PIN_LCD_RST`     --> `LCD_RST`

其中`PIN_LCD_SDO_B3`和`PIN_LCD_A0_B2`, 与按键功能共用。

## RCD

[RCM14-03](https://www.mouser.com/ProductDetail/Western-Automation/RCM14-03?qs=VJzv269c%252BPZrgM5pBx7ngA%3D%3D&srsltid=AfmBOoriL6y8ZDwTIYQ_xZoMsxQp24LKaptW_Wl2EFcMKkG-moNkJejP)

![RCM14-03](/images/WA-DS-015-RCM14-03-Rev-C-3.png)


### 接线

- `PIN_RCM_FAULT` --> `FAULT_OUT`

`FAULT_OUT`触发故障时, 该引脚输出高电平。

## 电流互感器

### 接线
