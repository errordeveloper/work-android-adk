**_This repository does not contain any useful code at the moment_**

## Notes

- Reference code from `git://android.git.kernel.org/device/`
   * _modules/device-google-accessory-arduino:_
   * _modules/device-google-accessory-demokit:_
   * _modules/device-sample:_<br>
   Keep future for reference
   * _modules/device-common:_<br>
   Keep future for reference

- Lightweight USB for AVR:
   * _modules/lufa-lib:_<br>
  This repo was cloned from a github mirror, there is an official LUFA repo
  [in Google Code SVN](http://lufa-lib.googlecode.com/svn)

  There is a [thread](http://groups.google.com/group/lufa-support/browse_thread/thread/6276262ccfa59c6a)
  which dicussed the issues of using LUFA with Android ADK, and the code under<br>
  `modules/lufa-lib/trunk/Demos/Host/Incomplete/AndroidAccessoryHost` does
  already implement the ADK protocol.

## Various Alternatives

[V-USB](http://www.obdev.at/products/vusb/index.html) may be considered as
an alternative to LUFA, on AVR devices which do not have a dedicated USB port.

![Circuit Wiring for V-USB using ATtiny2313](http://www.obdev.at/Images/vusb/circuit-zoomed.gif)

Also, the [AVR USB Modem](http://avrusbmodem.googlecode.com/svn/trunk) project has
achieved some integration of Contiki with LUFA stack.
