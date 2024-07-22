## Adafruit QT Py CH32V203 Dev Board with STEMMA QT PCB

<a href="http://www.adafruit.com/products/5996"><img src="assets/5996.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit QT Py CH32V203 Dev Board with STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5996

### Description

What a cutie pie! Or is it... a QT Py? This diminutive dev board features the powerful CH32V203 low-cost processor that's all the trend: based on RISC-V and cheaper than an 8-bit core! This little one is a great way to get started in the CH32x processor family, with everything you need to build many USB-based projects at an excellent price. 

The CH32V203G6 has a single 32-bit RISC-V core, running up to 144MHz, with 1-cycle multiply/divide. Inside is 10KB SRAM, 32KB single-cycle Flash as well as an additional 'external XIP' 224KB of Flash that can be used for program or data storage but  is not as fast as the 32KB. There's also extras you expect: ADC, timers, USB device, UART, I2C and SPI. 

However, please note that the CH32 series is not supported nearly-as-well as ATmega, ESP32, ATSAMD, STM32, or RP2040 chips that have a strong company-led development community. WCH is very "its a low cost chip, you figure it out" kind of company, and while there is some community-led development it is still best used by folks comfortable with having to use Makefiles, clone git repositories, edit configuration files, etc. It definitely does not run CircuitPython or Micropython, and Arduino support is very early. It's definitely not good for beginners! 

If you're interested in playing with the CH32V203, we've wrapped it up in a QT Py format. The pinout and shape is Seeed Xiao compatible, with castellated pads so you can solder it flat to a PCB. It comes with our favorite connector - the STEMMA QT, a chainable I2C port that can be used with any of our STEMMA QT sensors and accessories. We also added an RGB NeoPixel and both a reset button and 'bootloader enter' button that allows you to upload code over USB without a WCH LINKE or similar SWD programmer.

* Same size, form-factor, and pin-out as Seeed Xiao
* USB Type C connector - If you have only Micro B cables, this adapter will come in handy!
* CH32V203G8 RISC-V microcontroller core with 3.3V power/logic. Internal 144 MHz oscillator.
* Native USB Device - We do have USB CDC support via TinyUSB but its pretty chunky upload can also be done via USB
* Built in RGB NeoPixel LED
* 10 GPIO pins:
	* ADC input on all GPIOs
	* I2C port with STEMMA QT plug-n-play connector
	* Hardware UART
	* Hardware SPI
* 3.3V regulator with 600mA peak output
* Reset switch and bootloader switch for starting your project code over or entering USB ROM bootloader mode
* SWD data/clock pads on the bottom for advanced debugging usage
* Really really small

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
