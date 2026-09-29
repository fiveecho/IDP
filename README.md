# Part IB Integrated Design Project (IDP)

As part of Cambridge Engineering's Part IB Integrated Design Project, I worked with a team to design, build, and program an autonomous robot (running on a Raspberry Pi Pico, MicroPython) that follows a marked line, detects and picks up reels, identifies them by resistance value, and sorts them into the correct loading bay.

Code I was primarily responsible for, in `/sw`:
- `circuit.py`, `motor.py`, `grabber.py` — low-level hardware interfaces
- `line.py`, `test_linelogic.py` — line-following logic and its tests
- `reel_sensor.py`, `reellogictest.py`, `test_vl53l0x.py` — reel detection and resistance-based
  classification
- `pushbutton_logic.py` — start-button interrupt handling
- `main.py` — overall control flow

I also debugged and simplified `turning_tracker.py` and `start_box.py`, collaborating with a teammate.

## License and copyright

All material is copyright of the original author (see the git commit).

Some material is redistributed under licenses from the original codebase,
please refer to the licenses associated with, for example, special
libraries.

All text is made available under the Creative Commons
Attribution-ShareAlike 4.0 International Public License
(https://creativecommons.org/licenses/by-sa/4.0/legalcode).

All computer code is released under the MIT license.

The MIT License (MIT)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
