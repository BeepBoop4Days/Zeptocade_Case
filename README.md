# Zeptocade_Case
## Description
A Case for the [Zeptocore](https://zeptocore.com/) [Zeptocade](https://zeptocore.com/#zeptocade) by [Infinite Digits](https://infinitedigits.co/wares/)

Zeptocade is an oversized drum break machine, and just a ton of fun! I found the headphone jack to be cramped and tough to access, so in designing a panel to mount some jacks on, I ended up going all the way around. 

## Bom
- slim right angle TRS (stereo) cable, I used https://a.co/d/58kyzSU
- 2x 3.5mm switched TS (mono) jacks, https://www.taydaelectronics.com/pj-3001f-3-5-mm-mono-phone-jack.html
- 1x 3.5mm TRS (stereo) jack, https://www.taydaelectronics.com/hardware/3-5mm-plugs-jacks/3-5mm-stereo-enclosed-socket.html

## 3D Printing Notes
Designed to be printed with a < or equal to 0.6mm nozzle, FDM. 
Available as a complete model for those with huge beds, or as self supporting pairs (top+bottom and left+right).
- Inner brim recommended
- I didn't do this, but recommend pausing the build where one body supports the next and applying a little masking tape to the model to act as a profylactic layer.
  - My prints seperated fairly cleanly with the help of a blade, but I think they would have popped apart had I used tape.

## Directions
Ultimately I chose route the tip and ring signals to the inputs of the TS (mono) jacks and then from the switches of the mono jack to the TRS (stereo) jack. This means that TRS jack will not receive signal if the TS jacks are in use, and if you enable click track, you can have a floating ring cable (instead of grounding the ring with a TS cable). Minor details that probably don't matter.
- Prep the cable
  - Cut the right angle cable
  - Strip a little wire and tin the ends
  - Use a multimeter to determine which wire is the tip and which is the ring
- Solder the cable either directly to TS jacks or to a protoboard (recommended)
- Solder the TS jacks to the TRS jacks
- Mount the jacks in the 'Top' panel
- Test your work, and then mount the top and left panels using the standoffs that came with the kit
- Mount the bottom and right panels and snap the left bottom and right panels into place
