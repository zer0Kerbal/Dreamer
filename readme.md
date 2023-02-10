<!-- readme.md v1.7.0.1
Dreamer (DREAM)
created: 17 Jul 2017
updated: 17 Jan 2023 -->

<!--this file: CC BY-ND 4.0 by zer0Kerbal-->

[![Dreamer (DREAM)][MOD:shd]][forum] [![KSP version][KSP:shd]][KSP:url]  [![License][LIC:shd]][LIC:url]  
[![Curseforge][CURSFG:shd]][CURSFG:url] [![GitHub][GITHUB:shd]][GITHUB:url] [![SpaceDock][SPCDCK:shd]][SPCDCK:url]  
[![CKAN][ckan:shd]][ckan:url] [![Pages][PAGES:shd]][pages]



# Dreamer (DREAM) by [Axial Aerospace][AAL]

A roughly 2/3 scale model of Kierra Kevada Corp's Dream Kaser vertical launch spaceplane with cargo bay and docking nosecone!

## By [`zer0Kerbal`][zer0Kerbal], originally by [`artwhaley`][artwhaley]

adopted with *express* permission and brought to you by *KerbSimpleCo*

<img src="https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/img/HeroLogo_1920x1920.png" alt="Dreamer Hero" width="50%" height="50%">

### See more

>* [ChangeLog][chlog] for more details of changes
>* [Discussions][discu] or [KSP Forums][forum] for discussions and news
>* [GitHub Pages][pages]
>* [Known Issues][issue] for more details of feature requests and known issues
>* [Marketing Slicks][markt]
>* [Parts Catalog][parts] for part pictures

### YouTube review by [`Kottabos Gaming`](https://forum.kerbalspaceprogram.com/index.php?/profile/36583-kottabos/)

