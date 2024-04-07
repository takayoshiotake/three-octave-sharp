# Three Octave \#

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

A 38-key (3-octave + 1) keyboard.

## Layout

**Layer 0**:

📄 [keyboard-layout.png](layout/keyboard-layout.png) (v0.2.0)

![keyboard layout](layout/keyboard-layout.png)

MEMO: When pressed individually and released, it becomes the lower right keys (Esc, 英数 and かな).

**RAW data for Keyboard Layout Editor v0.15:**

📄 [keyboard-layout.rawdata.json](layout/keyboard-layout.rawdata.json)

```json
["MO(2)\n\n\nEsc","Q","W","E","R","T","Y","U","I","O","P","BS"],
[{"w":1.25},"MO(1)\n\n\nTab","A","S","D","F","G","H","J","K","L",{"w":1.75},"MO(4)\n\n\nReturn"],
[{"w":1.75},"Shift","Z","X","C","V","B","N","M","MO(5)",{"w":2.25},"MO(3)"],
[{"x":0.75,"w":1.25},"Ctrl",{"w":1.25},"Cmd\n\n\n英数",{"a":7,"w":6},"6u",{"a":4},"Opt\n\n\nかな","Ctrl"]
```

- 🔗 [Keyboard Layout Editor](http://www.keyboard-layout-editor.com/)

## BOM

WIP

## Schematic and PCB

📄 [Three_Octave_Sharp.kicad_sch](electronics/Three_Octave_Sharp/Three_Octave_Sharp.kicad_sch) (v1.0.0)

📄 [Three_Octave_Sharp.kicad_pcb](electronics/Three_Octave_Sharp/Three_Octave_Sharp.kicad_pcb) (v1.0.1)

![schematic svg](assets/schematic.svg)

![pcb png](assets/pcb.png)

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
