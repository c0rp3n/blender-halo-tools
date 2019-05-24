# Blender Halo Tools

A project that aims to provide comprehenisve blam engine support too blender.

_This project is not yet feature complete or stable so current features and or the usage of tihs addon may change, thus is it not recommended for general use as of yet until a stable version is released._

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
    |-.....
    |-Sub Collection
        |-more stuff here
        |-....
```
The frame should be a collection called Frame though the name of this can be changed in your scene properties. All sub collection in frame will also be included.

## Credits
* zekilk (cyboryxmen) - Original blender jms exporter.
* The Spartan - For creating the Halo 2 (.ass) exporter BLEND2HALO2.
* MosesOfEgypt - Moses Editing Kit and jms file format information.
