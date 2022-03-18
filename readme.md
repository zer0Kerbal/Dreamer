<!-- readme.md v1.6.5.9
Dreamer (DREAM)
created: 01 Oct 2019
updated: 05 Mar 2022 -->

<!--this file: CC BY-ND 3.0 unported by zer0Kerbal-->

[![Dreamer][MOD:shd:latest]][MOD:forum] [![KSP version][KSP:shd]][KSP:url]  [![License][LIC:shd]][LIC:url]
[![Curseforge][CURSFG:shd]][CURSFG:url] [![CKAN][CKAN:shd]][CKAN:url] [![GitHub][GITHUB:shd]][GITHUB:url] [![SpaceDock][SPCDCK:shd]][SPCDCK:url]
![Code][CODE:shd] ![KSP-AVC][AVC:shd] ![Validate AVC .version files][AVCVLD:shd]

[![GitHub Pages][MOD:pages:shd]][MOD:pages]




# Axial Aerospace Dreamer (AAD)

A roughly 2/3 scale model of Kierra Kevada Corp's Dream Kaser vertical launch spaceplane with cargo bay and docking nosecone!

## By [`zer0Kerbal`][LINK:zer0Kerbal], originally by [`artwhaley`][LINK:artwhaley]

---

### Hero Shots

***Click on image for Imgur Album***  
<a href="https://imgur.com/a/gd8Sp"><img src="https://i.imgur.com/NKiQQHk.png" alt="Hero Pose" width="50%" height="50%"> <img src="https://i.imgur.com/YeRx3QM.png" alt="Hero Pose II" width="50%" height="50%"></a>

### Glorious IVA compliments of RPM

***Click on image for Imgur IVA Album***  
<a href="https://imgur.com/a/MbYJn"><img src="https://i.imgur.com/Iq5vOfW.png " alt="Updated IVA" width="75%" height="75%"></a>

### Youtube review by [`Kottabos Gaming`](https://forum.kerbalspaceprogram.com/index.php?/profile/36583-kottabos/)

[![Kottabos reviews Dreamer](https://img.youtube.com/vi/Oj1etoybd7E/0.jpg)](https://www.youtube.com/watch?v=Oj1etoybd7E)

---

[Link to Craft File][LINK:craft:0]

### What's included

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

### Notes by [@artwhaley][LINK:artwhaley]

> * The centaur loads with less than full fuel tanks... and the Dreamer loads with more fuel than you probably need. I highly recommend planning your missions and adjusting the fuel in these two stages appropriately.
> * There's an electric generator built into the capsule. And the output is HIGH. I've had to do this to make the batteries last all the way through re-entry. I suppose I could turn the power down on the flywheel system. I'll play with that. But at the moment you'll never run out of electricity. Which is a little hacky. I need to get this into balance.
> * The mod supports DRE and FAR. The Far support should be considered a WIP. Please give feedback. The ship isn't designed to be EASY to fly, but if it's uncontrollable it's probably a bug. In general - space planes are hard to fly... Over the course of development I've bowed to pressure a few times to make this easier to handle during reentry and landing.... but it still isn't stupidly forgiving... I recommend reentering such that a ballistic landing would put you right on the KSP pad, so your lifting surfaces will make for a long overshoot... then out over the water at around 10,000m of altitude you can come back around to point west for landing.
> * **The Atlas V 402 launcher is low detail**, but it exists. I've put the .blend files in the abandoned model thread and you're welcome to start with my cfg files.... so if anyone is looking for a mod project, a day texturing what's already there... a couple of days building fairings and payload adapters, and a day modelling the single nozzle Centaur engine and you'd have a stand-alone Atlas V mod ready to release. :) All I ask is the option to include any improvements you make back into this mod if they fit with it! :) I may move on to this project eventually myself... but I've got a couple of projects ahead of it, so please feel free. I'll gladly help someone along, if it's their first project! :)
>* **Important Note:** This ship draws inspiration from several places, both real world and fictional craft. Any resemblance it bears to specific craft, however, is purely incidental. I've been asked not to use any trademarks belonging to a certain real world company working on a certain real world vertical launch, horizontal recovery shuttle, so let's enjoy this for what it is - a purely fantasy ship with many design features of it's very own.

---

### Help Wanted

