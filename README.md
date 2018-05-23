# JLINK-ARM-OB
STM32 ICE

![alt text](https://github.com/GCY/JLINK-ARM-OB/blob/master/J-Link%20Commander.png?raw=true)


JLink hack reference (cht): https://www.amobbs.com/thread-5653964-1-1.html

***

**Cook a potato:**


```arm-none-eabi-objcopy -I ihex --output-target=binary firmware.hex firmware.bin```

```python stm32loader.py -p /dev/ttyUSB0  -e -w -v firmware.bin```
