![zilpzalp](https://github.com/kilipan/zilpzalp/blob/main/img/zilpzalp_photo.jpg?raw=true)

# zilpzalp
A wonky 28-key, column-staggered, unibody-split keyboard made with fantastic FOSS software: [ergogen](https://github.com/ergogen/ergogen) and [KiCad](https://www.kicad.org/).

For buying ready-to-assemble kits, consider [keeb.supply](https://keeb.supply/products/zilpzalp)! They share part of the profits made by selling zilpzalp with me!

Four versions for choc switches are available:
- the choc version with support for optional hotswap sockets and slightly extended edgecuts to acommodate the extra space required by the socket (in the [pcb](https://github.com/kilipan/zilpzalp/tree/main/pcb) directory)
- the cfx version with different spacing, making the zilpzalp almost 1.5 cm smaller horizontally (in the [pcb_cfx_spacing](https://github.com/kilipan/zilpzalp/tree/main/pcb_cfx_spacing) directory)
- the default-spacing solder-only version with tighter edge cuts (in the [pcb_solder_only](https://github.com/kilipan/zilpzalp/tree/main/pcb_solder_only) directory)
- the minimal-choc-spacing solder-only version with the tightest spacing that choc V1 switches allow for (in the [pcb_minimal_choc](https://github.com/kilipan/zilpzalp/tree/main/pcb_minimal_choc) directory)  
  **Note:** You will have to procure minimal-spacing keycaps. I am not aware of any commercial solution. Recommendation: [Philadelphia Minimalist](https://github.com/pseudoku/PseudoMakeMeKeyCapProfiles/blob/master/Philadelphia_Minimalist.scad) by [Pseudoku](https://github.com/pseudoku)

One version for MX, KS-27, and KS-33 switches is available:
- this version has default MX-spacing and features a hybrid switch-footprint for hotswap-only MX and solder-only KS-27/33 (in the [pcb_mx_spacing](https://github.com/kilipan/zilpzalp/tree/main/pcb_mx_spacing) directory)


**Warning:** The solder-only default choc-spacing version has not been tested yet!

Some example keymaps for getting an idea of how zilpzalp may be used can be found in the [`example_keymaps` directory](https://github.com/kilipan/zilpzalp/tree/main/example_keymaps).

## BOM
- 1 pcb
- 1 Seeed XIAO compatible controller, like e.g. [Miao](https://github.com/kilipan/miao)
- 14 sot23 diodes (common cathode)
- optional (for hot swap versions only): 28 hot swap sockets  
  (choc or mx depending on pcb version)
- 28 kailh choc low profile switches
- 28 fitting keycaps (pay special attention here when building the cfx or minimal-spacing version!)

## Firmware
I personally use and recommend [ZMK firmware](https://github.com/kilipan/zmk-config-zilpzalp) which is tested and confirmed-functional for the Seeed XIAO RP2040 and the Seeed XIAO BLE controllers.  
Check out [FAK firmware](https://github.com/semickolon/fak) if you're planning to use the Miao!  
[QMK firmware](https://github.com/kilipan/qmk-config-zilpzalp) for the Seeed XIAO RP2040 is also available.

## Inspiration
- all the fantastic keyboards, knowledge, and help by [GEIST](https://github.com/GEIGEIGEIST/), [Freya](https://linktr.ee/freya_irl), [Bob](https://github.com/GroooveBob), and the wonderful Clacktales keyboard community
- the [hummingbird](https://github.com/PJE66/hummingbird) keyboard and the [rufous](https://github.com/jcmkk3/trochilidae#rufous) variation
- the [aptmak](https://github.com/apsu/aptmak) keymap

<p align="center">

![zilpzalp](https://github.com/kilipan/zilpzalp/blob/main/img/zilpzalp.png?raw=true)

</p>
