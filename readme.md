<!-- readme.md v1.6.9.1
Keridian Dynamics (KDVA)
created: 17 Jul 2017
updated: 04 Jul 2022 -->

<!--this file: CC BY-ND 4.0 by zer0Kerbal-->

[![Keridian Dynamics][MOD:shd:latest]][MOD:forum] [![KSP version][KSP:shd]][KSP:url]  [![License][LIC:shd]][LIC:url]
[![Curseforge][CURSFG:shd]][CURSFG:url] [![GitHub][GITHUB:shd]][GITHUB:url] [![SpaceDock][SPCDCK:shd]][SPCDCK:url] [![CKAN][CKAN:shd]][CKAN:url] 
[![Pages][MOD:pages:shd]][MOD:pages]

# Keridian Dynamics (KDVA)

Parts pack for resource-conversion and vessel-assembly for Kerbal Space Program.

## By [`zer0Kerbal`][zer0Kerbal], originally by [Eleusis La Arwall][eleusislaarwall]

adopted with *express* permission and brought to you by *KerbSimpleCo*

## PECUNIA PER KERBULUS

<img src="https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/img/HeroLogo_1920x1920.png" alt="KeridianDynamics Hero" width="72%" height="72%">

### Preamble by [Eleusis La Arwall][eleusislaarwall]

> This pack contains a Furnace and a ChemicalReactor to convert Ore to Metal and a 3D-Printer to print RocketParts from Metal. Also some launchpads that require ExtraplanetaryLaunchpads to assemble vessels from Rocketparts and some tanks to store Metal and RocketParts. The production-chain is very basic: Ore --> Metal --> RocketParts --> Vessel.

---

### See More

* see [Parts Invoice][MOD:parts] for a Parts Catalog with pictures
* Discussions and news on this mod: See [Discussions][MOD:discu] or [KSP Forums][MOD:forum]
* Changelog Summary for more details of changes : See [ChangeLog][MOD:chlog]
* Known Issues for more details of feature requests and known issues : See [Known Issues][MOD:issue]
* GitHub Pages : See [Pages][MOD:pages]

### Help Wanted

> * Compatibility patches
> * Contracts for these glorious parts!
> * Variant Textures
> * Would love someone to convert from FireSpitter to Stock and/or KSPWheel
> * Model updates to Unity 2019
> * Have a request? Glad to have them, kindly submit through [GitHub][MOD:issue].

---

### Localization

>* ![English][EN] English
>* ***your translation here***
>
> HELP WANTED - See the [README in the Localization folder][lreadme] or the [Quickstart Guide][qstart] for instructions for adding or improving translations. [GitHub][GitHub:url] push is the best way to contribute. *Additions and corrections welcome!*

---

### Installation Directions [^1]

***Use***
  CurseForge/OverWolf App (currently does not install dependencies)

  <a href="https://download.curseforge.com/">
    <img src="https://www.overwolf.com/brand-guidelines/img/logo2.svg" alt="CurseForge/OverWolf App" width="15%" height="15%">
</a>

Whilst I agree CKAN is a great mod for those that can't use zip tools. I take no part, nor am I interested in maintaining the CKAN mod metadata for my mods.
Please don't ask me about it but refer to the CKAN mod thread if you are having issues with CKAN or the metadata it maintains. Beware, CKAN *can* really mess up though it tries very, very, very hard not to.

or [![CKAN][CKAN:img]][CKAN:url]

### Dependencies

* [Kerbal Space Program][KSP:url] [![Kerbal Space Program][KSP:shd]][KSP:url] [^2]

### Recommends

* Either
  * [Extraplanetary Launchpads (XPL)][xpl] or [SimpleConstruction! (SCON)][SCON]
    * One of the XPL based construction addons are 99.9% required
    * KSP will load all parts but some will have reduced or no function
    * The configs autodetects if [XPL][xpl] or [SCON][SCON] are installed and uses the corresponding modules
