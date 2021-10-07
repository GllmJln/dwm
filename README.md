# Dwm personal configuration
Personal configuration of [dwm](https://dwm.suckless.org/).

## Patches

Includes patches in the `patches` folder.

<div align="center">

| **Patch** | **Description** |
| --- | :--- |
| [barpadding](https://dwm.suckless.org/patches/barpadding/) | Adds padding to the status bar, looks better when using rounded corners |
| [dwmblocks](https://github.com/torrinfail/dwmblocks) | Scriptable, clickable blocks for the status bar |
| [fixborders](https://dwm.suckless.org/patches/alpha/) | Fix the transparency of the border of transparent windows |
| [pertag](https://dwm.suckless.org/patches/pertag/) | Make layouts, master window size and number of masters different on each tag |
| [reorganizetags](https://dwm.suckless.org/patches/reorganizetags/) | Reorganise tags, shift all clients per tag to leftmost unoccupied tags |
| [statusallmons](https://dwm.suckless.org/patches/statusallmons/) | Adds the status bar on all monitors |
| [tagmonall](https://github.com/Thegajout/tagmonall) | Personal patch, allows the transfer of all clients from on monitor to the other |
| [vanitygaps](https://dwm.suckless.org/patches/vanitygaps/) | Adds gaps between clients |

</div>

## Extra customisation

- Different colour theme for status on selecter monitor and other monitor(s).

## `libxft-bgra`

[libxft-bgra](https://aur.archlinux.org/packages/libxft-bgra/) must be installed for proper display of emojis and colour characters in the bar. If it is not installed dwm will crash.

## Bindings

Almost all bindings are default. Gaps resizing has been disabled because I don't use it. \
Bindings not relevant to dwm are set by [sxhkd](https://github.com/baskerville/sxhkd).

## To do
- [ ] Add bindings to documents somewhere
- [ ] Gaps per tag?
- [ ] More colour themes for use in dwmblocks?
