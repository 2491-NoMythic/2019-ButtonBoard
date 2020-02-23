# 2019-ButtonBoard

Arduino code for operating a custom control board that the driver station will read as a joystick.

We had to go down this road because the cheap controller we were using broke with no time to order another one.

It is pretty easy to wire up switches and arcade buttons to inputs on an Arduino compatable. Several of the boards, such as a Leonardo or Adafruit 32u4 will act as a USB HID controller. See the code for the libraries used.

The real trick is getting all the wires connected. See the images folder for how we dealt with this.
