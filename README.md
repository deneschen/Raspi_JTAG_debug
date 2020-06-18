# Raspi3 Raspi4 jtag debug

40-pin gpio connect

gpio22-27 Alternative Function Assignments all are ALT4.

connect following gpio pin to jlink pin.

|管脚名字|gpio功能ALT4|
|------|------|
|GPIO22 | ARM_TRST |
|GPIO23 | ARM_RTCK |
|GPIO24 | ARM_TDO |
|GPIO25 | ARM_TCK |
|GPIO26 | ARM_TDI |
|GPIO27 | ARM_TMS |
|GPIO01 | Vref |
|GPIO09 | GND |

--------------------------------------------
# Download pre-built OpenOCD for Windows
https://gnutoolchains.com/arm-eabi/openocd/