> * Would love someone to convert from FireSpitter to Stock and/or KSPWheel  
> * Variant Textures and code to make it work always welcome!
> * Model updates to Unity 2019
> * Have a request? Glad to have them, kindly submit through GitHub.

---

### Localization - *work in progress*

>* [x] ![English][EN] English - in progress
>* [ ] ***your translation here***
>
> HELP WANTED - See the [README in the Localization folder][MOD:local] for instructions for adding or improving translations. [GitHub][GitHub:url] push is the best way to contribute. *Additions and corrections welcome!*

---

### How to support this and other great mods by [`zer0Kerbal`][LINK:zer0Kerbal]  

[![Support][PAYPAL:img]][PAYPAL:url] [![Github Sponsor][GSPONS:img]][GSPONS:url] [![Patreon][PATREON:img]][PATREON:url] [![Buy zer0Kerbal a snack][BMCC:img]][BMCC:url]

---

### See More

* Discussions and news on this mod: See [Discussions][MOD:discu] or [KSP Forums][MOD:forum]
* Changelog Summary for more details of changes : See [ChangeLog][MOD:chlog]
* Known Issues for more details of feature requests and known issues : See [Known Issues][MOD:known]
* GitHub Pages : See [Pages][MOD:pages]

---

### Installation Directions

***Use***
  CurseForge/OverWolf App (currently does not install dependencies) [^3]  

  <a href="https://download.curseforge.com/">
    <img src="https://www.overwolf.com/brand-guidelines/img/logo2.svg" alt="CurseForge/OverWolf App" width="15%" height="15%">
</a>

or [![CKAN][CKAN:img]][CKAN:url] [^3]  

### Dependencies

* [Kerbal Space Program][KSP:url] [![Kerbal Space][KSP:shd]][KSP:url] [^1]

### Recomends

* [On Demand Fuel Cells][thread:ODFC]

### Suggests

