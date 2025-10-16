# MZ-80B GRAM1ボード

　MZ-80B OWNER'S MANUAL p65「図4-19 グラフィックメモリ1 MZ-8BG(オプション)」回路図から基板を起こしました。

　本体への装着方法は純正品と同じです。

## 回路図
　KiCadフォルダ内のMZ-80B_GRAM1.pdf参照

[回路図](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/KiCAD/MZ-80B_GRAM1.pdf)
![回路図](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/KiCAD/MZ-80B_GRAM1_1.jpg)

## 部品表
|番号|品名|数量|備考|
| ------------ | ------------ | ------------ | ------------ |
|C1|電解コンデンサ 16V100uF|1||
|C2-C6, C8-C14, C16-C20|積層セラミックコンデンサ 0.1uF|17||
|C7|コンデンサ 470pF|1||
|C15|コンデンサ 220pF|1||
|J1|2x20ピンヘッダ|1|秋月電子通商 PH-2x40SG等|
|J2|2x5ピンヘッダ|2|秋月電子通商 PH-2x40SG等|
|J3|2x5ピンヘッダ|2|GRAM2接続用 秋月電子通商 PH-2x40SG等|
|J3|使用しません|||
|R1-R4|カーボン抵抗 1k|4||
|R5|カーボン抵抗 47Ω|1||
|R6|カーボン抵抗 100Ω|1||
|U1|8kx8 SRAM 6264|1|若松通商等|
|U5-U8|74LS157|4|若松通商等|
|U10-U12|74LS93|3|若松通商等|
|U13|74LS245|1|若松通商等|
|U14|74LS165|1|若松通商等|
|U15|74LS175|1|若松通商等|
|U16|74LS04|1|若松通商等|
|U17|74LS107|1|若松通商等|
|U18, U20|74LS32|2|若松通商等|
|U19|74LS08|1|若松通商等|
|U21|74LS00|1|若松通商等|
||2x20フラットケーブル|1|15cm程度|
||2x5フラットケーブル|1|20cm程度|

## ボードの完成写真
![MZ80B_GRAM1_01](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_01.jpg)

## 取付方法
ケーブルは1Pinの△マークを合わせて接続します。マザーボート上で2x5Pinケーブルなら手前左に1Pinの△マークがあり、2x20Pinケーブルは、右奥に1Pinの△マークがあります。

![MZ80B_GRAM1_02](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_02.jpg)

![MZ80B_GRAM1_03](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_03.jpg)

![MZ80B_GRAM1_04](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_04.jpg)

![MZ80B_GRAM1_05](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_05.jpg)

上筐体の裏側にGRAM1ボードを挿し込みます。

![MZ80B_GRAM1_06](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_06.jpg)

## 追記
2025.10.10 回路図のpdfファイルを追加した。

2025.10.15 J3は使用しないので部品表を修正。

2025.10.16 すみません。GRAM2を使うときにはJ3必要でした。
