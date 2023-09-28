# ghidra-omniwave
Samsung Omniwave CPU (KS0164) arch for Ghidra

Implemented based on the CPU core from MAME ([source](https://github.com/mamedev/mame/blob/master/src/devices/cpu/ks0164/ks0164.cpp)). The CPU itself does not have public datasheets so the instruction set was worked out through reverse engineering, so there is no guarantee that all opcodes are correct or all flags are implemented properly.

This is my first attempt at a CPU architecture in Ghidra so there may be issues with the code still.
