# Blender Halo Tools

A project that aimed to provide comprehenisve blam engine support too blender.

This project and all of its functionality is now superceeded by [Halo-Asset-Blender-Development-Toolset](https://github.com/General-101/Halo-Asset-Blender-Development-Toolset), please use that rather than these tools.

## Features

### JMS Exporter
Halo CE exporter comparison

|                     | Blender Halo Tools | BlueStreak | Blitzkrieg | Chimp |
|---------------------|--------------------|------------|------------|-------|
| Models              |  ✓                 |  ✓         |  ✓         |  ✓    |
| Texture Coordinates |  ✓                 |  ✓         |  ✓         |  ✓    |
| Vertex Normals      |  ✓                 |  ✓         |  ✓         |  ✓    |
| Nodes               |  ✗                 |  ✓         |  ✓         |  ✗    |
| Biped Systems       |  ✗                 |  ✓         |  ✓         |  ✗    |
| Multiple Regions    |  ✓                 |  ✗         |  ✓         |  ✗    |
| Vertex Weights      |  ✗                 |  ✓         |  ✓         |  ✗    |

#### Usage
Model layout:
```
- Frame
    |-Terrain
    |-Sky
    |-...
    |-Sub Collection
        |-more stuff here
        |-...
```
The frame should be a collection called Frame though the name of this can be changed in your scene properties. All sub collection in frame will also be included.

## Credits
* zekilk (cyboryxmen) - Original blender jms exporter.
* The Spartan - For creating the Halo 2 (.ass) exporter BLEND2HALO2.
* MosesOfEgypt - Moses Editing Kit and jms file format information.
