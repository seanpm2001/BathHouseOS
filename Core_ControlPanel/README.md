
***

# BathHouseOS

## Control Panel Core subsystem

### About

The core control panel subsystem is a sub-operating system for BathHouseOS that allows wireless or wired connection and control to other devices running BathHouseOS in the current room. By default, the system does not require an Internet connection (as I want to prevent Internet reliance, and weaken IoT (Internet of Things) as frankly, it is very dystopian, and won't last longer than the company that runs it)

The system features a basic GUI, and lets you control the settings of other BathHouseOS devices, since they typically won't have a screen on them. The hardware required for connecting the devices to each other has not been created yet. The control panel subsystem is written in nesC and Verilog, and uses the TinyOS operating system kernel.

It controls the following systems:

[BathOS](BathOS/) - For bathtubs

[ThroneOS](ThroneOS/) - For toilets

[MaprilOS](MaprilOS/) - For showers

[UriOS](UriOS/) - For urinals

[SankOS](SankOS/) - For sinks (which don't have to be in a bathroom most of the time)

## Home repositories

[Guesthouse repository](https://github.com/seanpm2001/BathHouseOS_Core_ControlPanel/)

This is a guesthouse repository, and not a home repository, as development mainly stays on the main BathHouseOS side. This is just the guesthouse that the project retreats to at times. If you are already in this repository, the link is likely recursive, and will reload the page.

[Home repository](https://github.com/seanpm2001/BathHouseOS/tree/BathHouseOS_Main-dev/Core_ControlPanel/)

This is the home repository. If you are already in this repository, the link is likely recursive, and will reload the page.

***

**File version:** `1 (2022, Tuesday, May 10th at 7:37 pm PST)`

***