[![KSP Mods - Dreamer](https://img.youtube.com/vi/Oj1etoybd7E/0.jpg)](https://youtu.be/Oj1etoybd7E)

[YouTube test/demo I](https://youtu.be/aAUGHN3GlAs)
[YouTube test/demo II](https://youtu.be/fx9IibZhpg4)

[Link to Craft File][craft:0]

### Preable by [artwhaley][artwhaley]

> What's included
>
> * **Two versions of the body** - one that's true to the original, and one that adds a small payload bay. The payload bay is one of a few changes that I've made to the Dream Chaser (all of them optional... you CAN build and set it up to fly true to the prototype if accuracy is your thing.) because I want this to be a mod that people can actually use - rather than being like some of the awesome mods on here that realistically capture every detail of a real world craft... but don't really have any 'playability' - so you launch them once to marvel at the model... then either delete it or let it slow down your game load times forever... but never really PLAY with it. These are game pieces... not museum collectibles.
> * **Two versions of the nose section** - one that just has internal space to attach pieces - batteries, computers, small rcs tanks, etc... and one that adds an Orbiter Delta-Glider style docking port in the nose.
> * **Three payload bay modules** - a generic tank (comes preconfigured for TAC life support, but the idea is that you can edit the .cfg file to add any resource from any mod that YOU use... so reconfigure it for snacks or karbonite or anything else), an LFO tank that adds additional delta-v to the ship, and a KAS workshop module that, if you have KAS installed, gives a winch, a pipe attachment, and a storage crate, turning this into an awesome little maintenance and upgrades platform.
> * **An Atlas V two-stage launcher** to lob the thing into orbit. This is lower detail, as I wanted to spend CPU cycles and memory on the ship you actually fly all mission, not on the launcher you discard in three minutes. But it's there, and both stages terminate at 2.5m so they're useable with other payloads... though you'll probably have to have an adapter fairing of some sort for the upper stage, because the top of the centaur isn't flat.
> * **The other little parts to make it work** - wings, tail, landing skid and wheels, a rear docking port (true to the prototype design) OMS engines and a 2.5m adapter.
> * I've now added integrated airbrakes. They're attached with the tail model, and the tail is where you click to control them. It's possible to reenter and land the ship in both stock and FAR without them... but they make it a LOT less scary.

### What's included besides the basic ship

> * **Three payload bay modules** - a generic tank (comes preconfigured for TAC life support, but the idea is that you can edit the config (.cfg) file to add any resource from any mod that YOU use... so reconfigure it for snacks or karbonite or anything else), an LFO tank that adds additional delta-v to the ship, and a KAS workshop module that, if you have KAS installed, gives a winch, a pipe attachment, and a storage crate, turning this into an awesome little maintenance and upgrades platform.
> * **An Atlas V two-stage launcher** to lob the thing into orbit. This is lower detail, as I wanted to spend CPU cycles and memory on the ship you actually fly all mission, not on the launcher you discard in three minutes. But it's there, and both stages terminate at 2.5m so they're useable with other payloads... though you'll probably have to have an adapter fairing of some sort for the upper stage, because the top of the centaur isn't flat.
<!-- > -->
> * *The launch vehicle adapter is 2.5m*, so you can hypothetically launch it on top of any 2.5m parts from the game... but... there's a lot of aerodynamic surface on this thing, and it's way up front in the launch configuration. The included Atlas V has increased gimbal range to let you counteract the instability instead of fins (just like the real thing) so if you launch this on stock parts, you may need quite a few fins at the base of the rocket.

### Notes by [@artwhaley][artwhaley]

> * The centaur loads with less than full fuel tanks... and the Dreamer loads with more fuel than you probably need. I highly recommend planning your missions and adjusting the fuel in these two stages appropriately.
> * There's an electric generator built into the capsule. And the output is HIGH. I've had to do this to make the batteries last all the way through re-entry. I suppose I could turn the power down on the flywheel system. I'll play with that. But at the moment you'll never run out of electricity. Which is a little hacky. I need to get this into balance.
> * The mod supports DRE and FAR. The Far support should be considered a WIP. Please give feedback. The ship isn't designed to be EASY to fly, but if it's uncontrollable it's probably a bug. In general - space planes are hard to fly... Over the course of development I've bowed to pressure a few times to make this easier to handle during reentry and landing.... but it still isn't stupidly forgiving... I recommend reentering such that a ballistic landing would put you right on the KSP pad, so your lifting surfaces will make for a long overshoot... then out over the water at around 10,000m of altitude you can come back around to point west for landing.
> * **The Atlas V 402 launcher is low detail**, but it exists. I've put the .blend files in the abandoned model thread and you're welcome to start with my cfg files.... so if anyone is looking for a mod project, a day texturing what's already there... a couple of days building fairings and payload adapters, and a day modelling the single nozzle Centaur engine and you'd have a stand-alone Atlas V mod ready to release. :) All I ask is the option to include any improvements you make back into this mod if they fit with it! :) I may move on to this project eventually myself... but I've got a couple of projects ahead of it, so please feel free. I'll gladly help someone along, if it's their first project! :)
>* **Important Note:** This ship draws inspiration from several places, both real world and fictional craft. Any resemblance it bears to specific craft, however, is purely incidental. I've been asked not to use any trademarks belonging to a certain real world company working on a certain real world vertical launch, horizontal recovery shuttle, so let's enjoy this for what it is - a purely fantasy ship with many design features of it's very own.

### Help Wanted

> * Compatibility patches
> * Contracts for these glorious parts
> * Variant Textures
> * Converting from FireSpitter to Stock and/or KSPWheel  
> * Model updates (add/improve lights, iva, hatches and so forth)
> * Marketing Images and Videos such as hero shots, animated gifs, short highlights
> * Translations: See the [README in the Localization folder][lreadme] for instructions for adding or improving translations. There is also the [quickstart guide][qstart]. [GitHub][GitHub:url] push is the best way to contribute. *Additions and corrections welcome!*
> * Have a request? Glad to have them, kindly submit through [GitHub][issue].

### Localization

>* ![English][EN] English
>* ***your translation here***

### Installation Directions [^1]

Use CurseForge/OverWolf Website/App

<a href="https://download.curseforge.com/"><img src="https://www.overwolf.com/brand-guidelines/img/logo2.svg" alt="CurseForge/OverWolf App" height="80px"></a>

or<a href="https://forum.kerbalspaceprogram.com/index.php?/topic/197082-*/"><img src="https://i.postimg.cc/x8XSVg4R/sj507JC.png" alt="CKAN App" height="75px"></a>

I take no part, nor am I interested in maintaining the [CKAN][ckan:url] metadata for my mods. [CKAN][ckan:url] is a great mod for those that can't use zip tools. If you are having issues please let the [CKAN][ckan:url] people know and refer to the [CKAN][ckan:url] thread. My support of [CKAN][ckan:url] extends with checking the checkbox in [SpaceDock][SPCDCK:url]. Beware, [CKAN][ckan:url] *can* really mess up; though it tries very, very, very hard not to.

### Dependencies

* [AxialAerospace Ltd (AA/L)][AAL]
* [Kerbal Space Program][KSP:url] [![Kerbal Space Program][KSP:shd]][KSP:url] [^2]

### Recommends

* by [Axial Aerospace Ltd (AAL)][AAL]
  * [LanderTek (LTEK)][LTEK]
  * [Simple Cargo Solutions (CARGO)][CARGO]
  * [WhimChaser (WHIM)][WHIM]

### Suggests

* [Adjustable Mod Panel (KAMP)][KAMP]
* [Biomatic (BIO)][BIO]
* [Docking Port Descriptions(DPD)][DPD]
* [Drop Tank Wrapper (DROP)][DROP]
* [Field Training Facility (FTF)][FTF]
* [Field Training Lab (FTL)][FTL]
* [GPO (Goo Pumps & Oils') Speed Pump (GPO)][GPO]
* [Inflatable PicoPort (IPP)][IPP]
* [Kaboom! (BOOM)][BOOM] *another way to not go to space today*
* [Kerbal Inventory System][kis]
* [Kerbal Joint Reinforcement][kjr]
* [Lithobrake Exploration Technologies (LET)][LET]
* [On Demand Fuel Cells (ODFC)][ODFC]
* [OScience Laboratories (OSL)][OSL]
* [Papa Kerballini's Pizza (PIZZA)][PIZZA]
* [Portable Science Container (PRC)][PRC]
* [Precise Maneuver (PM)][PM]
* [Shielded PicoPort (SPP)][SPP]
* [SimpleConstruction! (SCON)][SCON]
* [SimpleLogistics! (SLOG)][SLOG]
* [SimpleNotes! (NOTE)][NOTES]
* [Solar Science (SOL)][SOL]
* [Stack Inline Lights - Patches (SILP)][SILP]
* [Stack Inline Lights (SIL)][SIL]
* [Tweakscale (twk)][twk]

### Supports

* [ContractConfigurator][cc]
* [GPO (Goo Pumps & Oils') Speed Pump (GPO)][GPO]
* [Kerbal Joint Reinforcement - Next][kjr]
* [KRASH][krsh]
* [KURS style docking camera (kurs)][kurs]
* [Less Real Than Real(ism)][lrtr] by [Pehvbot](https://forum.kerbalspaceprogram.com/index.php?/profile/182810-*/)
* [NEAR-FAR][far]
* [On Demand Fuel Cells (ODFC)][ODFC]
* [RemoteTech (RT)][rt]
* [SimpleConstruction! (SCON)][SCON]
* [StageRecovery (sr)][sr]
* [TweakScale][twk]
* *either* [^3]
  * [Module Manager /L][mml]
  * [Module Manager][mm]
* One of the following:
  * [Raster Prop Monitor][rpm]  Make the IVA look great!
  * [MOARdV's Avionics Systems][mas]  Make the IVA look great!
* *either*  for fully functioning wheels. may invoke bouts of dizziness.
  * [Firespitter core][fsc]
  * [Firespitter][fs]

### Tags

* career, config, crewed, parts, uncrewed, variants

<div style="border:0.5px solid Tomato; background-color: #BADA55; color: #FF0000; text-align:center">
  <p><b>red box below is a link to forum post on how to get support</b></p>
  <a href="https://forum.kerbalspaceprogram.com/index.php?/topic/83212-*">
    <p><img src="https://i.postimg.cc/vHP6zmrw/image.png" alt="How to get support"></p></a>
  <p style="color: #000000;">Be Kind: Lithobrake, not jakebrake! Keep your Module Manager up to date</p>
</div>

### Credits and Special Thanks

* [artwhaley][artwhaley] for creating this glorious addon!
* see [Attribution][attrb] for more

### Legal Mumbo Jumbo (License *provenance*)

#### Author (1) - [`zer0Kerbal`][zer0Kerbal]

> Forum: [Thread][forum] - Source: [GitHub][GITHUB:url]  
> License: [![License][LIC:shd]][LIC:url] ![License][LIC:log]
>
> ##### Disclaimer(s)
>
> ***All bundled mods are distributed under their own licenses***  
> ***All art assets (textures, models, animations, sounds) are distributed under their own licenses***

##### see [Notices][notic] for more *legal mumbo jumbo*

#### Original (ROOT) (0) - Author: ['artwhaley'][artwhaley]

> Forum: [Thread][MOD:0:thread] - Download: [CurseForge][MOD:0:dnload] - Source: [CurseForge][MOD:0:source]
> License: [![License][LIC:0:shd]][LIC:0:url] ![License][LIC:0:log]

### How to support this and other great mods by [`zer0Kerbal`][zer0Kerbal]

> ***Completely voluntary, absolutely amazing, and really does help me out a lot!***  
> quote from <a href="https://forum.kerbalspaceprogram.com/index.php?/profile/32393-*/"><img src="https://kerbal-forum-uploads.s3.us-west-2.amazonaws.com/monthly_2020_06/kappa-kerbal-anarchy.thumb.png.673a2f6f7b36cc60a35c24efef217246.png" width="25px" height="25px" alt="cybutek" > cybutek</a> creator of <a href="https://forum.kerbalspaceprogram.com/index.php?/topic/17833-130-*/" alt="Kerbal Engineer Redux (KER)"> Kerbal Engineer</a>

[![Support][PAYPAL:img]][PAYPAL:url] [![Github Sponsor][GSPONS:img]][GSPONS:url] [![Patreon][PATREON:img]][PATREON:url] [![Buy zer0Kerbal a snack][BMCC:img]][BMCC:url]

*and it is true.*
<!-- mod links -->
[attrb]: https://zer0kerbal.github.io/Dreamer/Attributions "Attribution"
[chlog]: https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/changelog.md  "Changelog"
[discu]: https://github.com/zer0Kerbal/Dreamer/discussions "Discussions"
[forum]: https://forum.kerbalspaceprogram.com/index.php?/topic/207306-*/ "Dreamer Forum Thread"
[issue]: https://github.com/zer0Kerbal/Dreamer/issues "Issues"
[markt]: https://zer0kerbal.github.io/Dreamer/Marketing "Marketing Slicks"
[notic]: https://zer0kerbal.github.io/Dreamer/Notices "Notices"
[parts]: https://zer0kerbal.github.io/Dreamer/PartsCatalog "Parts Catalog"
[pages]: https://zer0kerbal.github.io/Dreamer "GitHub Pages"

<!--- shields -->
[MOD:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/mod.json
[PAGES:shd]: https://img.shields.io/badge/GitHub-Pages-white?style=plastic&labelColor=9cf&logoColor=181717&logo=github "GitHub IO"

<!--- mod provenance -->

[MOD:0:dnload]: https://www.curseforge.com/kerbal/ksp-mods/dreamer/files "CurseForge"
[MOD:0:source]: https://www.curseforge.com/kerbal/ksp-mods/dreamer/files "CurseForge"
[MOD:0:thread]: https://forum.kerbalspaceprogram.com/index.php?/topic/126208-*/ "KSP Forum"

<!--- license provenance-->
[LIC:0:url]: https://www.gnu.org/licenses/gpl-3.0-standalone.html "GPL-3.0"
[LIC:0:log]: https://i.postimg.cc/9FrwMgK6/GPL-17x17.png "GPL-3.0"
[LIC:0:shd]: https://img.shields.io/badge/License-GPL-3.0-A42E2B?style=plastic&labelColor=white&logoColor=A42E2B&logo=gnu "GPL-3.0"

[LIC:url]: https://www.gnu.org/licenses/gpl-2.0-standalone.html "GPL-2.0"
[LIC:log]: https://i.postimg.cc/9FrwMgK6/GPL-17x17.png "GPL-2.0"
[LIC:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/license.json "GPL-2.0"

<!--- release links -->
[CURSFG:url]: https://www.curseforge.com/kerbal/ksp-mods/Dreamer "Curseforge"
[CURSFG:shd]: https://img.shields.io/badge/CurseForge-Link-CCFF00.svg?labelColor=6441A4&style=plastic&logo=curseforge "Curseforge"

[GITHUB:url]: https://github.com/zer0Kerbal/Dreamer/ "GitHub"
[GITHUB:shd]: https://img.shields.io/badge/Github-Link-CCFF00.svg?labelColor=181717&style=plastic&logo=github "GitHub"

[SPCDCK:url]: http://spacedock.info/mod/2999 "SpaceDock"
[SPCDCK:shd]:  https://img.shields.io/badge/SpaceDock-Link-CCFF00.svg?labelColor=181717&style=plastic&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA1MDAgNTAwIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MDAgNTAwOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+CjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+Cgkuc3Qwe2ZpbGw6IzFBMUExQTt9Cgkuc3Qxe2ZpbGw6IzA1Nzg5Mzt9Cgkuc3Qye2ZpbGw6IzA3QUNEMjt9Cjwvc3R5bGU+CjxwYXRoIGlkPSJYTUxJRF8xXyIgY2xhc3M9InN0MCIgZD0iTTQwMCwwLjZIMTAwYy01NSwwLTEwMCw0NS0xMDAsMTAwVjQwMGMwLDU1LDQ1LDEwMCwxMDAsMTAwaDMwMGM1NSwwLDEwMC00NSwxMDAtMTAwVjEwMC42CglDNTAwLDQ1LjYsNDU1LDAuNiw0MDAsMC42eiIvPgo8ZyBpZD0iWE1MSURfNl8iPgoJPGcgaWQ9IlhNTElEXzlfIj4KCQk8cGF0aCBpZD0iWE1MSURfMTdfIiBjbGFzcz0ic3QxIiBkPSJNMTgzLjMsMTY1LjljNi40LTMuNiwxNi45LTMuNiwyMy4zLDBMNDY3LjQsMzE0YzYuNCwzLjYsNi40LDkuNiwwLDEzLjJMMjA2LjYsNDc0LjQKCQkJYy02LjQsMy42LTE3LjcsNi42LTI1LDYuNmgtNDQuOGMtNy40LDAtOC4xLTMtMS43LTYuNmwyNjEtMTQ3LjJjNi40LTMuNiw2LjQtOS42LDAtMTMuMkwxNzEsMTg2Yy02LjQtMy42LTYuNC05LjYsMC0xMy4yCgkJCUwxODMuMywxNjUuOXoiLz4KCTwvZz4KCTxnIGlkPSJYTUxJRF84XyI+CgkJPHBhdGggaWQ9IlhNTElEXzE2XyIgY2xhc3M9InN0MiIgZD0iTTMxOC44LDE5Yy03LjQsMC0xOC42LDIuOC0yNSw2LjRMMzMsMTczLjRjLTYuNCwzLjYtNi40LDkuNSwwLDEzLjFsMjYwLjcsMTQ3LjEKCQkJYzYuNCwzLjYsMTYuOSwzLjYsMjMuMywwbDEyLjMtN2M2LjQtMy42LDYuNC05LjUsMC0xMy4ybC0yMjUuMS0xMjdjLTYuNC0zLjYtNi40LTkuNSwwLTEzLjJMMzY1LjYsMjUuNGM2LjQtMy42LDUuNi02LjQtMS43LTYuNAoJCQlIMzE4Ljh6Ii8+Cgk8L2c+CjwvZz4KPC9zdmc+Cg==  "SpaceDock"

[CKAN:url]: http://forum.kerbalspaceprogram.com/index.php?/topic/197082-*/ "CKAN"
[CKAN:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/ckan.json "CKAN"

<!-- Kerbal Space Program -->
[KSP:url]: https://kerbalspaceprogram.com/ "Kerbal Space Program"
[KSP:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/ksp.json&logo=data:image/webp;base64,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 "Kerbal Space Program"

<!-- links to add-ons/mods --> 
[BIO]: https://forum.kerbalspaceprogram.com/index.php?/topic/191426-*/ "Biomatic (BIO)"
[BOOM]: https://forum.kerbalspaceprogram.com/index.php?/topic/192938-*/ "Kaboom! (BOOM)"
[DPD]: https://forum.kerbalspaceprogram.com/index.php?/topic/192184-*/ "Docking Port Descriptions"
[FTF]: https://forum.kerbalspaceprogram.com/index.php?/topic/188841-*/ "Field Training Facility (FTF)"
[FTL]: https://forum.kerbalspaceprogram.com/index.php?/topic/188841-*/ "Field Training Lab (FTL)"
[GPO]: https://forum.kerbalspaceprogram.com/index.php?/topic/207732-*/ "GPO SpeedPump (GPO)"
[IPP]: https://forum.kerbalspaceprogram.com/index.php?/topic/208975-*/ "Inflatable PicoPort (IPP)"
[KAMP]: https://forum.kerbalspaceprogram.com/index.php?/topic/207263-*/ "Adjustable Mod Panel (KAMP)"
[NOTES]: https://forum.kerbalspaceprogram.com/index.php?/topic/207118-*/ "SimpleNotes! (NOTES)"
[ODFC]: https://forum.kerbalspaceprogram.com/index.php?/topic/187625-*/ "On Demand Fuel Cells (ODFC)"
[OSL]: https://forum.kerbalspaceprogram.com/index.php?/topic/209490-*/ "OScience Laboratories (OSL)"
[PIZZA]: https://forum.kerbalspaceprogram.com/index.php?/topic/209577-*/ "Papa Kerballini's Pizza (PIZZA)"
[PM]: https://forum.kerbalspaceprogram.com/index.php?/topic/207261-*/ "Precise Maneuver (PM)"
[SCON]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-*/ "SimpleConstruction! (SCON)"
[SIL]: https://forum.kerbalspaceprogram.com/index.php?/topic/193050-*/ "Stock Inline Lights (SIL)"
[SILP]: https://forum.kerbalspaceprogram.com/index.php?/topic/193051-*/ "Stock Inline Lights Patches (SILP)"
[SLOG]: https://forum.kerbalspaceprogram.com/index.php?/topic/191045-*/ "SimpleLogistics! (SLOG)"
[SOL]: https://forum.kerbalspaceprogram.com/index.php?/topic/192489-*/ "Solar Science (SOL)"
[SPP]: https://forum.kerbalspaceprogram.com/index.php?/topic/192187-*/ "Shielded PicoPort (SPP)"
[LET]: https://www.curseforge.com/kerbal/ksp-mods/lithobrakeexplorationtechnologies "Lithobrake Exploration Technologies (LET)"
[DROP]: https://forum.kerbalspaceprogram.com/index.php?/topic/209332-*/  "Drop Tank Wrapper (DROP)"
[PRC]: https://forum.kerbalspaceprogram.com/index.php?/topic/209350-*/ "Portable Science Container (PRC)"

[AAL]: https://forum.kerbalspaceprogram.com/index.php?/topic/209301-*/ "AxialAerospace Ltd. (AA/L)"
[CARGO]: https://forum.kerbalspaceprogram.com/index.php?/topic/210255-/ "Simple Cargo Solutions (CARGO)"
[LTEK]: https://forum.kerbalspaceprogram.com/index.php?/topic/207923-*/ "LanderTek (LTEK)"
[WHIM]: https://forum.kerbalspaceprogram.com/index.php?/topic/204900-*/ "WhimChaser (WHIM)"

[cc]: https://forum.kerbalspaceprogram.com/index.php?/topic/91625-*/ "Contract Configurator"
[far]: https://forum.kerbalspaceprogram.com/index.php?/topic/179445-*/ "FAR"
[fs]: https://github.com/snjo/Firespitter/ "Firespitter Core"
[fsc]: https://github.com/snjo/Firespitter "Firespitter core"
[kis]: https://forum.kerbalspaceprogram.com/index.php?/topic/149848-*/ "Kerbal Inventory System"
[kjr]: https://forum.kerbalspaceprogram.com/index.php?/topic/184206-*/ "Kerbal Joint Reinforcement"
[krsh]: https://forum.kerbalspaceprogram.com/index.php?/topic/133082-*/ "KRASH"
[kurs]: https://github.com/linuxgurugamer/DockingCam "KURS style docking camera"
[lrtr]: https://forum.kerbalspaceprogram.com/index.php?/topic/189978-*/ "Less Real Than Real(ism)"
[mas]: https://forum.kerbalspaceprogram.com/index.php?/topic/160856-*/ "MOARdV's Avionics System"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
[rpm]: https://forum.kerbalspaceprogram.com/index.php?/topic/190737-*/ "Raster Prop Monitor"
[rt]: http://remotetechnologiesgroup.github.io/RemoteTech/ "RemoteTech"
[sr]: https://forum.kerbalspaceprogram.com/index.php?/topic/179306-*/ "StageRecovery"
[twk]: https://forum.kerbalspaceprogram.com/index.php?/topic/179030-*/ "TweakScale"

<!-- financial support -->
[PAYPAL:img]: https://img.shields.io/badge/Buy%20me%20some%20-LFO-BADA55?style=for-the-badge&logo=paypal&labelColor=FFDD00/ "PayPal"
[PAYPAL:url]: https://www.paypal.com/donate?hosted_button_id=DC22YHMEJREKL/ "PayPal"
[PATREON:img]: https://img.shields.io/badge/Patreon%20-Patreonize-FF424D?style=for-the-badge&logo=patreon/ "Patreon"
[PATREON:url]: https://www.patreon.com/bePatron?u=23390503/ "Patreon"
[GSPONS:img]: https://img.shields.io/badge/Github%20-Sponsor-EA4AAA?style=for-the-badge&logo=githubsponsors/ "Github Sponsors"
[GSPONS:url]: https://github.com/sponsors/zer0Kerbal/ "Github Sponsors"
[BMCC:img]: https://img.shields.io/badge/Buy%20Me%20a%20-Snack!-FFDD00?style=for-the-badge&logo=buymeacoffee/ "Buy Me A Snack"
[BMCC:url]: https://buymeacoffee.com/zer0Kerbal/ "Buy Me A Snack"

<!-- Localization -->
[lreadme]: https://github.com/zer0Kerbal/zer0Kerbal/blob/master/Localization/readme.md "Localization Readme"
[qstart]: https://github.com/zer0Kerbal/zer0Kerbal/blob/master/Localization/quickstart.md "Quickstart"
[EN]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/EN.png "English"

[curseforge]: https://www.curseforge.com/members/zer0kerbal/projects
[reddit]: https://www.reddit.com/user/zer0Kerbal
[twitch]: https://www.twitch.tv/zer0kerbal
[twitter]: https://twitter.com/zer0Kerbal
[youtube]: https://www.youtube.com/@zer0Kerbal
[steam]: https://steamcommunity.com/id/zeroKerbal/

[artwhaley]: https://forum.kerbalspaceprogram.com/index.php?/profile/118388-*/ "artwhaley"
[zer0Kerbal]: https://forum.kerbalspaceprogram.com/index.php?/profile/190933-*/ "zer0Kerbal "

[craft:0]: https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/craft/DreamerLaunchReady.craft "Craft File"

### Glorious IVA compliments of RPM

***Click on image for Imgur IVA Album***  
<a href="https://imgur.com/a/MbYJn"><img src="https://i.imgur.com/Iq5vOfW.png " alt="Updated IVA" width="75%" height="75%"></a>

#### Connect with me

Track progress: issues [here][issue] and projects [here](https://github.com/zer0Kerbal/Dreamer/projects/) along with **[The Short List](https://github.com/users/zer0Kerbal/projects/27)**

[<img align="left" alt="zer0Kerbal | kerbalspaceprogram.com" width="32px" src="https://cdn.icon-icons.com/icons2/1381/PNG/32/kerbalspaceprogram_93898.png" />][zer0Kerbal] [<img align="left" alt="zer0Kerbal | CurseForge" width="32px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/curseforge.svg" />][curseforge] [<img align="left" alt="zer0Kerbal | reddit" width="32px" src="https://cdn.icon-icons.com/icons2/1945/PNG/512/iconfinder-reddit-4661631_122483.png" />][reddit] [<img align="left" alt="zer0Kerbal | Patreon" width="32px" src="https://cdn.icon-icons.com/icons2/2429/PNG/512/patreon_logo_icon_147253.png" />][PATREON:url] [<img align="left" alt="zer0Kerbal | YouTube" width="32px" src="https://cdn.icon-icons.com/icons2/836/PNG/512/Youtube_icon-icons.com_66802.png" />][youtube] [<img align="left" alt="zer0Kerbal | Twitch" width="32px" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/twitch_logo_icon_170383.png" />][twitch] [<img align="left" alt="zer0Kerbal | PayPal" width="32px" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/paypal_logo_icon_168055.png" />][PAYPAL:url] [<img align="left" alt="zer0Kerbal | Buy Me a Coffee" width="32px" src="https://www.buymeacoffee.com/assets/img/bmc-meta-new/new/favicon.ico" />][BMCC:url] [<img align="left" alt="zer0Kerbal | Twitter" width="32px" src="https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/twitter-32.ico" />][twitter]</br>

##### Release Schedule

1. GitHub, reaching first manual installers and users of KSP-AVC. Right now.
2. CurseForge. Right now.
3. SpaceDock (and CKAN users). Soon™ *(the button was pressed)*

<!-- footnotes -->
[^1]: this isn't a mod. ;P  
[^2]: ***may*** work on other versions (YMMV)  
[^3]: *Be Kind: Lithobrake, not jakebrake! Keep your Module Manager up to date!*