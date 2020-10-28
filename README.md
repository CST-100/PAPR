# DIY PAPR

*Forked from thethoughtemporium/PAPR*

TO DO:
- build a functioning one first
- organize things
- **120VAC tethering** - allow use of 120V power via a suitably long cord for "tethering" purposes, especially in office/school scenarios where sitting still for a long time in front of others in a closed environment. Would allow the system to operate independently of batteries, or even charge said batteries if applicable. 240 should also be under consideration.

For helmet users:
- Possible HUD using transparent LCDs? Information such as outside air temperature, battery voltage, etc. May not be immediately possible due to the tiny distance between eyes and visor, but worth being looked in to. Another possible solution would be a tiny screen, 7 segment or LCD, at the bottom of the wearer's field of view with such information.
- Audio system, while current one is workable, microphones on left-right may be useful along with small speakers in helmet to either double as headphones or to augment hearing (This is *especially* useful in phone calls and other situations where while to a human, you may be audible, a microphone would struggle to pick you up)
- Onboard camera? Due to political "climate", one may be a good idea. 

### Parts List:
**Original parts:**
*Note: Sizes listed for screws are the maximum that can fit. Using smaller screws is a good idea if you plan to take yours apart frequently or cannot find larger ones. If you have to use US Standard sizes for screws, replace M3 with #4. I'm personally testing #4 screws and will update on whether they work.*
- Voltage regulator: 2x MT3608 
- Fans: 2x 75x75x30mm blower fan
- A 20mm switch and Micro-USB port of some kind, power-only at this time.
- 9 M3x30 self-tapping, flathead screws (or shorter) to hold the top and bottom shells together.
- 20 M3x15 self-tapping, flathead screws (or shorter) to hold the fan-filter connector to the bottom shell.
- 8 M3x7 screws to hold the fan-CPAP connector to the bottom shell. Technically, six of these can be up to 10mm, but on the top-left of each connector, the screw would collide with one of the fan-filter screws.

**Of the 3D printed parts:**
- 1 Bottom Shell
- 1 Top Shell
- 2 "Fans to Filter" 
- 2 "Fan to CPAP connector"
- 2 "90 degree connector"

### What is a PAPR?

A PAPR is a positive air pressure respirator that works by supplying clean air to the user in such a way that more air is supplied than is used so external contaminants don't get in.
They're particulalrly useful in the case of smoke or contagions as all the input air is heavily filtered before being delivierd to the user.

But most are quite expensive so we wanted to design our own!

This repo contains all of the files you need to recreate our design and adapt it to work with many types of commercially availiable filters and helmets. 

V3 is the most up to date and functional version. V4 is still under development.

![PAPRv4](https://github.com/thethoughtemporium/PAPR/blob/main/493507e8-c7e0-45a2-9ea5-cce407912ea4.PNG?raw=true)
