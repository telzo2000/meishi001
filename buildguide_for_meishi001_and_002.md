# Build guide

## Parts list


| No. | Patrs | Quantity | remarks | Suppliers | Cost |
|--|--|--|--|--|--|
|番号|名前|数|備考|調達先|参考価格（送料込）|<br>
|1|PCB|1|keyboard|[elecrow](https://www.elecrow.com)<br>[JLCPCB](https://jlcpcb.com)<br>[ALLPCB](https://www.allpcb.com)|5枚で5ドル|<br>
|2-1|pro micro|1|ピンヘッダ含む|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|価格変動中|
|2-2|BLE MIcro(Pro MicroサイズのUSB対応nRF52マイコンボード)|1|電池基板キットも含む|[遊舎工房](https://yushakobo.jp)<br>[のぎすけ屋](https://nogikes.booth.pm)|１個4500円|
|3|Diode<br>ダイオード|45|リードタイプ|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|100個で220円程度から|
|4|tactile switch|45|TVBP06-B043CB-B|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)<br>[秋月電子通商](https://akizukidenshi.com/catalog/g/gP-08073/)|１個20円から|
この他に、USBケーブルが必要です。
<br><br>


## Firmware

[Here](https://github.com/telzo2000/meishi001/tree/main/firmware)

<br>
[remap](https://remap-keys.app/)

<br>
<br><br>


## Build

Please read it and then work on it.
<br>
一読してから、作業をしてください。
<br><br>


### Photo

Front side（表面）<br>
![](img/img00009.jpg)

Back side(裏面)<br>
![](img/img00010.jpg)


<br><br>


### 1 Diode soldering

Solder the diode on the front side.
<br>
表面にダイオードのハンダ付けをします。
<br>

<br>
<br>

### 2 Soldering switch

Solder the switch on the front side.
<br>
表面にスイッチのハンダ付けをします。
<br>

<br><br>


### 3-1 Pro micro（meishi001 or 002）

meishi001 or 002 are compatible with pro micro.
<br>
meishi001または002はpro microに対応しています。
<br>
<br>
The pro micro is attached using a pin header on the back.
<br>
pro microは裏面にピンヘッダを使って取り付けます。
<br>
<br>
Please refer to the photo for the orientation of the pro micro.
<br>
pro microの向きは、写真を参考にしてください。
<br>
<br>

### 3-2 BLE Micro(meshi002)

meishi002 supports BLE micro.
<br>
meishi002はBLE microに対応しています。
<br>
<br>
The pro micro is attached using a pin header on the back.
<br>
pro microは裏面にピンヘッダを使って取り付けます。
<br>
<br>
Please refer to the photo for the orientation of the pro micro.
<br>
pro microの向きは、写真を参考にしてください。
<br>
<br>
Assemble the battery board set and attach it to the position shown in the photo.
<br>
電池基板セットを組み立てて、写真の位置に取り付けてください。
<br>
<br>

### 5　Test


Please write the firmware and check the operation.
<br>
ファームウェアを書き込んで、動作確認をしてください。
<br>

Install a switch or measure continuity with tweezers, etc.
<br>
スイッチを取り付けるか、ピンセット等で導通をはかるかを行います。
<br>
<br>

Firmware

[github](https://github.com/telzo2000/meishi001/tree/main/firmware)



[remap](https://remap-keys.app/)

<br>
If you have a switch that doesn't respond, use a hot soldering iron to warm up the switch socket,diode and pro micro terminals.
<br>
もし、反応しないスイッチがあったら、温めたハンダゴテで、そのスイッチソケットやダイオード、pro microの端子を温めてください。
<br>
Also make sure the diode is oriented correctly.
<br>
また、ダイオードの向きが正しいか確認してください。
<br>


<br><br><br>

Have a fun selfmade keyboard life!
<br>
楽しい自作キーボード生活を!<br>

![](img/img00005.jpg)

