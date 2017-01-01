# Applied Energistics 2

## Table of Contents

* [About](#about)
* [Downloads](#downloads)
* [Building](#building)
* [License](#license)
* [Credits](#credits)

## About

The point of this repo is to maintain a fork of AE2 for servers running SpongeForge. The patch used was made by [Prototik](https://github.com/Prototik). Downloads can be found below.

**All of the versions provided are provided "AS-IS" and with NO WARRANTIES. USE AT YOUR OWN RISK: if this breaks your world blows up your server or anything else, don't come to me!**

## Downloads

appliedenergistics2-rv4-alpha-7 [[94ce78d](https://github.com/Prototik/Applied-Energistics-2/commit/94ce78d123171d357ab7ff90db35d12003dc36aa)] [Download](https://raw.githubusercontent.com/Stonebound/Applied-Energistics-2/spongeforge/sponge-builds/appliedenergistics2-rv4-alpha-7.jar)  
appliedenergistics2-rv4-alpha-8 [[c8d5936](https://github.com/Stonebound/Applied-Energistics-2/commit/c8d5936c8c0a4286970b802bf49d2bf37dcfa402)] [Download](https://raw.githubusercontent.com/Stonebound/Applied-Energistics-2/spongeforge/sponge-builds/appliedenergistics2-rv4-alpha-8.jar)  
appliedenergistics2-rv4-alpha-9 [[fb42cb3](https://github.com/Stonebound/Applied-Energistics-2/commit/fb42cb33f6ed4b196f4a14a219d3f0cc2f250e11)] [Download](https://raw.githubusercontent.com/Stonebound/Applied-Energistics-2/spongeforge/sponge-builds/appliedenergistics2-rv4-alpha-9.jar)  
appliedenergistics2-rv4-alpha-11 [[820ada0](https://github.com/Stonebound/Applied-Energistics-2/commit/820ada0b7833589f04d495acbe6c10d5625f5f72)] [Download](https://raw.githubusercontent.com/Stonebound/Applied-Energistics-2/spongeforge/sponge-builds/appliedenergistics2-rv4-alpha-11.jar)

## Building

1. Clone this repository via
  - SSH `git clone git@github.com:Stonebound/Applied-Energistics-2.git` or
  - HTTPS `git clone https://github.com/Stonebound/Applied-Energistics-2.git`
2. Setup workspace
  - CI server `gradlew setupCIWorkspace` (enough if you just want to build your own version)
  - Decompiled source `gradlew setupDecompWorkspace`
  - Obfuscated source `gradlew setupDevWorkspace`
3. Build `gradlew build`. Jar will be in `build/libs`

## License

* Applied Energistics 2 API
  - (c) 2013 - 2015 AlgorithmX2 et al
  - [![License](https://img.shields.io/badge/License-MIT-red.svg?style=flat-square)](http://opensource.org/licenses/MIT)
* Applied Energistics 2
  - (c) 2013 - 2015 AlgorithmX2 et al
  - [![License](https://img.shields.io/badge/License-LGPLv3-blue.svg?style=flat-square)](https://raw.githubusercontent.com/AppliedEnergistics/Applied-Energistics-2/rv2/LICENSE)
* Textures and Models
  - (c) 2013 - 2015 AlgorithmX2 et al
  - [![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%203.0-yellow.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/3.0/)
* Text and Translations
  - [![License](https://img.shields.io/badge/License-No%20Restriction-green.svg?style=flat-square)](https://creativecommons.org/publicdomain/zero/1.0/)

## Credits

Thanks to
 
* Notch et al for Minecraft
* Lex et al for MinecraftForge
* AlgorithmX2 for AppliedEnergistics2
* all [contributors](https://github.com/AppliedEnergistics/Applied-Energistics-2/graphs/contributors)
