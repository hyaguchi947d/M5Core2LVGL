# M5Stack Core2でLVGLを動かしてみたサンプル

PlatformIO on Windows10で動作確認をしています。

https://platformio.org/

## 必要ライブラリ

以下のライブラリをプロジェクトに追加してください。

- LovyanGFX
  - https://github.com/lovyan03/LovyanGFX
- LVGL
  - https://lvgl.io/

## lv_conf.hについて

`include/lv_conf_m5core2.h`を
`libdeps/m5stack-core2/lvgl`
に`lv_conf.h`として配置してください。


## ライセンスについて

LVGLのサンプルを元に作成しています。
著者の追加実装部分についてはPublic Domainとさせていただきます。
LVGL由来のコードについてはオリジナル(MIT)に従ってください。

LICENSE:
This program is based on LVGL sample.
Part of author's edit is Public Domain.
Codes from LVGL sample are MIT.
