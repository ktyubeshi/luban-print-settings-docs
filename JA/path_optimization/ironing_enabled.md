アイロンを有効にする
====
### **説明**
アイロンを使用すると、プリンターはトップ面をさらに滑らかにするために、もう一度パスを行います。この追加のパスでは、非常に小さなラインを非常にゆっくりと印刷します。

![通常のプリント、上側から見た](../images/ironing_enabled_disabled.png)
![アイロニングが有効になっている場合、上部の細いラインに注意してください。](../images/ironing_enabled_enabled.png)

### **影響**
アイロンは、印刷物のトップ面の上にラインパターンを印刷します。これには2つの主な利点があります：
* ホットノズルを何度も通過させることで、上面を再び溶かします。これが「アイロン」という名前の由来です。移動速度がとても遅く、ラインの幅がとても小さいため、ノズルは表面を大幅に加熱します。ノズルの平らな部分がそれをストロークして滑らかにします。
* トップ面の隙間を埋めます。アイロニングの動きは、レイヤー自体と同じ高さで行われます。完全なレイヤーよりも流れが少ないですが、それでもある程度の流れがあります。理論的には、この流れはどこにも行くところがないはずですが、実際にはノズルチャンバー内に圧力を保つでしょう。ノズルが表面の凹凸部分を通過するたびに、ノズル内の材料がその隙間に流れ込みます。

しかしながら、アイロニングにはいくつかの欠点もあります：
* 印刷時間が大幅に増加します。
* アイロニングパターンが中断すると（異なるパーツに移動する必要があるため）、異なるアイロン部分の間に可視のラインが残ります。これは、適切な[アイロンパターン](ironing_pattern.md)を選択することで場合によっては回避できます。
* 斜面、または詳細の多いトップ面は、アイロニングされる可能性もあります。これは地形効果を増大させます。レイヤー間の境界はより顕著になります。これは[最上層のみアイロン](ironing_only_highest_layer.md)を有効にすることで防ぐことができます。

---

Enable Ironing
====
### **Description**
Ironing causes the printer to do another pass over the top surface in order to make it extra smooth. This extra pass prints very small lines extremely slow.

![A normal print, viewed from the top side](../images/ironing_enabled_disabled.png)
![With ironing enabled, notice the thin lines on top.](../images/ironing_enabled_enabled.png)

### **Influence**
Ironing will print a line pattern on top of the top surface of your print. This has two major beneficial effects:
* It melts the top surface again by going over it multiple times with a hot nozzle. This is where the name "Ironing" comes from. Because the moving speed is so low and the line width is so small, the nozzle will heat up the surface significantly. The flat part of the nozzle then strokes it smooth.
* It fills in gaps in the top surface. The ironing motion is done at the same height as the layer itself. It has less flow than a full layer, but still has some flow. In theory, this flow has nowhere to go, but in practice it will keep pressure inside the nozzle chamber. Whenever the nozzle passes over an unevenness in the surface, the material in the nozzle will flow into that gap.

However, ironing comes with some disadvantages as well:
* It increases printing time significantly.
* If the ironing pattern has interruptions (because it has to travel to different parts), it will leave a visible line between two different ironed parts. This can sometimes be avoided by selecting a proper [Ironing Pattern](ironing_pattern.md).
* Sloped surfaces, or top surfaces with lots of detail, may get ironed as well, which increases the topography effect. The borders between the layers will become more pronounced. This can be prevented by enabling [Iron Only Highest Layer](ironing_only_highest_layer.md).