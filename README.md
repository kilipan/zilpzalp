![zilpzalp](https://github.com/kilipan/zilpzalp/blob/main/img/zilpzalp_photo.jpg?raw=true)

# zilpzalp
A wonky 28-key, column-staggered, unibody-split keyboard made with fantastic FOSS software: [ergogen](https://github.com/ergogen/ergogen) and [KiCad](https://www.kicad.org/).

Three versions are available:
- the version with support for optional hotswap sockets and slightly extended edgecuts to acommodate the extra space required by the socket (in the [pcb](https://github.com/kilipan/zilpzalp/tree/main/pcb) directory)
- the solder-only version with tighter edge cuts (in the [pcb_solder_only](https://github.com/kilipan/zilpzalp/tree/main/pcb_solder_only) directory)
- the cfx version with different spacing, making the zilpzalp almost 1.5 cm smaller horizontally (in the [pcb_cfx_spacing](https://github.com/kilipan/zilpzalp/tree/main/pcb_cfx_spacing) directory)

**Warning:** The solder-only version has not been tested yet!

## BOM
- 1 pcb
- 1 Seeed XIAO RP2040 controller
- 14 sot23 diodes
- (optional: 28 choc hot swap sockets)
- 28 kailh choc low profile switches
- 28 fitting keycaps (pay special attention here when building the cfx version!)

## Firmware
As of now, the only tested-and-confirmed-working firmware is the [QMK firmware](https://github.com/kilipan/qmk-config-zilpzalp) for the Seeed XIAO RP2040 controller.  
There are also untested ZMK and KMK firmwares which will be made available after testing.

## Inspiration
- all the fantastic keyboards, knowledge, and help by [GEIST](https://github.com/GEIGEIGEIST/), [Freya](https://linktr.ee/freya_irl), [Bob](https://github.com/GroooveBob), and the wonderful Clacktales keyboard community
- the [hummingbird](https://github.com/PJE66/hummingbird) keyboard and the [rufous](https://github.com/jcmkk3/trochilidae#rufous) variation
- the [aptmak](https://github.com/apsu/aptmak) keymap

<p align="center">

![zilpzalp](https://github.com/kilipan/zilpzalp/blob/main/img/zilpzalp.png?raw=true)

</p>
