
***

# BathHouseOS

## Codename: Taft

BathHouseOS is a small cluster (6 different operating systems) of operating systems, designed to automate and improve the system performance of a bathroom. Internet connection will not be required anything, except for time syncing. is a small, basic, embedded operating system for bathtub, shower, sink, toilet, hair dryer, and urinal automation. Based on TinyOS, and written in nesC and Verilog, BathHouseOS can help you automate some basic tasks of your bathroom. No Internet connection is required for anything, except for optional time syncing.

### Taft codename

Alpha versions to the first non-beta version (and before v2.0) is codenamed Taft. It is named after the US President William Howard Taft, who is famously known for being severely overweight and getting stuck in the White House bathtub, although he did accomplish some good things as president back in 1909 to 1913 that he isn't credited as much for. He wasn't the best, but he was OK.

### Other codenames

I don't have any other codename ideas at the moment.

### BathOS

BathOS is a special lightweight operating system for automating and managing bath tubs.

Features include:

| Feature | Description |
|---|---|
| Flood protection | The typical drain in a bathtub normally can't keep up with the speed that water pours in. Sometimes, people forget, and then you come back to your floor being drowned in 1 inch of water. It is the reason why I made this operating system, I never thought I would gain approval for it, or make the system. Drain protection involves various sensors, which will automatically shut the water off when it reaches a threshold |
| Flood protection: threshold 1 | The first flood protection threshold has sensors 10 centimeters (3.93 inches) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 2 | The second flood protection threshold has sensors 20 centimeters (7.8 inches) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 3 | The third flood protection threshold has sensors 30 centimeters (11.8 inches) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 4 | The fourth flood protection threshold has sensors 40 centimeters (15.74 inches, or 1 foot 3.74 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 5 | The fifth flood protection threshold has sensors 50 centimeters (19.68 inches, or 1 foot 7.68 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 6 | The sixth flood protection threshold has sensors 60 centimeters (23.62 inches, or 1 foot 11.62 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 7 | The seventh flood protection threshold has sensors 70 centimeters (27.55 inches, or 2 foot 4.55 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 8 | The eighth flood protection threshold has sensors 80 centimeters (31.94 inches, or 2 foot 7.94 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 9 | The ninth flood protection threshold has sensors 90 centimeters (35.43 inches, or 2 foot 11.43 inches deep) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Flood protection: threshold 10 | The tenth flood protection threshold has sensors 100 centimeters (39.37 inches, or 3 foot 7.37 inches deep, or 1 meter) deep, and once the water touches all sensors at once, the water will be shut off automatically. |
| Temperature gauge | See separately the temperature of cold water and hot water, along with the combined temperature (default: Celsius, can be switched to Fahrenheit, Rankine, or Kelvin) and a separate meter for the average bath temperature by threshold |
| Hot water gauge | See how much hot water is left, limit how much hot water you use, schedule to complete the filling another time |
| Automatic draining | Automatically drain the water after a certain amount of time (max: 12 hours, or never) |

More thresholds may be added in the future, and sub-thresholds may also be added.

### ThroneOS

ThroneOS is a special lightweight operating system for automating and managing toilets (the porcelaine throne)

Features include:

| Feature | Description |
|---|---|
| Automatic flushing | Turn automatic flushing on and off |
| Flush direction | Change the flushing direction |
| Blender | Optional add-on: Close the lid and turn on the blender, an alternative to the plunger |
| Automatic closing | Puts the toilet seat down after flushing |
| Automatic opening | When sensors detect you are within a few feet of the front, the lid will automatically rise. This feature is optional |000000000000000
| Tank meter | Show how many millileters/gallons/pints/quarts of water are in the toilet tank |

### MaprilOS

MaprilOS (April showers bring May flowers, Mapril is a portmanteau of May and April that I came up with early in my childhood) is a shower operating system. 

| Feature | Description |
|---|---|
| ThoughtPad | Having some shower thoughts? Write them down, and continue your shower, without getting out |
| Hot water gauge | See how much hot water is left, limit how much hot water you use. |
| Temperature gauge | See separately the temperature of cold water and hot water, along with the combined temperature (default: Celsius, can be switched to Fahrenheit, Rankine, or Kelvin) and a separate meter for the average shower temperature by threshold |
| Automatic turnoff | Turn the shower off after a set amount of time |
| AutoOff | Turn the shower off by simply walking out of it, walk over the sensors of the door to de-activate the shower |

### UriOS

UriOS (Urinal Operating System) is a basic operating system for urinals.

Features include:

| Feature | Description |
|---|---|
| Automatic flushing | Turn automatic flushing on and off |
| Flush direction | Change the flushing direction |

### SankOS

SankOS is a basic operating system for sinks. It can be used outside the bathroom as well.

Features include:

| Feature | Description |
|---|---|
| Temperature gauge | See separately the temperature of cold water and hot water, along with the combined temperature (default: Celsius, can be switched to Fahrenheit, Rankine, or Kelvin) and a separate meter for the average washing temperature by threshold |
| Automatic turnoff | Turn the sink off after a set amount of time |
| Soap dispenser | Enable/disable a soap dispenser |
| Towel dispenser | Enable/disable a towel dispenser |

### BathHouse Core

BathHouse Core is an operating system installable on a panel to gain access to all BathHouseOS devices in the bathroom. It is a lightweight, GUI operating system that connects to the other subsystems. It is also written in nesC, and Verilog, and is also based on the TinyOS operating system.

| Feature | Description |
|---|---|
| Full control | Control all BathHouseOS devices in the current room through this one device. |

<!--
### Features:

- [x] Change the brightness/lighting based on the time of day (including but not limited to: brightness level, color, color range, pattern of colors, pattern of brightness, frequency)

- [x] Automatically feed the fish at certain times of the day, also allows for specifying which fish food to place in

- [x] Operate a tiny operating system (estimated system requirements: 4 megabytes of RAM, 64 megabytes disk space)

- [ ] Suggest a feature
!-->

***

**File version:** `1 (2022 Monday, May 9th at 3:03 pm PST)`

***
