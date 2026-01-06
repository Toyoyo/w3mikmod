# W3MikMod
A Win32 GUI for MikMod designed to run on win32s.

![w3mikmod](/assets/w3mikmod.png)

## Building
To build this, you need the following:
* GNU make or Watcom make
* OpenWatcom (tested on 2.0 beta)

## Prerequistes
* Windows 3.1
* Microsoft Win32s 1.30c (might work in other versions, not tested, compatible comctl32.dll required)
* Also works in any later version, and wine.

## Running
* An optional list of modules can be passed on command line

## w3mikmod.ini settings
* font: font name to use. fixed-width font assumed.
* size: font size
* empty: show empty samples/instruments names in their respective windows
* avewidth: use font average character width instead of max to resize samples/instruments windows
* mixfreq: mix frequency
* playlist: show/don't show playlist
* dmode_interp: set/don't set DMODE_INTERP
* dmode_reverse: set/don't set DMODE_REVERSE
* dmode_surround: set/don't set DMODE_SURROUND
* dmode_16bits: set/don't set DMODE_16BITS
* dmode_hqmixer: set/don't set DMODE_HQMIXER
* dmode_soft_music: set/don't set DMODE_SOFT_MUSIC
* dmode_soft_sndfx: set/don't set DMODE_SOFT_SNDFX
* dmode_stereo: set/don't set DMODE_STEREO
* dmode_float: set/don't set DMODE_FLOAT
