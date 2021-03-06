rpihacks
========

This repository contains code and config files to go along with the Raspberry Pi Hacks book.

== Software Copies ==

For convenience purposes, we have copied some upstream projects into this repository.

=== raspberry-gpio-python ===<BR>
Python library for GPIO access on a Raspberry Pi<BR>
http://code.google.com/p/raspberry-gpio-python/<BR>
License: MIT

=== matrix_keypad-1.0.4-fixed ===<BR>
Python module for interfacing with the Matrix numeric keypads.<BR>
https://pypi.python.org/pypi/matrix_keypad<BR>
License: GPLv3+

Note: This code has been modified in order to make it work properly, the 
original code did not work at all. Any copyrightable changes are under the
GPLv3+ license (same license as original work).

=== Adafruit_CharLCDPlate === <BR>
Python module for interfacing with the Pi LCD Plate.<BR>
https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code<BR>
License: BSD

Note: We have added an additional file into this directory 
(LCD-pi-plate-print-ip-addrs.py) for one of the hacks in our book.
It is derived loosely from LCDtest.py, but is licensed under MIT.

=== Adafruit_DHTDriver === <BR>
C code for reading the temperature and humidity from the DHT11/22 chips
via the BCM2835 GPIO.<BR>
https://github.com/adafruit/Adafruit-Raspberry-Pi-Python-Code<BR>
License: BSD<BR>

Note: This copy is unmodified, and included here solely for convenience.

=== nxt === <BR>
Bindings to connect the NXT Mindstorms to ROS, with added support for
groovy and Raspberry Pi (Raspbian).<BR>
https://github.com/maxsieber<BR>
License: BSD <BR>

Note: This copy has some fixes for the rviz plugin to build properly.
# Tom forked it here: https://github.com/spotrh/nxt

== Licenses ==

=== CODE ===

Unless otherwise stated, all code files in this repository are under the terms of the following license (MIT):

Copyright (c) 2012 Tom Callaway & Ruth Suehle

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

=== CONTENT ===

Unless otherwise stated, all non-code files (e.g. config files, images, whatever) in this repository are under the 
terms of the Creative Commons Attribution License 3.0 (Unported). A copy of this license can be found here:

http://creativecommons.org/licenses/by/3.0/

For attribution, Ruth and Tom would prefer the following phrasing to be placed in an appropriate place:

"This content was originally created by Tom Callaway and Ruth Suehle for the Raspberry Pi Hacks book, and may be used 
under the terms of the Creative Commons Attribution License 3.0 (Unported): http://creativecommons.org/licenses/by/3.0/"
