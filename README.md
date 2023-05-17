![zilpzalp](https://github.com/kilipan/zilpzalp/blob/main/img/zilpzalp_photo.jpg?raw=true)

# zilpzalp
A wonky 28-key, column-staggered, unibody-split keyboard made with fantastic FOSS software: [ergogen](https://github.com/ergogen/ergogen) and [KiCad](https://www.kicad.org/).

Four versions are available:
- the version with support for optional hotswap sockets and slightly extended edgecuts to acommodate the extra space required by the socket (in the [pcb](https://github.com/kilipan/zilpzalp/tree/main/pcb) directory)
- the cfx version with different spacing, making the zilpzalp almost 1.5 cm smaller horizontally (in the [pcb_cfx_spacing](https://github.com/kilipan/zilpzalp/tree/main/pcb_cfx_spacing) directory)
- the default-spacing solder-only version with tighter edge cuts (in the [pcb_solder_only](https://github.com/kilipan/zilpzalp/tree/main/pcb_solder_only) directory)
- the minimal-choc-spacing solder-only version with the tightest spacing that choc V1 switches allow for (in the [pcb_minimal_choc](https://github.com/kilipan/zilpzalp/tree/main/pcb_minimal_choc) directory)  
  **Note:** You will have to procure minimal-spacing keycaps. I am not aware of any commercial solution. Recommendation: [Philadelphia Minimalist](https://github.com/pseudoku/PseudoMakeMeKeyCapProfiles/blob/master/Philadelphia_Minimalist.scad) by [Pseudoku](https://github.com/pseudoku)

**Warning:** The solder-only versions (both default and minimal-spacing) have not been tested yet!

Some example keymaps for getting an idea of how zilpzalp may be used can be found in the [`example_keymaps` directory](https://github.com/kilipan/zilpzalp/tree/main/example_keymaps).

## BOM
- 1 pcb
- 1 Seeed XIAO RP2040 controller
- 14 sot23 diodes (common cathode)
- (optional, for hot swap versions only: 28 choc hot swap sockets)
- 28 kailh choc low profile switches
- 28 fitting keycaps (pay special attention here when building the cfx or minimal-spacing version!)

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
