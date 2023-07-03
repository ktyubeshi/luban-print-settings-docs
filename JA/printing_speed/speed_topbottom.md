**上/下速度**
### **説明**
上/下速度とは、モデルの上面と下面を印刷する速度のことです。この設定は、通常の印刷速度とは別に設定できます。

![Various structures printed at different speeds](../images/speed_difference.png)

### **影響**
モデルの上面と下面をゆっくり印刷すると、以下の効果があります。
* 印刷時間が増加します。上面と下面には長い線があるため、加速度やジャークよりも速度が最大の影響を及ぼします。上面と下面は、合計印刷時間のかなりの量を占めます。
* 非常に平らなオーバーハングがある場合、オーバーハングの品質が向上します。まだ急斜面になっているオーバーハングには多くの影響がないため、そのオーバーハングのスキンが露出していないからです。フィラメントのストリングに張力を保つため、ゆっくりとオーバーハングを印刷します。
* オーバーハングと同様に、上面の品質も向上します。同じオーバーハング効果がインフィルの上に置かれた上面に適用されます。
* プリンター全体が一般的に振動が少なくなります。ビルドプレートの振動が少なければ、上面と下面がより良く見えます。

**この設定は、ビルドプレートの接着力には重大な影響を及ぼしません。[初期レイヤー印刷速度](speed_print_layer_0.md)は、最初のいくつかのレイヤーに使用されます。**

speed_topbottom.md

---------------

Top/Bottom Speed
====
### **Description**
Top/Bottom Speed refers to the speed at which the top and bottom side of the model is printed. This setting can be configured separately from the normal print speed.

![Various structures printed at different speeds](../images/speed_difference.png)

### **Influence**
Printing the top and bottom side of the model slowly will cause the following effects:
* The printing time increases, sometimes drastically. Since the top and bottom sides have long lines, the speed has the greatest effect on printing time, rather than acceleration and jerk. Top and bottom can be a significant part of the total printing time.
* The quality of overhang will be improved, if there is a very flat overhang. Overhang that is still sloped steeply is not affected much, since the skin in that overhang is not exposed then. Printing overhang more slowly keeps the tension on the strings of filament, allowing it to cool down longer.
* Similar to overhang, it will improve the quality of the top surface. The same overhang effect is applied to the way that the top surface rests on the infill.
* The printer will generally vibrate less. If the build plate vibrates less, the top and bottom will look better.

**This setting has no significant effect on the build plate adhesion. The [Initial Layer Print Speed](speed_print_layer_0.md) is used for the first few layers.**