* [Module Manager][mm] or [Module Manager /L][mml][^3]
  * Resource Switchers Supported: [Interstellar Fuel Switch CORE][ifsc], [Firespitter][fs], [B9PartSwitch][b9ps]
  * One of the Resource Switcher addons are 99% required
  * KSP will load all parts but some will have reduced or no function
  * The configs autodetects if [Interstellar Fuel Switch CORE][ifsc], [Firespitter][fs] or [B9PartSwitch][b9ps] is installed and uses the corresponding modules
  * If multiple ResourceSwitchers are installed, the priority goes as follows: [Interstellar Fuel Switch CORE][ifsc] > [Firespitter][fs] > [B9PartSwitch][b9ps]

### Suggests

* [GPO (Goo Pumps & Oils') Speed Pump (GPO)][GPO]
* [Not So SimpleConstructon! (NSSC)][NSSC]
* [On Demand Fuel Cells (ODFC)][ODFC]
* [SimpleLogistics! (SLOG)][SLOG]
* [Transparent Command Pods (TP)][TCP]
* [GTIndustries][gti]
* [JSI Advanced Transparent Pods][atp]- *gives the  passable and nonpassable Storage Tanks an IVA overlay*
* [Kerbal Inventory System][kis] - *this gives the Launchsite and Sledgehammer function*
* [Kerbal Attachment System][kas] - *allows the RecycleSite to dump all recycled resources*
* [PatchManager][pm] - *allows patches to be easily toggleable*
* [TweakScale][twk]

### Supports

* Resource Switchers
  * [Interstellar Fuel Switch CORE][ifsc]
  * [Firespitter CORE][fsc]
  * [B9PartSwitch][b9ps]
* [Community Tech Tree][ctt]
* [Community Resource Pack][crp]
* [Connected Living Space][cls]
* [Contract Configurator][cc]
* [FAR][far]
* [Firespitter][fsc] for fully functioning wheels. may invoke bouts of dizziness.
* [GTIndustries][gti]
* [JSI Advanced Transparent Pods][atp]- *gives the  passable and nonpassable Storage Tanks an IVA overlay*
* [Kerbal Inventory System][kis] - *this gives the Launchsite and Sledgehammer function*
* [Kerbal Attachment System][kas] - *allows the RecycleSite to dump all recycled resources*
* [On Demand Fuel Cells (ODFC)][ODFC]
* [OSE Workshop][ose]
* [PatchManager][pm] - *allows patches to be easily toggleable*
* [ReStock][rstk]
* [TweakScale][twk]

### Replaces

* KeridianDynamicsVesselAssembly

### Tags

* parts, config, flags, agency, resources, science, tech-tree, career, crewed, uncrewed

---

### Experimental Section

* WARNING:
  * Very WIP! May not function as advertised. Designed for testing.
* Installation:
  * Copy the 'GameData' folder from ".zip/WIP_ExperimentalSection" to your Kerbal Space Program directory and overwrite if asked.
* The textures are complete overkill atm. Included lower-res textures (untested).

---

<div style="border:0.5px solid Tomato; background-color: #BADA55; color: #FF0000; text-align:center">
  <p><b>red box below is a link to forum post on how to get support</b></p>
  <a href="https://forum.kerbalspaceprogram.com/index.php?/topic/83212-*">
    <p><img src="https://i.postimg.cc/vHP6zmrw/image.png" alt="How to get support"></p></a>
  <p style="color: #000000;">Be Kind: Lithobrake, not jakebrake! Keep your Module Manager up to date</p>
</div>

### Credits and Special Thanks

A very big THANK YOU to the following mod developers and specially the plugin-writers/maintainers (because that is witchcraft to me ;) ) for their hard work:

* [Eleusis La Arwall][eleusislaarwall] for creating this glorious parts addon!
* see [Attribution.md][MOD:attr] for more comprehensive list

### Legal Mumbo Jumbo (License *provenance*)

#### Current (1) - [`zer0Kerbal`][zer0Kerbal]

> Forum: [Thread][MOD:forum] - Source: [GitHub][GITHUB:url]  
> License: [![License][LIC:shd]][LIC:url] ![License][LIC:log]
>
> ##### Disclaimer(s)
>
> ***All bundled mods are distributed under their own licenses***  
> ***All art assets (textures, models, animations, sounds) are distributed under their own licenses***

##### see [Notices.md][MOD:notic] for more *legal mumbo jumbo*

#### Original (0) - Author: [Eleusis La Arwall][eleusislaarwall]

> Forum: [Thread][MOD:0:thread] - Download: [Dropbox][MOD:0:dnload] - Source: [Dropbox][MOD:0:source]  
> License: [![License][LIC:0:shd]][LIC:0:url] ![License][LIC:0:log]

---

### How to support this and other great mods by [`zer0Kerbal`][zer0Kerbal]

[![Support][PAYPAL:img]][PAYPAL:url] [![Github Sponsor][GSPONS:img]][GSPONS:url] [![Patreon][PATREON:img]][PATREON:url] [![Buy zer0Kerbal a snack][BMCC:img]][BMCC:url]

---

<img src="https://i.imgur.com/WLHvoo8.png" alt="Keridian Dynamics Logo" width="72%" height="72%">
<img src="https://i.imgur.com/fn0gqpZ.jpg" alt="Product Line Up" width="72%" height="72%">

<!-- mod links -->

[MOD:attr]: https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/Attribution.md "Attribution"
[MOD:chlog]: https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/changelog.md  "Changelog"
[MOD:contr]: https://github.com/zer0Kerbal/.github/blob/master/.github/CONTRIBUTING.md "Contributing"
[MOD:discu]: https://github.com/zer0Kerbal/KeridianDynamics/discussions "Discussions"
[MOD:forum]: https://forum.kerbalspaceprogram.com/index.php?/topic/202945-*/ "KeridianDynamics Forum Thread"
[MOD:issue]: https://github.com/zer0Kerbal/KeridianDynamics/wiki/Known-Issues "GitHub Issues"
[MOD:licns]: https://github.com/zer0Kerbal/KeridianDynamics/blob/master/LICENSE "Github License"
[MOD:notic]: https://zer0kerbal.github.io/KeridianDynamics/Notices "Notices"
[MOD:parts]: https://zer0kerbal.github.io/KeridianDynamics/PartsCatalog "Parts Catalog"
[MOD:pages]: https://zer0kerbal.github.io/KeridianDynamics/ "GitHub Pages"

<!--- mod -->
[MOD:shd:latest]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/json/mod.json

[CODE:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/json/code.json

[MOD:pages:shd]: https://img.shields.io/badge/GitHub-Pages-white?style=plastic&labelColor=9cf&logoColor=181717&logo=github "GitHub IO"

<!--- mod provenance -->
[MOD:0:source]: https://github.com/EleusisLaArwall/KeridianDynamics-VesselAssembly/ "GitHub"
[MOD:0:thread]:https://forum.kerbalspaceprogram.com/index.php?/topic/116987-*/ "KSP Forum"
[MOD:0:download]: http://spacedock.info/mod/308 "SpaceDock"

<!--- license provenance -->
[LIC:0:url]: https://creativecommons.org/licenses/by-sa/4.0/ "CC BY-SA 4.0"
[LIC:0:log]: https://licensebuttons.net/i/l/by-sa/transparent/33/66/99/76x22.png "CC BY-SA 4.0"
[LIC:0:shd]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-ef9421?labelColor=black&style=plastic&logoColor=ef9421&logo=creativecommons "CC BY-SA 4.0"

[LIC:url]: https://creativecommons.org/licenses/by-sa/4.0/ "CC BY-SA 4.0"
[LIC:log]: https://licensebuttons.net/i/l/by-sa/transparent/33/66/99/76x22.png "CC BY-SA 4.0"
[LIC:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/json/license.json "CC BY-SA 4.0"

<!--- CKAN -->
[CKAN:img]: https://i.postimg.cc/x8XSVg4R/sj507JC.png "CKAN"
[CKAN:url]: http://forum.kerbalspaceprogram.com/index.php?/topic/197082-*/ "CKAN"
[CKAN:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/json/ckan.json "CKAN"

<!--- release links -->
[CURSFG:url]: https://www.curseforge.com/kerbal/ksp-mods/KeridianDynamics "Curseforge"
[CURSFG:shd]: https://img.shields.io/badge/CurseForge-Link-CCFF00.svg?labelColor=6441A4&style=plastic&logo=curseforge "Curseforge"

[GITHUB:url]: https://github.com/zer0Kerbal/KeridianDynamics/ "GitHub"
[GITHUB:shd]: https://img.shields.io/badge/Github-Link-CCFF00.svg?labelColor=181717&style=plastic&logo=github "GitHub"

[SPCDCK:url]: http://spacedock.info/mod/308 "SpaceDock"
[SPCDCK:shd]: https://img.shields.io/badge/SpaceDock-Link-CCFF00.svg?labelColor=181717&style=plastic&logo=data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0idXRmLTgiPz4KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIElsbHVzdHJhdG9yIDE5LjAuMCwgU1ZHIEV4cG9ydCBQbHVnLUluIC4gU1ZHIFZlcnNpb246IDYuMDAgQnVpbGQgMCkgIC0tPgo8c3ZnIHZlcnNpb249IjEuMSIgaWQ9IkxheWVyXzEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHg9IjBweCIgeT0iMHB4IgoJIHZpZXdCb3g9IjAgMCA1MDAgNTAwIiBzdHlsZT0iZW5hYmxlLWJhY2tncm91bmQ6bmV3IDAgMCA1MDAgNTAwOyIgeG1sOnNwYWNlPSJwcmVzZXJ2ZSI+CjxzdHlsZSB0eXBlPSJ0ZXh0L2NzcyI+Cgkuc3Qwe2ZpbGw6IzFBMUExQTt9Cgkuc3Qxe2ZpbGw6IzA1Nzg5Mzt9Cgkuc3Qye2ZpbGw6IzA3QUNEMjt9Cjwvc3R5bGU+CjxwYXRoIGlkPSJYTUxJRF8xXyIgY2xhc3M9InN0MCIgZD0iTTQwMCwwLjZIMTAwYy01NSwwLTEwMCw0NS0xMDAsMTAwVjQwMGMwLDU1LDQ1LDEwMCwxMDAsMTAwaDMwMGM1NSwwLDEwMC00NSwxMDAtMTAwVjEwMC42CglDNTAwLDQ1LjYsNDU1LDAuNiw0MDAsMC42eiIvPgo8ZyBpZD0iWE1MSURfNl8iPgoJPGcgaWQ9IlhNTElEXzlfIj4KCQk8cGF0aCBpZD0iWE1MSURfMTdfIiBjbGFzcz0ic3QxIiBkPSJNMTgzLjMsMTY1LjljNi40LTMuNiwxNi45LTMuNiwyMy4zLDBMNDY3LjQsMzE0YzYuNCwzLjYsNi40LDkuNiwwLDEzLjJMMjA2LjYsNDc0LjQKCQkJYy02LjQsMy42LTE3LjcsNi42LTI1LDYuNmgtNDQuOGMtNy40LDAtOC4xLTMtMS43LTYuNmwyNjEtMTQ3LjJjNi40LTMuNiw2LjQtOS42LDAtMTMuMkwxNzEsMTg2Yy02LjQtMy42LTYuNC05LjYsMC0xMy4yCgkJCUwxODMuMywxNjUuOXoiLz4KCTwvZz4KCTxnIGlkPSJYTUxJRF84XyI+CgkJPHBhdGggaWQ9IlhNTElEXzE2XyIgY2xhc3M9InN0MiIgZD0iTTMxOC44LDE5Yy03LjQsMC0xOC42LDIuOC0yNSw2LjRMMzMsMTczLjRjLTYuNCwzLjYtNi40LDkuNSwwLDEzLjFsMjYwLjcsMTQ3LjEKCQkJYzYuNCwzLjYsMTYuOSwzLjYsMjMuMywwbDEyLjMtN2M2LjQtMy42LDYuNC05LjUsMC0xMy4ybC0yMjUuMS0xMjdjLTYuNC0zLjYtNi40LTkuNSwwLTEzLjJMMzY1LjYsMjUuNGM2LjQtMy42LDUuNi02LjQtMS43LTYuNAoJCQlIMzE4Ljh6Ii8+Cgk8L2c+CjwvZz4KPC9zdmc+Cg==  "SpaceDock"

<!-- Kerbal Space Program -->
[KSP:url]: https://kerbalspaceprogram.com/ "Kerbal Space Program"
[KSP:shd]: https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/zer0Kerbal/KeridianDynamics/master/json/ksp.json&logo=data:image/webp;base64,UklGRpAGAABXRUJQVlA4TIQGAAAvH8AHEE0obNsGDakwXkT/Q4chj76jn1yYjSRjH6H+6xQqRUkkSc5ckHD+NUUVhx4+RNu2bTTl/3OTVhD6H8u6fF8dDYm40CK7N0CjAxK52rYtjfQRAvGNjbu7V+vuLp2fwhzA6gG4li6de+nuO+4uJBlkwoTA//90kENgtZZs27ZpO2Oufa5vbNsq2Sw6qaa9r3n/kZJTex/wSrFt27o62kuSJNuqrdTa1+/7uLu7uzQZAk0mRN/mAz2CAbi723vvy5WztxxIAAiw+dh2bdvWZJuT12y1bdu2bdu2bbs3AQABlsED+y50lDqLE4pf/Uxe8KO77HFes9hvxu1p3O2Q09LVg0NVjo7Z5U6AvwBSOfivKdQTujOnXNG8hzNhqYSMMHJ+MwWWyTSjNUoP1jWHp1ZNmgB8TMH3Tl33mvoVb8uIj3umyIJLsAmYoCIqUCVMCN5WrW78Qi+AkeaGOkWFk3QbRmIWHpIZSURXDxhJVlJiYZ6kLEgeEjIRCBmxebhCTWlTJNaXLystGysVToPOAFJJjqSPNOXftSVbXPQjxrzVaFNzXvBonWJlonIVTJabAfjZ0Jxufl5GPntEHKjB7PIXtg6eYHywJn3hTdijjXUain94KjfCfg1hM3AZRR4N16VMXBrsDVYDCjOIMmGFsAab8rdY7+kIw0BgtRgL1DKJeuNZdQ9f5RAGGfOQfZxexj7t37RkjNp4rPDIHOJVyPBF+XHKsnQk4SWRBl8Wot74WtkBqidQggbyj2vW1WEFG6JfUZ8UxhVzOmAUdKTYZ3yxR2QwIIAQdA9YgiRBZWyCguiOER9y9IauiyGqR0EayVLiEVwmXmF5+Z2jfohj8i1q8ybRahCBAXZBCBUqLgAACQFzp5M/o5wzCDcCJZEOF9EzggM7NEd18c1Q85gPBldtg6mwB1N+hzyTSFp5jWM+WpCRBEBAjIaUxJI80o3s6vDYJ7gNXuAUfOacvsLvLhNIMaMwh8GccsXjtuiK+wkxZ/kVdOCzoCeAOn+N7H1rU1YT35MgAWY9yD5wMWI7j7G976bSh8LxDx2jI3IJRAnJ+RQQIU7gABnLd3vKSyMAd71mq7HgV3AJ+Sxh5Bz5O0z/gbTiNT8DxQssrrv7Uyx9Y7q6BQVUoIGonF/FfoC/RqwVHlviCRSABDvLaCUfZlz1cNENn6adNTz+AF8v8KWQAFL+QMkpCthFkpvvq7+2/to6AIBhyvPdrUr3g1XwBEJPMeP/98SxWWvs3nHIhgNnsY1RWVyw+Guh5IZLgj9WzPi/iEk9gPPGLAni3aRlsqlGQ9jP4z9Q/s/xi3dw486abm6Bqi2l3qu9e9tQsdVMdG4zbVYqp5wJcBSA2W6sNmkwxuNk+nw3r4MFi/4EkTAhiRFk70jkqNDiWbDK65OLIn0s0wD/ucAp3XwVSsSNBAqjFUIXwFE0MihZQ6utQYV2oR+tShO7Ad6bswY3xd7qe0VrVxK9ZjueQy4TPnF8MCQGjoxSugSFgFMV4LiVwgsn/i+gXZ2FzplAduxnn0/OlW0uqf+M64MRPqzwrl+PnpKQSaXS49Ui7n2/ctFtHtAtiprzxq6WniwESvW5yUG1Xx6/8Hx8NKELwKZK15pV/EvXvm9ZMlx0aKUO98iUPaWvst/n8ZbOmkvGhcOQRWf5zj9dk9cfpad5oHN3Rns/wsuvy2puxz1Ziu96Q7/SOWoROzvNzFo5Z5+1BDej3OjQ/XymEkW9jr0em5g5SdX8VC2gf9xJb/RWCC5bIKWDgWcYf+K9Kje3zbQBh/F448wMLoICeUyJ330nXlPmawiRT/sblG4vWrbErgQaMzYbZcwbhSaNrwH+Tqa04jqrd3JZTvwbFxHFSVMAv5UZdEq+tQUupcis/5+MZNsxk9b8TPa7cMqdzzrh9FtD5v+vPACvJy7nDT69IP/Yx6EywGdTFsD5iU7bqkovJogzTjQm3iFTyp4jV4bjVKdcnv5/JrhokmpnGAIA4D/AXYCfVgoBXnrDkCqqCHRG529HeYB51Jy1z6nlW/gnVmzyxmVHxnQrxXxelcI0yN85udPl+//t2rzKzA+oluPTNjp6qY1PVduFVdo8ya+8E6p8KOZR+bLj6Vju9oi5dar0erTS8Z1x3/IITU3vyDRLiZWBZVH6CbqURTeLptD3pEPIR4W4QlHfTnRJzZBRJ8MlI8LmmEXLAdAxsqIYbSDGTt65GfF0cUL6aQQ= "Kerbal Space Program"

<!-- links to add-ons/mods -->
[GPO]: https://forum.kerbalspaceprogram.com/index.php?/topic/207732-*/ "GPO SpeedPump (GPO)"
[ODFC]: https://forum.kerbalspaceprogram.com/index.php?/topic/187625-*/ "On Demand Fuel Cells"
[TCP]: https://forum.kerbalspaceprogram.com/index.php?/topic/187495-*/ "Transparent Command Pods"
[SCON]: https://forum.kerbalspaceprogram.com/index.php?/topic/191424-*/ "SimpleConstructon!"
[SLOG]: https://forum.kerbalspaceprogram.com/index.php?/topic/191045-*/ "SimpleLogistics!"
[NSSC]: https://forum.kerbalspaceprogram.com/index.php?/topic/191504-*/ "Not So SimpleConstructon!"

[atp]: https://forum.kerbalspaceprogram.com/index.php?/topic/138433-*/ "JSI Advanced Transparent Pods"
[b9ps]: https://forum.kerbalspaceprogram.com/index.php?/topic/140541-*/ "B9 Part Switch"
[cc]: https://forum.kerbalspaceprogram.com/index.php?/topic/91625-*/ "ContractConfigurator"
[cls]: http://forum.kerbalspaceprogram.com/index.php?showtopic=192130-*/ "Connected Living Space"
[crp]: http://forum.kerbalspaceprogram.com/index.php?/topic/83007-*/ "Community Resource Pack"
[ctt]: https://forum.kerbalspaceprogram.com/index.php?/topic/90530-*/ "Community Tech Tree"
[far]: https://forum.kerbalspaceprogram.com/index.php?/topic/179445-*/ "FAR"
[fsc]: https://github.com/snjo/Firespitter/ "Firespitter"
[gti]: http://forum.kerbalspaceprogram.com/index.php?/topic/152667-*/ "GTIndustries"
[ifsc]: http://forum.kerbalspaceprogram.com/index.php?/topic/106243-* "Interstellar Fuel Switch CORE"
[kas]: http://forum.kerbalspaceprogram.com/index.php?/topic/142594-*/ "Kerbal Attachment System"
[kis]: http://forum.kerbalspaceprogram.com/index.php?/topic/149848-*/ "Kerbal Inventory System"
[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"
[ose]: http://forum.kerbalspaceprogram.com/index.php?/topic/163246-*/ "OSE Workshop"
[pm]: https://forum.kerbalspaceprogram.com/index.php?/topic/163072-*/ "PatchManager"
[rstk]: https://forum.kerbalspaceprogram.com/index.php?/topic/182679-*/ "ReStock"
[twk]: https://forum.kerbalspaceprogram.com/index.php?/topic/179030-*/ "TweakScale"
[xpl]: https://forum.kerbalspaceprogram.com/index.php?/topic/54284-*/ "Extraplanetary Launchpads"

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
[BR]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/BR.png "Português Brasil"
[CN]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/CH.png "中文"  
[DE]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/DE.png "Deutsch"  
[ES]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/ES.png "Español"  
[FR]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/FR.png "Français"  
[IT]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/IT.png "Italiano"  
[JA]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/JA.png "日本語"  
[KO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/KO.png "한국어"  
[MX]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/MX.png "Mexicano Español"  
[NL]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/NL.png "Dutch"  
[NO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/NO.png "Norsk"
[PO]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/PO.png "Polski"  
[RU]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/RU.png "Русский"  
[SW]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/SW.png "Svenska"  
[TR]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/TR.png "Türk"  
[TW]: https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/TW.png "国语"

[curseforge]: https://www.curseforge.com/members/zer0kerbal/projects
[reddit]: https://www.reddit.com/user/zer0Kerbal
[twitch]: https://www.twitch.tv/zer0kerbal
[twitter]: https://twitter.com/zer0Kerbal
[youtube]: https://www.youtube.com/channel/UCp9c8IaK4Gjgfj3O9QxrbDw

[eleusislaarwall]: https://forum.kerbalspaceprogram.com/index.php?/profile/116286-*/ "Eleusis La Arwall"
[zer0Kerbal]: https://forum.kerbalspaceprogram.com/index.php?/profile/190933-*/ "zer0Kerbal"

---

#### Connect with me

Track progress: issues [here][MOD:issue] and projects [here](https://github.com/zer0Kerbal/MOD-NAME/projects/) along with **[The Short List](https://github.com/users/zer0Kerbal/projects/27)**

[<img align="left" alt="zer0Kerbal | kerbalspaceprogram.com" width="32px" src="https://cdn.icon-icons.com/icons2/1381/PNG/32/kerbalspaceprogram_93898.png" />][zer0Kerbal] [<img align="left" alt="zer0Kerbal | CurseForge" width="32px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/curseforge.svg" />][curseforge] [<img align="left" alt="zer0Kerbal | reddit" width="32px" src="https://cdn.icon-icons.com/icons2/1945/PNG/512/iconfinder-reddit-4661631_122483.png" />][reddit] [<img align="left" alt="zer0Kerbal | Patreon" width="32px" src="https://cdn.icon-icons.com/icons2/2429/PNG/512/patreon_logo_icon_147253.png" />][PATREON:url] [<img align="left" alt="zer0Kerbal | YouTube" width="32px" src="https://cdn.icon-icons.com/icons2/836/PNG/512/Youtube_icon-icons.com_66802.png" />][youtube] [<img align="left" alt="zer0Kerbal | Twitch" width="32px" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/twitch_logo_icon_170383.png" />][twitch] [<img align="left" alt="zer0Kerbal | PayPal" width="32px" src="https://cdn.icon-icons.com/icons2/2699/PNG/512/paypal_logo_icon_168055.png" />][PAYPAL:url] [<img align="left" alt="zer0Kerbal | Buy Me a Coffee" width="32px" src="https://www.buymeacoffee.com/assets/img/bmc-meta-new/new/favicon.ico" />][BMCC:url] [<img align="left" alt="zer0Kerbal | Twitter" width="32px" src="https://cdn.icon-icons.com/icons2/836/PNG/32/Twitter_icon-icons.com_66803.png" />][twitter]

<!-- footnotes -->
[^1]: this isn't a mod. ;P
[^2]: ***may*** work on other versions (YMMV)
[^3]: *Be Kind: Lithobrake, not jakebrake! Keep your Module Manager up to date!*
