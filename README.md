## Adafruit Joy FeatherWing PCB

<a href="http://www.adafruit.com/products/3632"><img src="assets/image.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for joy featherwing. Format is EagleCAD schematic and board layout

For more details, check out the product page at
* https://www.adafruit.com/products/3632

### Description

Make a game or robotic controller with this Joy-ful FeatherWing. This FeatherWing has a 2-axis joystick and 5 momentary buttons (4 large and 1 small) so you can turn your feather board into a tiny game controller. This wing communicates with your host microcontroller over I2C so it's easy to use and doesn't take up any of your precious analog or digital pins. There is also an optional interrupt pin that can alert your feather when a button has been pressed or released to free up processor time for other tasks.

This FeatherWing features Adafruit Seesaw technology - a custom programmed little helper microcontroller that takes the two analog inputs from the joystick, and 5 button inputs, and converts it into a pretty I2C interface. This I2C interface means you don't 'lose' any GPIO or analog inputs when using this 'Wing, and it works with any and all Feathers! You can easily stack this with any other FeatherWing because I2C is a shared bus. If you have an I2C address conflict, or you want to connect more than one of these to a Feather, there are two address-select jumpers so you have 4 options of I2C addresses.

There's an optional IRQ (interrupt) line that you can use if you'd like the Wing to let you know when a button has been pressed. Since its optional (and most Feathers are perfectly happy polling the Wing for data) we left a bunch of solder jumpers so you can select what pin has the IRQ on it. Or just leave it disconnected!

We have an Adafruit Seesaw library for Arduino, Python and CircuitPython so you can get started with the Joy FeatherWing in a jiffy.

Comes with one assembled and programmed Wing, and two pieces of 0.1" header. Some soldering is required to attach the headers to the FeatherWing.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
