# Build guide

## Parts list


| No. | Patrs | Quantity | remarks | Suppliers | Cost |
|--|--|--|--|--|--|
|番号|名前|数|備考|調達先|参考価格（送料込）|<br>
|1|PCB|1|meishi size keyboard|[elecrow](https://www.elecrow.com)<br>[JLCPCB](https://jlcpcb.com)<br>[ALLPCB](https://www.allpcb.com)|５枚で10ドル程度|<br>
|2|pro micro|2|ピンヘッダも別途購入|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|価格変動中|
|3|Diode<br>ダイオード|45|リードタイプでもSMDでも可|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|100個で220円程度から|
|4|タクトスイッチ|46|２本足のもの|[遊舎工房](https://yushakobo.jp)<br>[Talp Keyboard](https://talpkeyboard.net)<br>[Daily Craft Keyboard](https://shop.dailycraft.jp)等|１個11円程度|

In addition, you will need a TRRS cable, USB cable, keycaps, etc.
<br>
この他に、USBケーブルが必要です。
<br>

## Firmware

###  QMK_FIRMWARE
[Here](https://github.com/telzo2000/meishi001/tree/main/firmware)

<br>
[remap](https://remap-keys.app/catalog/LnDFLEBLKVYKpWCBQks4)

<br>

## Build 

### 1 Diode soldering


Insert the diode from the front side of the PCB and solder it to the back side.
<br>
PCBの表面からダイオードを差して、裏面にハンダ付けをします。
<br>

There are lead type and SMD diodes.
<br>
ダイオードはリードタイプか、SMDがあります。
<br>
Here, we will explain the lead type soldering.
<br>
ここでは、リードタイプのハンダ付けの説明をします。
<br>
Use a lead bender to bend the legs of the diode.
<br>
リードベンダーを使い、ダイオードの足を曲げます。
<br>


Insert the diode into the board.
<br>
ダイオードを基板に挿しこみます。
<br>

Please pay attention to the orientation of the diode.
<br>
ダイオードの向きに注意してください。
<br>


Secure the diode with masking tape, then face up.
<br>
マスキングテープでダイオードを固定してから、表面を上にします。
<br>
Solder the protruding legs.
<br>
はみ出ている足部分に、ハンダ付けをします。
<br>
After soldering, use nippers to cut off the protruding legs.
<br>
はんだ付けが終わったら、はみ出ている足をニッパーで切り取ってください。
<br>

[８倍速　Diodeハンダ付け動画](https://youtu.be/Yaodh2-XxV4)


<br>
<br>

### 2 Tactswitch soldering

Insert the tactswitch on the surface.
<br>
表面にタクトスイッチを挿しこみます。
<br>
Solder the legs of the tactswitch from the back.
<br>
裏面からタクトスイッチの足をハンダ付けします。
<br>

#### 3 pro micro

The side on which the parts of the pro micro are mounted is the surface. The opposite side is the back side.
<br>
pro microの部品が実装されている面を表面とします。反対の面を裏面とします。
<br>

The pro micro attaches to the back side of the PCB.
<br>
pro microは、PCBの裏面に取り付けます。
<br>
At that time, attach it so that the front surface of the pro micro and the back surface of the PCB face each other.
<br>
その際、pro microの表面とPCBの裏面が向かい合うように取り付けます。
<br>
Please use the cons through while considering removal. If not, please solder it with a pin header.
<br>
取り外しを考えるながら、コンスルーを利用してください。　そうでなければ、ピンヘッダでハンダ付けしてください。
<br>
Just install the firmware and you're done. If you like, print the case with a 3D printer and attach it.
<br>
あとはファームウェアを入れて完成です。お好みで3Dプリンタでケースを印刷して付けてください。
<br>






