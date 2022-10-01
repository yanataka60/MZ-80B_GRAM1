# MZ-80B GRAM1ボード

　海外版MZ-80B回路図よりGRAM1ボードを作成したものです。後で確認したところ、国内版と若干の違いがありますが、今のところ不具合は起きていません。

## 部品表
|番号|品名|数量|備考|
| ------------ | ------------ | ------------ | ------------ |
|C1|電解コンデンサ 16V100uF|1||
|C2-C6, C8-C14, C16-C20|積層セラミックコンデンサ 0.1uF|17||
|C7|コンデンサ 1000pF|1||
|C15|コンデンサ 470pF|1||
|J1|2x20連結ピンソケット|1|秋月電子通商 FH-2x20SG(10)|
|J2|2x5ピンヘッダ|1|秋月電子通商 PH-2x40SG|
|R1-R4|カーボン抵抗 1k|4||
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
||2x5フラットケーブル|1|20cm程度|

## ボードの完成写真
![MZ80B_GRAM1_01](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_01.jpg)

## 取付方法
2x5Pinケーブルはマザーボートと同じ向きに挿します。手前左を1Pinとすればボードのピンソケットも手前左が1Pinとなるように接続します。

![MZ80B_GRAM1_02](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_02.jpg)

![MZ80B_GRAM1_03](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_03.jpg)

2x20ピンソケットは足の長い連結用ピンソケットを使うことでケーブルの干渉を避けることができます。

![MZ80B_GRAM1_04](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_04.jpg)

![MZ80B_GRAM1_05](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_05.jpg)

マザーボードのピンソケットに合わせてGRAM1ボードを挿し込みます。

![MZ80B_GRAM1_06](https://github.com/yanataka60/MZ-80B_GRAM1/blob/main/JPEG/MZ80B_GRAM1_06.jpg)

　純正拡張I/Oポートのケーブルとは干渉しないと思いますが、もし干渉するようであれば、2x20ピンソケットではなく、2x20ピンヘッダを基板表側に取り付け、純正GRAM1ボードのようにカセットデッキの裏側の留め具(右側2か所になんとか填められる気がします)に填めて2x20フラットケーブルで繋ぐことになります。
