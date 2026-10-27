# Ghidra Processor Module for Hitachi HCD62121

**Status**: Disassembly mostly matches MAME reference, but pcode needs to be fixed and adjusted to be more decompiler-friendly.

Used in various Casio handhelds:
* Calculators (CFX-9850);
* Organizers: Picky Talk / Super Denshi Techou Jr. (JD-xxx), Magic Diary (JD-5000);
* Likely any devices in HD621xx family (e.g. HD62119A03, unconfirmed until one is dumped);

The "C" in HCD is used for [chip-on-board CPUs](https://www.hitachi.co.jp/New/cnews/9812/1217a.html).

## References

* http://martin.poupe.org/casio/
* https://github.com/mamedev/mame/blob/master/src/devices/cpu/hcd62121/hcd62121.cpp
