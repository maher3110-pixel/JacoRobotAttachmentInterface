# Jaco Robot Attachment Interface

This repository contains the design files and supporting documentation for the Jaco Robot Attachment Interface project.

## Repository contents

| Folder | Contents |
|---|---|
| [CAD/Fusion360](CAD/Fusion360/) | Native Autodesk Fusion 360 designs, organized by study interfaces and research folders |
| [CAD/STEP](CAD/STEP/) | STEP exports of the two official study interfaces |
| [CAD/STL](CAD/STL/) | STL mesh files for Gripper components |
| [Drawings](Drawings/) | Engineering drawings, dimensions and manufacturing details |
| [Images](Images/) | Renders, assembly views and project photographs |
| [Documentation](Documentation/) | Design notes, instructions and supporting technical documents |

## CAD folder structure

```text
CAD/
├── Fusion360/
│   ├── Official Study Interfaces/   # Two official designs in .f3d format
│   └── Research & Development/       # Design iterations, source models and supporting files
│       ├── Gripper/
│       ├── Holster Designs/
│       ├── Last Year Assets/
│       ├── Online Attachment Models/
│       ├── Palm Designs/
│       └── Tool Designs/
├── STEP/
│   └── Official Study Interfaces/   # The same two official designs in .step format
└── STL/
    └── Research & Development/
        └── Gripper/                 # Five mesh files
```

The two official study interfaces are **Insert & Twist Interface** and **Snap On Interface**. Each is available as a native Fusion 360 file and as a STEP file. The Research & Development folders retain the source project organization; the five Gripper STL assets are stored separately under CAD/STL.

## Getting started

1. Open the relevant folder under `CAD`.
2. Download the file you need.
3. Open `.f3d` files in Autodesk Fusion 360. STEP files can be imported into most mainstream CAD applications. STL files are mesh exports intended primarily for fabrication workflows.

## Existing project document

The repository also includes [Mhky_JacoSmartAttachment.pdf](Mhky_JacoSmartAttachment.pdf).

## File conventions

- Keep native Fusion 360 source files in `CAD/Fusion360/`.
- Keep STEP exchange files in `CAD/STEP/`.
- Keep mesh exports in `CAD/STL/`.
- Preserve the study interface and research subfolder structure when adding new files.

## Licence

A licence has not yet been added. Reuse and redistribution permissions will be specified once the project owner selects an appropriate open-hardware licence.
