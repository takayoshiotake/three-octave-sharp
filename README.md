# Three Octave \#

A 38-key (3-octave + 1) keyboard.

## Layout

**Layer 0**:

📄 [keyboard-layout.png](layout/keyboard-layout.png) (v0.2.0)

![keyboard layout](layout/keyboard-layout.png)

MEMO: When pressed individually and released, it becomes the lower right keys (Esc, 英数 and かな).

**RAW data for Keyboard Layout Editor v0.15:**

📄 [keyboard-layout.rawdata.json](layout/keyboard-layout.rawdata.json)

```json
["Tab","Q","W","E","R","T","Y","U","I","O","P","BS"],
[{"w":1.25},"MO(1)\n\n\nEsc","A","S","D","F","G","H","J","K","L",{"w":1.75},"Return"],
[{"w":1.75},"Shift","Z","X","C","V","B","N","M","MO(2)",{"w":2.25},"MO(3)"],
[{"x":0.75,"w":1.25},"Ctrl",{"w":1.25},"Cmd\n\n\n英数",{"a":7,"w":6},"6u",{"a":4},"Opt\n\n\nかな","Fn"]
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

📄 [Three-Octave-Sharp-Case.FCStd](mechanics/Three-Octave-Sharp-Case.FCStd) (v1.0.1)

## Firmware

### Vial

- Built UF2
    - 📄 [takayoshiotake_three_octave_sharp_vial_20240210.uf2](vial-bin/takayoshiotake_three_octave_sharp_vial_20240210.uf2)

See [vial-porting](vial-porting) for more details.
