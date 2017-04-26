# General ISSUES repository to consider of CHIRIMEN Open Hardware Project

[![Join the chat at https://gitter.im/chirimen-org/meeting](https://badges.gitter.im/chirimen-org/meeting.svg)](https://gitter.im/chirimen-org/meeting?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

This repository is prepared to consider ISSUES of the CHIRIMEN Open Hardware Project. Therefore, it is used only for discussion purposes of [issues](https://github.com/chirimen-org/meeting/issues).


Projects
---
#### Discussion about CHIRIMEN (bulletin board)

* Please see [this link](https://github.com/issues?utf8=%E2%9C%93&q=is%3Aopen+is%3Aissue+user%3Achirimen-oh) to view all issues.

##### any-issues
* Bulletin board to discuss issues connected to the whole CHIRIMEN. An explanation of the following repository is also included (readme).

##### [Support-And-FAQ](https://github.com/chirimen-oh/Support-And-FAQ)
* Bulletin board to ask questions and support connected to CHIRIMEN.(If you have questions, please post to [issues](https://github.com/chirimen-oh/Support-And-FAQ/issues).)


##### [meeting](https://github.com/chirimen-oh/meeting)
* Repository for CHRIMEN monthly meeting

#### Development using CHIRIMEN, Repository on various information of CHIRIMEN
##### [examples](https://github.com/chirimen-org/examples)
* Basic program collection for using WebGPIO / I2C API that devices (sensors, actuators) that have been confirmed with CHIRIMEN. The usage of the device is explained in fabble and the program for that is collected in this repository.

* [fabbleへのリンク](http://fabble.cc/chirimenedu)

##### [chirimen-org.github.io](https://github.com/chirimen-org/chirimen-org.github.io)
* CHIRIMEN Homepage source code. Conversion by jekyll is necessary to write home page by markdown notation.

##### [CHIRIMEN-tools](https://github.com/chirimen-org/CHIRIMEN-tools)
* Tools collection useful for CHIRIMEN development and document creation. Drivers for Windows, image creation tools and CHIRIMEN material for Fritzing (schematic drawing tool) etc.

#### Repository on CHIRIMEN release
##### [release](https://github.com/chirimen-oh/release)
* Repository on the release of CHIRIMEN.

#### A repository of modules required for building a CHIRIMEN build
##### [B2G](https://github.com/chirimen-org/B2G)
* When building B2G base repository. Config for CHIRIMEN build etc had added. The necessary information is cloned using b2g-manifest below. If you want to build an image burned to CHIRIMEN, clone this repository.

##### [b2g-manifest](https://github.com/chirimen-org/b2g-manifest)
* Reference information to clone each of the following repositories (including other, external repositories) in config.sh of B2G. The following repositories are referenced from b2g-manifest, and as a result, these repositories are cloned under B2G by config.sh of B2G.

##### [gaia](https://github.com/chirimen-org/gaia) 
* It is equivalent to the gaia layer of B2G. To create an application or home screen when starting CHIRIME, edit this repository. Now, Is it necessary because it seems that customization for CHIRIMEN is not included?

##### [b2g-patches](https://github.com/chirimen-org/b2g-patches) 
* Patch collection for building B2G for CHIRIMEN and making it work. Eventually it is required to merge with gecko-dev to eliminate this repository.

##### [gecko-dev](https://github.com/chirimen-org/gecko-dev) 
* A customized version of B2G's gecko layer for CHIRIMEN. Implementation of webGPIO / I2C API is also included here. It is referred to from b2g-manifest.

#####  [i2c-tools](https://github.com/chirimen-org/i2c-tools) 
* A Linux program for execute I2C operations on the command line. It is incorporated in CHIRIMEN for confirmation of I2C operation on shell. It is referred to from b2g-manifest.

#####  [device-chirimen](https://github.com/chirimen-org/device-chirimen)
* It is referred to from b2g-manifest.

#####  [device-rockchip-rksdk](https://github.com/chirimen-org/device-rockchip-rksdk)
* It is referred to from b2g-manifest.

#####  [linux-rockchip](https://github.com/chirimen-org/linux-rockchip)
* It is referred to from b2g-manifest.

#####  [platform_system_core](https://github.com/chirimen-org/platform_system_core)
* It is referred to from b2g-manifest.


 __*__ _If there is a corresponding repository and there is no list above, please let us know the issue of this repository._



---


__*Note：*__ When linking from outside to this project github, please give a link to the location where README of this repository can refer.

