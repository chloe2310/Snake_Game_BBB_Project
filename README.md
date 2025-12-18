Description : 

An embedded Linux project implementing the classic Snake Game on BeagleBone Black, using physical GPIO buttons for control and an SSD1306 OLED display (I2C) for real-time graphics rendering.

Features :

  - Device Tree : I2C device declaration (0x3C) and GPIO pinmux/button mapping
  - Linux Interrupt Request (IRQ): handling button input events
  - Linux GPIO & pinctrl: configuring input pins and using GPIO descriptor-based access
  - GPIO subsystem & Pin Control subsystem: configuring GPIO pins and using GPIO descriptor-based 
