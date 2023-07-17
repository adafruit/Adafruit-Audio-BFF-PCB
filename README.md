## Adafruit Audio BFF Add-on for QT Py and Xiao PCB

<a href="http://www.adafruit.com/products/5769"><img src="assets/5769.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit Audio BFF Add-on for QT Py and Xiao. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5769

### Description

Our QT Py boards are a great way to make very small microcontroller projects that pack a ton of power - and now we have a way for you to turn many QT Py boards into powerful audio play projects that are super small!

This BFF comes with a MicroSD card slot that can address up to 64 GB of storage and a I2S 3 Watt amplifier, for high-quality audio playback, that can fit on the back of your miniature dev board. All together uses the SPI port plus 4 GPIO pins for card CS, and I2S data, clock and left-right select.

We call this the Adafruit Audio BFF - a "Best Friend Forever". When you were a kid, you may have learned about the "buddy" system; well, this product is kinda like that! A board that will watch your QT Py's back and give it more capabilities.

This PCB is designed to fit onto the back of any QT Py or Xiao board, it can be soldered into place or use pin and socket headers to make it removable. Onboard is a MAX98357 audio amplifier and picoblade-compatible connector for plugging in a 4 or 8 ohm speaker. We use A1 for the audio data, A2 for wordselect clock, and A3 for bitclock. The SD card connects over the SPI port: MOSI, MISO and SCK plus A0 for card select.

This pinout will work with ESP32 series, nRF52840, and RP2040 chipset boards. It won't work with the ATSAMD21 'original 'QT Py because those pins on the SAMD21 are not I2S capable. However, you could cut and rewire the traces to connect to the I2S pads if desired - personally, we recommend just upgrading to an RP2040 QT Py instead.

We include some header that you can solder to your QT Py. You can also pick up an Itsy Bitsy short female header kit to make it removable but compact, you'll just need to trim down the headers to 7 pins long.

* Comes as an assembled and tested PCB
* For any QT Py or Xiao boards
* Contains a MAX98357 3 Watt audio amplifier pre-configured for 'stereo' mix output and 9 dB gain which will work great for any project.
* Use any micro SD card that supports SPI mode with one CS pin.
* Connect to the speaker output with a picoblade-compatible 2-pin cable. We recommend this 3W 4 ohm speaker
* There are various Arduino / CircuitPython / MicroPython libraries can be used to talk to the SD card and I2S amplifier.

Speaker, microSD memory card, and QT Py are not included.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
