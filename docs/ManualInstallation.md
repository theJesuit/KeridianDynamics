---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
# layout: bare
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.7.0
Keridian Dynamics (KDVA)
created: 01 Oct 2019
updated: 18 Apr 2022 -->

<!-- based upon work by Lisias -->

# Keridian Dynamics (KDVA)

[Home](./index.md)

Parts pack for resource-conversion and vessel-assembly for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `KeridianDynamics` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KeridianDynamics`
* Extract the package's `KeridianDynamics/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/KeridianDynamics` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/KeridianDynamics`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**, including any other fork:
  * Delete `<KSP_ROOT>/GameData/KeridianDynamics`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/KeridianDynamics`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [KeridianDynamics]
      + [Agencies]
        ...
      + [Assets]
        ...
      + [Compatibility]
        ...
      + [Contracts]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      + [Patches]
        ...
      + [Resources]
        ...
      + [Spaces]
        ...
      * #.#.#.#.htm
      * changelog.md
      * CC-BY-SA-4.0.txt
      * readme.htm
      * KeridianDynamics.version
    ...
  * KSP.log
  ...
```

### Dependencies

* none