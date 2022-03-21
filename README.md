# NppHorizontalRuler-DARK-x64-en-US

## ENG version by `roryap`

* 64-bit English language version of NppHorizontalRuler
* I converted the NppHorizontalRuler plugin discussed here:
https://pixelatedbigfoot.wordpress.com/2019/05/14/notepad-horizontal-ruler-plugin/
* I don't know C++ at all, so excuse any horible code changes I made.  I just "got it to work" and that's it.

## rsebestik addition:

* I took 64b english version from `roryap` and adjusted it for better usage in dark theme
* I also don't know C++ at all, I was able to add simple colors configuration from plugin menu.
* I just "got it to work" and that's it. Download `x64\Unicode Realeas\NppHorizontalRulerDark.dll` or build it by yourself.
* Note that this configuration is primitive, no color picker, no validation, and it must be in format `0xRRGGBB` with `0x` hexa prefix, 
because I tried a lot, but joining 2 `TCHAR*` strings in code was tooo much for me :D, c++ is so strange language...