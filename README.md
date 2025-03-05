# Portfolio
A collection of my projects

### Teensy4.1 QSPI MRAM Upgrade

**Repos:** [Teensy4.1-QSPI-MRAM](https://github.com/Michael2MacDonald/Teensy4.1-QSPI-MRAM) & [teensy4_core_extmem_improvments](https://github.com/Michael2MacDonald/teensy4_core_extmem_improvments)

**Tags/Topics:** PSRAM/Flash, MRAM/FRAM, QSPI Memory Interface, Reverse Engineering, MCU & Memory Documentation

**Tl;Dr:** I soldered an MRAM chip to the PSRAM/Flash expansion pads on the Teensy 4.1 MCU development board. Utilizing the MCU documentation and the MRAM chip documentation, I reverse-engineered and then modified the Teensy 4.1 Arduino Core Library, altering the QSPI memory interface opcodes and command sequences to enable memory-mapped access to the MRAM chip for fast and non-volatile data and code storage with nearly unlimited write endurance. After I had the MRAM chip successfully working I created a new fork of the Core Library, adding a mechanism to select either PSRAM/Flash or MRAM support for each memory chip slot depending on the user's hardware setup.



