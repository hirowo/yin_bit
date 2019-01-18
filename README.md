# yin:bit
micro:bit用の拡張モジュールです。micro:bitでフルカラーLED(WS2812B)をコントロールできます。

## 概要
従来からmicro:bitでフルカラーLEDを点灯させるモジュール等はありましたが、  
micro:bitから出力される3.3VをフルカラーLEDの電源として使っているものや、  
電源を単3電池×3本を前提にしている物が多く、安定して光らせられるLEDの数は多くはありませんでした。

本モジュールは、本モジュールについているUSBコネクタから電源供給することで、  
micro:bitに給電しつつ、フルカラーLEDを5V給電することが可能です。

フルカラーLEDの点灯を一時的に抑えたいとき等のために、フルカラーLEDの電源ON/OFFスイッチも実装してあります。

Groveコネクタも実装してありますので、センサの値に応じて好きな色に光らせるといったこともできます。

よい電飾ライフを！

## スペック
サイズ：44×13×6mm  
フルカラーLED用電源電圧:5V  
Grove用電源電圧:3.3V

## ピン
フルカラーLEDシリアルピン:P0  
Grove用入出力ピン:P1/P2