* [Module Manager][thread:mm][^2]
* [Kerbal Joint Reinforcement - Next][thread:kje]
* [Less Real Than Real(ism)][thread:lrtr] by [@Pehvbot][LINK:]
* One of the following:
  * [Raster Prop Monitor][thread:rpm]  Make the IVA look great!
  * [MOARdV's Avionics Systems][thread:mas]  Make the IVA look great!

### Supports

* [TweakScale][thread:tweakscale]
* [KRASH][thread:krsh]
* [RemoteTech][thread:rt]
* [NEAR-FAR][thread:far]
* [ContractConfigurator][thread:cc]
* [Firespitter][thread:fs] for fully functioning wheels. may invoke bouts of dizziness.

---

<div style="border:0.5px solid Tomato; background-color: #BADA55; color: #FF0000; text-align:center">
<p><b>*red box below is a link to forum post on how to get support*</p>  
<a href = "https://forum.kerbalspaceprogram.com/index.php?/topic/83212-*">
  <p><img src = "https://i.postimg.cc/vHP6zmrw/image.png" alt="How to get support"></p></a>Be Kind: Lithobrake, not jakebrake! Keep your Module Manager up to date</div>

### Credits and Special Thanks

* [`Mike-NZ`][LINK:mike-nz]  for taking over and improving/updating this ship through the 1.0 to 1.0.4 stage! He solved some problems I'd been banging my head against and I can't say enough how good it feels to have a project of yours matter enough to someone to put the effort into it that he did!
* [`artwhaley`][LINK:artwhaley] for creating this glorious mod!

### Legal Mumbo Jumbo (License *provenance*)

#### Current (1) - [`zer0Kerbal`][LINK:zer0Kerbal]

> Forum: [Thread][MOD:forum] - Source: [GitHub][GITHUB:url]  
> License: [![License][LIC:shd]][LIC:url] ![License][LIC:log]
>
> ##### Disclaimer(s)
>
> ***All bundled mods are distributed under their own licenses***  
> ***All art assets (textures, models, animations, sounds) are distributed under their own licenses***

#### Original (0) - Author: [`artwhaley`][LINK:artwhaley]

> Forum: [Thread][MOD:org:thread]  - Download: [Dropbox][MOD:org:download] - Source: [Dropbox][MOD:org:source]
> License: [![License][LIC:org:shd]][LIC:org:url] ![License][LIC:org:log]

<!-- mod links -->
[MOD:forum]: https://forum.kerbalspaceprogram.com/index.php?/topic/207306-* "Dreamer Forum Thread"
[MOD:chlog]: https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/changelog.md  "Changelog"
[MOD:contr]: https://github.com/zer0Kerbal/.github/blob/master/.github/CONTRIBUTING.md "Contributing"
[MOD:discu]: https://github.com/zer0Kerbal/Dreamer/discussions "Discussions"
[MOD:issue]: https://github.com/zer0Kerbal/Dreamer/wiki/Known-Issues "GitHub Issues"
[MOD:known]: https://github.com/zer0Kerbal/Dreamer/wiki/Known-Issues "Known Issues"
[MOD:licns]: https://github.com/zer0Kerbal/Dreamer/blob/master/LICENSE "Github License"
[MOD:local]: https://github.com/zer0Kerbal/Dreamer/blob/master/GameData/Dreamer/Localization/readme.md "Localization"
[MOD:pages]: https://zer0kerbal.github.io/Dreamer/ "GitHub Pages"
[MOD:wiki]: https://github.com/zer0Kerbal/Dreamer/wiki "Wiki"

<!--- mod -->
[MOD:shd:latest]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/mod.json

[CODE:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/code.json

[MOD:pages:shd]: https://github.com/zer0Kerbal/Dreamer/actions/workflows/pages/pages-build-deployment/badge.svg "GitHub IO"

<!--- mod provenance -->

[MOD:org:source]: https://github.com/artwhaley/Dreamer
[MOD:org:thread]: https://forum.kerbalspaceprogram.com/index.php?/topic/126208-*
[MOD:org:download]: https://github.com/artwhaley/Dreamer/releases/latest

<!--- license provenance-->
[LIC:org:url]: https://www.gnu.org/licenses/gpl-3.0-standalone.html "GPLv3"
[LIC:org:log]: https://i.postimg.cc/9FrwMgK6/GPL-17x17.png "GPLv3"
[LIC:org:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/license.json "GPLv3"

[LIC:url]: https://www.gnu.org/licenses/gpl-3.0-standalone.html "GPLv3"
[LIC:log]: https://i.postimg.cc/9FrwMgK6/GPL-17x17.png "GPLv3"
[LIC:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/license.json "GPLv3"

<!--- AVC -->
[AVC:shd]:  https://img.shields.io/badge/KSP-AVC--supported-00C961.svg?labelColor=black&style=plastic
[AVCVLD:shd]: https://github.com/zer0Kerbal/Dreamer/workflows/Validate%20AVC%20.version%20files/badge.svg?labelColor=black&style=plastic "AVC-Valid - thank you to DasSkelett"

<!--- CKAN -->
[CKAN:img]: https://i.postimg.cc/x8XSVg4R/sj507JC.png "CKAN"
[CKAN:url]: http://forum.kerbalspaceprogram.com/index.php?/topic/197082-* "CKAN"
[CKAN:shd]: https://img.shields.io/badge/CKAN-Dreamer-white.svg?labelColor=E32811&style=plastic "CKAN"

<!--- release links -->
[CURSFG:url]: https://www.curseforge.com/kerbal/ksp-mods/AADreamer "Curseforge"
[CURSFG:shd]: https://img.shields.io/badge/CurseForge-Listed-white.svg?labelColor=6441A4&style=plastic&logo=curseforge "Curseforge"

[GITHUB:url]: https://github.com/zer0Kerbal/Dreamer/ "GitHub"
[GITHUB:shd]: https://img.shields.io/badge/Github-Listed-white.svg?labelColor=181717&style=plastic&logo=github "GitHub"

[SPCDCK:url]: http://spacedock.info/mod/2999 "SpaceDock"
[SPCDCK:shd]:  https://img.shields.io/badge/SpaceDock-Listed-white.svg?labelColor=181717&style=plastic&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA1MDAgNTAwIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MDAgNTAwOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+CjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+Cgkuc3Qwe2ZpbGw6IzFBMUExQTt9Cgkuc3Qxe2ZpbGw6IzA1Nzg5Mzt9Cgkuc3Qye2ZpbGw6IzA3QUNEMjt9Cjwvc3R5bGU+CjxwYXRoIGlkPSJYTUxJRF8xXyIgY2xhc3M9InN0MCIgZD0iTTQwMCwwLjZIMTAwYy01NSwwLTEwMCw0NS0xMDAsMTAwVjQwMGMwLDU1LDQ1LDEwMCwxMDAsMTAwaDMwMGM1NSwwLDEwMC00NSwxMDAtMTAwVjEwMC42CglDNTAwLDQ1LjYsNDU1LDAuNiw0MDAsMC42eiIvPgo8ZyBpZD0iWE1MSURfNl8iPgoJPGcgaWQ9IlhNTElEXzlfIj4KCQk8cGF0aCBpZD0iWE1MSURfMTdfIiBjbGFzcz0ic3QxIiBkPSJNMTgzLjMsMTY1LjljNi40LTMuNiwxNi45LTMuNiwyMy4zLDBMNDY3LjQsMzE0YzYuNCwzLjYsNi40LDkuNiwwLDEzLjJMMjA2LjYsNDc0LjQKCQkJYy02LjQsMy42LTE3LjcsNi42LTI1LDYuNmgtNDQuOGMtNy40LDAtOC4xLTMtMS43LTYuNmwyNjEtMTQ3LjJjNi40LTMuNiw2LjQtOS42LDAtMTMuMkwxNzEsMTg2Yy02LjQtMy42LTYuNC05LjYsMC0xMy4yCgkJCUwxODMuMywxNjUuOXoiLz4KCTwvZz4KCTxnIGlkPSJYTUxJRF84XyI+CgkJPHBhdGggaWQ9IlhNTElEXzE2XyIgY2xhc3M9InN0MiIgZD0iTTMxOC44LDE5Yy03LjQsMC0xOC42LDIuOC0yNSw2LjRMMzMsMTczLjRjLTYuNCwzLjYtNi40LDkuNSwwLDEzLjFsMjYwLjcsMTQ3LjEKCQkJYzYuNCwzLjYsMTYuOSwzLjYsMjMuMywwbDEyLjMtN2M2LjQtMy42LDYuNC05LjUsMC0xMy4ybC0yMjUuMS0xMjdjLTYuNC0zLjYtNi40LTkuNSwwLTEzLjJMMzY1LjYsMjUuNGM2LjQtMy42LDUuNi02LjQtMS43LTYuNAoJCQlIMzE4Ljh6Ii8+Cgk8L2c+CjwvZz4KPC9zdmc+Cg==  "SpaceDock"

<!-- Kerbal Space Program -->
[KSP:url]: https://kerbalspaceprogram.com/ "Kerbal Space Program"
[KSP:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/json/ksp.json&logo=data:image/webp;base64,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 "Kerbal Space Program"

<!-- financial support -->
[PAYPAL:img]: https://img.shields.io/badge/Buy%20me%20some%20-LFO-BADA55?style=for-the-badge&logo=paypal&labelColor=FFDD00 "PayPal"
[PAYPAL:url]: https://www.paypal.com/donate?hosted_button_id=DC22YHMEJREKL "PayPal"
[PATREON:img]: https://img.shields.io/badge/Patreon%20-Patreonize-FF424D?style=for-the-badge&logo=patreon "Patreon"
[PATREON:url]: https://www.patreon.com/bePatron?u=23390503 "Patreon"
[GSPONS:img]: https://img.shields.io/badge/Github%20-Sponsor-EA4AAA?style=for-the-badge&logo=githubsponsors "Github Sponsors"
[GSPONS:url]: https://github.com/sponsors/zer0Kerbal "Github Sponsors"
[BMCC:img]: https://img.shields.io/badge/Buy%20Me%20a%20-Snack!-FFDD00?style=for-the-badge&logo=buymeacoffee "Buy Me A Snack"
[BMCC:url]: https://buymeacoffee.com/zer0Kerbal "Buy Me A Snack"

<!-- Localization -->
[EN]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/American-flag-sm.png "American English"
[BR]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Brazilian-flag-sm.png "Brasil"
[CN]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Chinese-flag-sm.png "中文"
[DE]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/German-flag-sm.png "Deutsch"
[ES]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Spanish-flag-sm.png "Español"
[FR]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/French-flag-sm.png "Français"
[IT]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Italian-flag-sm.png "Italiano"
[JA]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Japanese-flag-sm.png "日本語"
[KO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/South-Korean-flag-sm.png "한국어"
[ME]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Mexican-flag-sm.png "Español Mexicano"
[NL]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Dutch-flag-sm.png "Dutch"
[NO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Norwegian-flag-sm.png "Norsk"
[PO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Polish-flag-sm.png "Polski"
[RU]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Russian-flag-sm.png "Русский"
[SW]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Swedish-flag-sm.png "Svenska"
[TW]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Taiwanese-flag-sm.png "国语"
[HA]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/zed'K/Localization/img/Hawaii-flag-sm.png "ʻŌlelo Pākē"

<!-- links to add-ons/mods --> 
[thread:BIO]: https://forum.kerbalspaceprogram.com/index.php?/topic/191426-* "Biomatic"
[thread:ODFC]: https://forum.kerbalspaceprogram.com/index.php?/topic/187625-* "On Demand Fuel Cells"
[thread:ckan]: https://forum.kerbalspaceprogram.com/index.php?/topic/154922-* "CKAN"

[thread:mm]:  https://github.com/net-lisias-ksp/ModuleManager "Module Manager"
[thread:cc]: https://forum.kerbalspaceprogram.com/index.php?/topic/91625-* "Contract Configurator"
[thread:fs]: https://github.com/snjo/Firespitter "Firespitter"
[thread:rt]: http://remotetechnologiesgroup.github.io/RemoteTech/ "RemoteTech"
[thread:sr]: https://forum.kerbalspaceprogram.com/index.php?/topic/179306-* "StageRecovery"
[thread:crp]: http://forum.kerbalspaceprogram.com/index.php?/topic/83007-* "Community Resource Pack"
[thread:far]: https://forum.kerbalspaceprogram.com/index.php?/topic/179445-* "NEAR-FAR"
[thread:kjr]: https://forum.kerbalspaceprogram.com/index.php?/topic/184206-* "Kerbal Joint Reinforcement - Next"
[thread:mas]: https://forum.kerbalspaceprogram.com/index.php?/topic/160856-* "MOARdV's Avionics Systems"
[thread:rpm]: https://forum.kerbalspaceprogram.com/index.php?/topic/190737-* "RasterPropMonitor"
[thread:twk]: https://forum.kerbalspaceprogram.com/index.php?/topic/179030-* "TweakScale"
[thread:lrtr]: https://forum.kerbalspaceprogram.com/index.php?/topic/189978-* "Less Real Than Real(ism)"
[thread:krsh]: https://forum.kerbalspaceprogram.com/index.php?/topic/133082-* "KRASH"

[LINK:zer0Kerbal]: https://forum.kerbalspaceprogram.com/index.php?/profile/190933-zer0kerbal/ "zer0Kerbal "
[LINK:artwhaley]: https://forum.kerbalspaceprogram.com/index.php?/profile/118388-artwhaley/ "artwhaley"
[LINK:mike-nz]: https://forum.kerbalspaceprogram.com/index.php?/profile/142683-mike-nz/ "Mike-NZ"
[LINK:craft:0]: https://raw.githubusercontent.com/zer0Kerbal/Dreamer/master/craft/DreamerLaunchReady.craft "Craft File"

<!-- footnotes -->
[^1]: ***may*** work on other versions (YMMV)
[^2]: *Be Kind: Lithobrake, not jakebrake! Keep your Module Manager up to date!*
[^3]: this isn't a mod. ;P

***Docking***
[![Dreamer Docking](https://img.youtube.com/vi/X_JThlA_xnw/0.jpg)](https://www.youtube.com/watch?v=X_JThlA_xnw)
***Building***
[![Dreamer Building](https://img.youtube.com/vi/GQLg9gWbaOI/0.jpg)](https://www.youtube.com/watch?v=GQLg9gWbaOI)
***Ascent and IVS Tour***
[![Dreamer Ascent and IVS Tour](https://img.youtube.com/vi/YMo9vXFeigo/0.jpg)](https://www.youtube.com/watch?v=YMo9vXFeigo)


<details>
  <summary><b>Youtube review by <a href="https://forum.kerbalspaceprogram.com/index.php?/profile/36583-kottabos/ ">@Kottabos Gaming</a></b></summary>
  Support on <a href="https://www.patreon.com/Kottabosgames">Patreon.</a>
  <iframe width="1136" height="639" src="https://www.youtube.com/embed/Oj1etoybd7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</details>
