## Preparation
- Reflow PPU2 with fresh solder, *make sure none bridges*
- Pre-tin both sides of the FPC at a lower temp
- Scrape the vias marked as CLT0-2, next to the S-CPU, in the image bellow
- Then add a blob of solder on each

![ctl](/Users/dudu/Projects/digiretro-hd-docs/ctl.jpg)

## Pins Lifiting

Carefully lift the following pins on PPU2 and PPU1

- PPU2: 93,92,91,90 and 58,57,56,55,54,53,52,51
- PPU1: 94

![instructions](/Users/dudu/Projects/digiretro-hd-docs/instructions.jpg)

## Audio

- Scrape blue coating off the three vias (DAT, WS, BCK)
- Add blob of solder on top of each scrapped via
- Connect one wire on each as well as on the one marked as AGND bellow

![dsp](/Users/dudu/Projects/digiretro-hd-docs/dsp.jpg)

## FPC Installation

- Place the FPC on top of the PPU2 while inserting the pads under the lifted pins
- Tack a few pins to stabilize
- Push down the lifted pins one by one, making sure they remain aligned *before* soldering them
- Once you checked they are properly aligned, solder all the pins

## Wiring

- Wire the CTL vias on the motherboard to the corresponding pads to the FPC
- Solder the audio wires from the DSP to the corresponding pads to the FPC
- Wire the 5V and GND pads on DigiRetro's main board to the voltage regulator output and ground legs

## Wrapping Up

- Connect the 32p FFC from the FPC to the main board.
- Connect a HDMI cable into the main board.
