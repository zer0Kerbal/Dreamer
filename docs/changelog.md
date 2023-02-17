---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
# layout: bare
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- hdr-changelog.md v1.0.0.1
Dreamer (DREAM)
created: 13 May 2022
updated: 05 Nov 2022
CC BY-ND 4.0 by zer0Kerbal -->  
# Changelog  
  
| modName    | Dreamer (DREAM)                                                   |
| ---------- | ----------------------------------------------------------------- |
| license    | GPL-2.0                                                           |
| author     | artwhaley and zer0Kerbal                                          |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/207306-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/Dreamer)                |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/Dreamer)              |
| spacedock  | (https://spacedock.info/mod/2999)                                 |
| ckan       | Dreamer                                                           |

## Version 1.3.99.1-prerelease - `<Thank you DeadJohn>` edition

* Released
  * 16 Feb 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Summary 1.3.99.1

* bug fixes
* flight and other tweaks
  * thank you [DeadJohn aka jvsperoni](https://github.com/jvsperoni)

### Changes 1.3.99.1

* [drm-cabin-bay]
  * move SkyHawkScienceSystems patching into patch :D
  * comment out several part modules.
  * variant update
* [drm-cabin-nobay]
  * move SkyHawkScienceSystems patching into patch :D
  * comment out several part modules.
  * correct seat count
  * variant update
* [drm-cargo-bay]
  * move SkyHawkScienceSystems patching into patch :D
  * comment out several part modules.
  * correct seat count (0)
* [drm-ccb-eng]
  * comment out several part modules.
* [drm-atlas-inter]
  * comment out several part modules.
  * attachRules = x,x,x,x,1
  * [ModuleDecouple] down to 100 from 600
* [drm-centaur]
  * reduce RW by 50%
  * variant update
* [drm-decoupler]
  * attachRules = x,x,x,x,1
  * [ModuleDecouple] up to 100 from 30
* [drm-nose-nodock]
  * comment out several part modules.
* [drm-tail]
  * part in flux
  * what to do about airbrakes? maybe optional patch to enable/disable?
  * need to recalc drag cubes with/without airbrakes
* [drm-wing-left]
  * comment out several part modules.
* [drm-wing-right]
  * comment out several part modules.
* add [drm-engine-mono]
  * thank you [DeadJohn aka jvsperoni](https://github.com/jvsperoni)

* Issues
  * closes #104 - Dreamer (DREAM) 1.3.99.1-prerelease `<Thank you artwhaley>` editio
  * closes #105 - 1.3.99.1 Additional Tasks
  * closes #108 - [BUG] crew capacity of pods
  * updates #109 - [BUG] engines falling off while shielded by interstage adapter

---

## Version 1.3.99.0-adoption - `<Thank you artwhaley>` edition

* Released
  * 10 Feb 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

* Can now search for `drm` or `dreamer`in the editor search bar to find all Dreamer parts
* ~ 23 otal parts
  * CCB / Centaur stages
  * Dreamer
    * two pods, one with and one without cargo bay

### Archival Releases 1.3.99.0

* Archival Releases
  * [x] 1.3.0.0
  * [x] 1.2.0.0
  * [x] 1.1.0.0
  * [x] 1.0.1.0
  * [x] 1.0.0.0
  * [x] 0.8.0.0
  * [x] 0.2.0.0
  * [x] 0.1.0.0
* closes #97 - 1.2.0.0 - Archival Release
* closes #98 - 1.3.0.0 - Archival Release
* closes #91 - Archival Releases

### Localization 1.3.99.0

* Localization directory and contents
  * Create
    * Localization/
      * <en-us.cfg>
      * [readme.md] v2.1.2.0
      * [quickstart.md] v1.0.1.1
  * updates #10 - Localization - Master
  * closes #11 - Localization - English <en-us.cfg>
  * closes #92 - Create Localization directory and contents

### Documentation 1.3.99.0

* Create
  * readme
  * deploy to:
    * CurseForge Description page 🤬
    * Forum Original Post 🐰
    * SpaceDock Information page 🌮
  * release notes
  * [changelog.md]
  * update /docs/

### GitHub Pages 1.3.99.0

* Create
  * docs/
    * [`_config.yml`]
    * [404.md] v1.0.3.2
    * [Assembly.md] v1.0.0.0
    * [Attribution.md] v1.0.7.1
    * [Disclaimer.md] v1.0.7.1
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [ManualInstallation.md] v1.1.8.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
* closes #8 - Needs a wiki
* closes #89 - Create GitHub Pages

### Legal Mumbo Jumbo 1.3.99.0

* Create
  * license check
  * offline documentation
  * _Legal
    * screenshots and pdfs
    * adoptionLetters
    * communications concerning
  * _Links/
    * link(s) saved
  * docs/LegalMumboJumbo
    * [License.md]
    * FORUM-##.png's
      * public documentation
  * GitHub: :octocat:
    * LICENSE
    * [license].txt
  * CurseForge
  * SpaceDock
  * CKAN

### Part Asset Updates 1.3.99.0

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* closes #93 - Part Asset Updates

### Parts 1.3.99.0

* Update
* Lint
* fix issues (below)
* closes #7 - Cargo
* closes #31 - [Bug]: landing gear fails to exist in game
* closes #44 - drm-container versions
* closes #47 - [Bug]: about to start testing KAS functionality for functionality will post updates on that here. edit: kas functionality is broken, same goes for the tail fin which now attaches at an offset node
* closes #56 - [Request]: patch for HullCameraVDS
* closes #57 - [Request]: patch for ConnectedLivingSpaces (CLS)
* closes #58 - [Request]: patch for MechJeb (MJ)
* closes #60 - [Request]: Maybe the docking nose should be an shielded port instead and not a weird extendable tongue thing?
* closes #61 - [Request]: patch for FireSpitter (FS)
* closes #63 - [drm-container] for Snacks
* closes #64 - [drm-container] for USI-LS
* closes #71 - Clean out duplicate textures/models
* closes #72 - [Bug]: IVA BROKEN
* closes #73 - [Bug]: undocking rear port undocks the port from dreamer
* closes #74 - [Bug]: centar attach node is broken,
* closes #80 - [Bug]: airbrakes that are said to exist in the description of the mod don't appear to exist

### Config 1.3.99.0

* Add localized tags to parts
* Create
  * Dreamer.cfg v1.0.0.0
    * adds localized tags to parts
* closes #94 - Create <Dreamer.cfg>

### License 1.3.99.0

* Update
  * Updated License: GPL-2.0
    * was: WTPFL

### Social Media Presence 1.3.99.0

* Create Social Media Presence
  * Kerbal Space Program forum
    * Create new thread/post in "Add-on Development"
    * title: [1.12.x] Dreamer (DREAM) - 1.3.99.0-adoption - `<Thank you artwhaley>` edition [01 Jan 2022]
    * create release post in new thread/post
      * content (readme.htm)
    * original mod's thread/post
      * post link to new thread/post
  * CurseForge
  * Twitter
  * SpaceDock
  * Reddit post
  * Patreon post

### Marketing 1.3.99.0

* Create
  * HeroLogo.png
* closes #90 - Create HeroLogo.png

### Status 1.3.99.0

* Issues
  * closes #85 - Dreamer (DREAM) 1.3.99.0-adoption `<Thank you artwhaley>` edition
  * closes #88 - 1.1.99.0 Create Social Media Presence
  * closes #87 - 1.1.99.0 Create Documentation
  * closes #86 - 1.1.99.0 Create Legal Mumbo Jumbo
  * closes #5 - Dreamer (DREAM) 1.3.99.0-adoption `<Thank you artwhaley>` edition
  * closes #4 - LegalMumboJumbo
  * closes #3 - Social
  * closes #6 - Repo

---

## Version 1.3.0.0-release `<Archival Release>`

* 21 Nov 2015
* Updated to 1.0.5

* configured to not explode on reentry. Mostly sometimes.

* Issues
  * closes #91 - Archival Releases
  * closes #98 - 1.3.0.0 - Archival Release

---

## Version 1.2.0.0-release `<Archival Release>`

* 29 Nov 2014
* Updated to 1.0.4

* Includes a brand new IVA with completely custom props
* no more Alcor dependency
* fixed a couple of texture mapping issues
* made it a little easier to control in the atmosphere
* It's STILL tough to land, by design

* Please keep feedback coming!
* I'm not actively playing the ship much, at the moment, so you guys are the only way I'll know what needs work!

* Issues
  * updates #91 - Archival Releases
  * closes #97 - 1.2.0.0 - Archival Release

---

### Version 1.1.0.0-release `<Archival Release>`

* 21 Nov 2014
* no changelog provided

---

### Version 1.0.1.0-release `<Archival Release>`

* 17 Nov 2014
* no changelog provided

---

## Version 1.0.0.0-release `<Archival Release>`

* 17 Nov 2014
* no changelog provided

---

### Version 0.8.0.0 - Original Author

* 11 Nov 2014
* no changelog provided

---

### Version 0.2.0.0 - Original Author

* 16 Oct 2014
* no changelog provided

---

### Version 0.1.0.0 - Original Author

* 14 Oct 2014
* no changelog provided

---
