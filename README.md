# Three Octave \#

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

A 38-key (3-octave + 1) keyboard. Powered by [Vial](https://get.vial.today/) firmware.

## Layout

v0.3.0

**Layer 0**:

![keyboard layout](layout/keyboard-layout.png)

MEMO: I couldn't figure out how to map keys to `fn` on macOS using Vial, so I am using Karabiner-Elements, a macOS app, to modify `right_control` to `fn`.

**Layer 1, 2**: arrows, symbols

![keyboard layout 1](layout/keyboard-layout-1.png)
![keyboard layout 2](layout/keyboard-layout-2.png)

**Layer 3, 4**: nums, symbols

![keyboard layout 3](layout/keyboard-layout-3.png)
![keyboard layout 4](layout/keyboard-layout-4.png)

**Layer 5**: fn

![keyboard layout 5](layout/keyboard-layout-5.png)

**RAW data for Keyboard Layout Editor v0.15:**

📄 [keyboard-layout.rawdata.json](layout/keyboard-layout.rawdata.json)

```json
[{a:1},"LT 2\nEsc",{a:7},"Q","W","E","R","T","Y","U","I","O","P","Bksp"],
[{a:1,w:1.25},"LT 1\nTab",{a:7},"A","S","D","F","G","H","J","K","L",{a:1,w:1.75},"LT 4\nEnter"],
[{a:7,w:1.75},"LShift","Z","X","C","V","B","N","M","MO(5)",{w:2.25},"MO(3)"],
[{x:0.75,w:1.25},"LCtrl",{a:1,w:1.25},"LGui_T\n英数",{a:7,w:6},"6u",{a:1},"RAlt_T\nかな",{a:7},"RCtrl"],
```

- 🔗 [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/)

## BOM

WIP

## Schematic and PCB

📄 [Three_Octave_Sharp.kicad_sch](electronics/Three_Octave_Sharp/Three_Octave_Sharp.kicad_sch) (v1.0.0)

📄 [Three_Octave_Sharp.kicad_pcb](electronics/Three_Octave_Sharp/Three_Octave_Sharp.kicad_pcb) (v1.0.1)

![schematic svg](assets/schematic.svg)

![pcb png](assets/pcb.png)

### Key-matrix

|    | C0    | C1   | C2    | C3 | C4 | C5 | C6 | C7 | C8 | C9    | C10    | C11 |
|----|-------|------|-------|----|----|----|----|----|----|-------|--------|-----|
| R0 | Esc   | Q    | W     | E  | R  | T  | Y  | U  | I  | O     | P      | BS  |
| R1 | Tab   | A    | S     | D  | F  | G  | H  | J  | K  | L     | Return |     |
| R2 | Shift | Z    | X     | C  | V  | B  | N  | M  | ,  | Shift | Opt    | Fn  | 
| R3 | Ctrl  | Cmd  | Space |    |    |    |    |    |    |       |        |     |

## Mechanics

📄 [Three-Octave-Sharp-Case.FCStd](mechanics/Three-Octave-Sharp-Case.FCStd) (v1.0.3)

## Firmware

### Vial

- Built UF2
    - 📄 [takayoshiotake_three_octave_sharp_vial_20240407.uf2](vial-bin/takayoshiotake_three_octave_sharp_vial_20240407.uf2)
- Code
    - 🔗 <https://github.com/vial-kb/vial-qmk/tree/vial/keyboards/takayoshiotake/three_octave_sharp>
    - 🔗 <https://github.com/vial-kb/vial-qmk/tree/bbaed80505cf4ceaeb51d1e5fe79b23b22acf1a6>

See [vial-porting](vial-porting) for more details.

## License

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/license-CC%20BY--SA%204.0-lightgrey.svg
