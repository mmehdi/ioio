Fix for IOIO-OTG v2.2 board USB Open Accessory on a non-OTG Android > 6.x device

-Added a SoftReset every 3 seconds which enables the IOIO board to connect over Open Accessory USB.
-The blinking LED means IOIO board is looking for connection. Once the connection establised, the LED will turn off.

If you do not wish to compile it, you can download the .ioioapp file from here and flash it using IOIODude.


<h2>Disclaimer</h2>
I am not responsible for any damage this code may cause to your board. I do not own any rights of this proejct. All Credits to [original author](https://github.com/ytai/ioio) of IOIO board.

<img alt="IOIO Logo" src="https://lh6.googleusercontent.com/-NtccMO1M7f4/UDhhwrx26UI/AAAAAAAAjTI/xwTI4Fb8xVQ/s887/ioio-logo.png">
The IOIO is a board that provides a host machine the capability of interfacing with external hardware over a variety of commonly used protocols.
The original IOIO board has been specifically designed to work with Android devices. The newer IOIO-OTG ("on the go") boards work with both Android devices and PC's (details [here](http://ytai-mer.blogspot.com/2012/05/second-generation-of-ioio-is-in-works.html)).
The IOIO board can be connected to its host over USB or Bluetooth, and provides a high-level Java API on the host side for using its I/O functions as if they were an integral part of the client.

All user documentation is on [the Wiki](https://github.com/ytai/ioio/wiki).

You can get answers to questions and get news about IOIO on the [ioio-users discussion group](https://groups.google.com/d/forum/ioio-users).

The [IOIO Gallery](http://pinterest.com/ytaibt/ioio/) lists various IOIO projects to give you some ideas of what you can do with IOIO.

And this is [the blog of Ytai](http://ytai-mer.blogspot.com), the inventor of IOIO, where new developments are normally announced. Specifically, [this introductory post](http://ytai-mer.blogspot.com/2011/04/meet-ioio-io-for-android.html) provides a good overview of this technology.

You can purchase a IOIO-OTG board online from:
- [SeeedStudio](http://www.seeedstudio.com/depot/ioio-otg-for-android-p-1615.html) (**primary manufacturer** - manufacturing, testing and service standards have been inspected).
- [Sparkfun Electronics](https://www.sparkfun.com/products/12633) (**primary manufacturer** - manufacturing, testing and service standards have been inspected).
- [Jaycon Systems](http://www.jayconsystems.com/ioio-otg.html).
- [LinkSprite](http://linksprite.com/wiki/index.php5?title=IOIO-OTG).
- [CuteDigi](http://www.cutedigi.com/development-tools/pic/ioio-otg-for-android.html).
- [AliExpress](http://www.aliexpress.com/store/product/Free-Shipping-IOIO-OTG/600038_781363573.html).

