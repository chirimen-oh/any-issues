# CHIRIMEN Open Hardwareプロジェクトの総合的なISSUES検討場所

[![Join the chat at https://gitter.im/chirimen-org/meeting](https://badges.gitter.im/chirimen-org/meeting.svg)](https://gitter.im/chirimen-org/meeting?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

このリポジトリは、CHIRIMEN Open HardwareプロジェクトのISSUESを検討するために用意されています。
従って、[issues](https://github.com/chirimen-org/meeting/issues)の議論の目的のみで利用されます。


Projects
---

#### CHIRIMENに関する議論（掲示板）
##### any-issues
* CHIRIMEN全体に関わるissueを議論するための掲示板。下記レポジトリの説明も含まれる(readme)。

#### CHIRIMENを利用した開発、CHIRIMENの各種情報に関するリポジトリ
##### [examples](https://github.com/chirimen-org/examples)
* CHIRIMENで動作確認の取れたデバイス（センサー、アクチュエーター）をWebGPIO/I2C APIを使用し動作させるための基本プログラム集。
デバイスの利用法がfabbleで説明され、そのためのプログラムが本レポジトリに格納される。

##### [chirimen-org.github.io](https://github.com/chirimen-org/chirimen-org.github.io)
* CHIRIMENホームページのソースコード。
markdown記法でホームページを書いて掲載するためにはjekyllによる変換が必要。

##### [CHIRIMEN-tools](https://github.com/chirimen-org/CHIRIMEN-tools)
* CHIRIMENの開発、ドキュメント作成に役立つツール集。
Windows用ドライバ、イメージ作成ツールやFritzing（回路図作成ツール）用のCHIRIMEN素材など。

#### CHIRIMENのリリースに関するリポジトリ
##### [release-candidate](https://github.com/chirimen-org/release-candidate)
* CHIRIMENのリリース候補に関するリポジトリ。
 
#### CHIRIMEN用ビルドを作るために必要となるモジュールのレポジトリ
##### [B2G](https://github.com/chirimen-org/B2G)
* B2Gをビルドする際の大元となるレポジトリ。CHIRIMEN用ビルドのためのconfigなどが追加されている。
下記b2g-manifestを使い必要な情報がcloneされる。CHIRIMENに焼くイメージをビルドをしたい場合、このリポジトリをcloneする。

##### [b2g-manifest](https://github.com/chirimen-org/b2g-manifest)
* B2Gのconfig.shで以下の各リポジトリ（他、外部のリポジトリも含まれる）をcloneするための参照情報。以下のリポジトリがb2g-manifest から参照され、結果として、B2Gのconfig.sh でこれらのリポジトリが B2G の下にclone される。

##### [gaia](https://github.com/chirimen-org/gaia) 
* B2Gのgaia層に相当。
CHIRIME起動時のアプリやホーム画面を作る場合はこのレポジトリを編集する。
**(確認中)現在はCHIRIMEN用のカスタマイズは入っていないと思われるため特別に必要か？**

##### [b2g-patches](https://github.com/chirimen-org/b2g-patches) 
* B2GをCHIRIMEN用にビルドして動作させるためのpatch集。
いずれはgecko-devにマージしてこのレポジトリをなくすことが求められる。

##### [gecko-dev](https://github.com/chirimen-org/gecko-dev) 
* B2Gのgecko層をCHIRIMEN用にカスタマイズしたもの。webGPIO/I2C APIの実装もここに組み込まれる。
b2g-manifestから参照されている。

#####  [i2c-tools](https://github.com/chirimen-org/i2c-tools) 
* コマンドライン上でI2Cの操作を行うためのLinuxプログラム。
shell上でのI2C動作確認用にCHIRIMENに組み込まれる。
b2g-manifestから参照されている。

#####  [device-chirimen](https://github.com/chirimen-org/device-chirimen)
* **(確認中)Firefoxブラウザ向けWebIDEに"CHIRIMEN"を認識させるための変更など。**
b2g-manifestから参照されている。

#####  [device-rockchip-rksdk](https://github.com/chirimen-org/device-rockchip-rksdk)
* **(確認中)I2CやGPIOを操作するためのpermissionの設定など?**
b2g-manifestから参照されている。

#####  [u-boot-rockchip](https://github.com/chirimen-org/u-boot-rockchip)
* **(確認中)CHIRIMENのチップ(rk3066)用のカーネルを作るのに必要？**
b2g-manifestから参照されている。

#####  [linux-rockchip](https://github.com/chirimen-org/linux-rockchip)
* **(確認中)CHIRIMENのチップ(rk3066)用のカーネルを作るのに必要？**
**u-boot-rockchipとの違いを書きたいが…**
b2g-manifestから参照されている。

#####  [platform_system_core](https://github.com/chirimen-org/platform_system_core)
* **(確認中)GPIOに対し正しくpermissionを設定するための回避策として必要。**
b2g-manifestから参照されている。


 __*__ _該当リポジトリがあり、上に一覧が無い場合は当リポジトリのissuesに御知らせください。_



---


__*お願い：*__ 外部から当プロジェクトgithubへリンクされる場合、このリポジトリのREADMEが参照出来る位置へのリンクを御願いします。

