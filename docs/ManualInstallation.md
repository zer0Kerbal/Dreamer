---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Dreamer (DREAM)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Dreamer (DREAM) by Axial Aerospace

[Home](./index.md)

A roughly 2/3 scale model of Kierra Kevada Corp's Dream Kaser vertical launch spaceplane with cargo bay and docking nosecone!

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `AxialAeroSpace` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/AxialAeroSpace/Dreamer`
* Extract the package's `AxialAeroSpace` folder into your KSP's as follows:
  * `<PACKAGE>/AxialAeroSpace` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/AxialAeroSpace/Dreamer`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/AxialAeroSpace/Dreamer`
* Extract the package's `GameData/` folder into your KSP's as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/AxialAeroSpace/Dreamer`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [AxialAeroSpace]
      + [AxialAeroSpaceLtd]
        + [Agencies]
          ...
        + [Config]
          ...
        + [Flags]
          ...
        + [Localization]
          ...
        ...
      + [Dreamer]
        + [Compatibility]
          ...
        + [Config]
          ...
        + [Contracts]
          ...
        + [Localization]
          ...
        + [Parts]
          ...
        * #.#.#.#.htm
        * Attributions.htm
        * changelog.md
        * Dreamer.version
        * GPL-3.0.txt
          ManualInstallation.htm
        * readme.htm
        ...
      ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [AxialAeroSpaceLtd (AA/L)][AAL]

[AAL]: https://github.com/zer0Kerbal/AxialAerospaceLtd "AxialAerospace Ltd (AA/L)"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
