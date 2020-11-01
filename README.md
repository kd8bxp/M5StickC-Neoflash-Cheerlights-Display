# M5StickC NeoFlash Hat Cheerlights Display

This is a conversion of a old display I did with a ESP8266 (D1 mini), a bit has changed since the original sketch.  
I wanted to use the M5StickC since I have plenty of them, which is ESP32 based.  
I then decided to use the NeoFlash Hat since I wasn't using it for anything else.  
So ESP8266 code needed changed, but the biggest change was the use of Cheerlights MQTT broker, and changing from Adafruit Neopixel Library (Which causes random pixel problems) to using FastLED library.  
The requirements are pretty small.  

Requirements:  
Install the ESP32 board core for Arduino https://github.com/espressif/arduino-esp32  
Install PubSubClient library by knolleary from the library manager or https://github.com/knolleary/pubsubclient  
Install FastLED library https://github.com/FastLED/FastLED  

You need a M5StickC and a Neoflash Hat from M5Stack (Thou this should work on other
ESP32 devices and with standard neopixels as well).  
https://m5stack.com/collections/all/products/m5stickc-neofalsh-hat  
https://m5stack.com/collections/m5-core/products/stick-c  

Usage should be pretty straight forward, set your routers ssid and password.  

## Libraries

Because the Arduino IDE has been getting pretty bad handling libraries, I've included the libraries used in the src directory of the sketch. These libraries may have been slightly modified to work from the sketch directory, and do not include the examples.  

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Support Me

If you find this or any of my projects useful or enjoyable please support me.  
Anything I do get goes to buy more parts and make more/better projects.  
https://www.patreon.com/kd8bxp  
https://ko-fi.com/lfmiller  
https://www.paypal.me/KD8BXP  

## Other Projects

https://www.youtube.com/channel/UCP6Vh4hfyJF288MTaRAF36w  
https://kd8bxp.blogspot.com/  


## Credits

Copyright (c) 2019 LeRoy Miller

## License

This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses>
