スパイラライズアウターコンター
====
### **説明**
モデルをスパイラライズすると、モデルはインフィルやトップを得ることはありません。壁と底部だけが得られます。重要な点として、ノズルの高さはレイヤーの進行とともに徐々に増加します。これにより、モデルの輪郭に沿った螺旋が形成されます。ノズルが徐々に次のレイヤーに向かって上昇していくため、一つのレイヤーから別のレイヤーへの工具頭の大きな上昇はありません。

レイヤーごとに印刷する場合、ノズルは通常、一つのレイヤーから次のレイヤーに移動する必要があります。この動きは、ノズルがXY方向でほんの一瞬ほぼ静止することを意味し、これにより表面にZシームと呼ばれる継ぎ目が残ります。モデルをスパイラライズすることでこれを防ぐことができます。

### **使用法**
スパイラライズモードは、多くのスライサーで一般的です。これは「花瓶モード」などとも呼ばれることがあります、なぜならそれは花瓶をプリントするのに良い方法だからです。スパイラライズアウターコンターには以下の効果があります：
* 非常に高速に印刷します。
* 表面が非常に滑らかになります。次のレイヤーに移動したところにもう[Zシーム](../troubleshooting/seam.md)はありません。
* モデルは非常に強くはありません。モデルが大きすぎると、[ワーピング](../troubleshooting/warping.md)により割れる傾向があります。
* 大きな場合、印刷物を完全に水密にするのは難しいです。

スパイラライズは、多くの水平面を持つ印刷物には適していません。それは全くオーバーハングを扱わず、トップ面を印刷しないので、何もHorizontal面に寄りかかることはできません。また、レイヤーに複数のパーツがある場合にも適していません。

---

Spiralize Outer Contour
====
### **Description**
When spiralising the model, the model will not get any infill or any tops. It will only get one wall and a bottom. Crucially, height of the nozzle will gradually increase over the course of a layer. This way a spiral is created following the contour of the model. There will be no significant toolhead lift from one layer to another, because the nozzle is gradually moving up towards the next layer.

When printing layer by layer, the nozzle normally needs to move from one layer to the next. This movement causes the nozzle to stand almost still in XY direction for a fraction of a second, which leaves a seam on the surface called the Z seam. Spiralising the model can prevent that.

### **Usage**
Spiralize mode is common among many slicers. It is also known as "vase mode" sometimes, because it is a good way to print vases. Spiralize Outer Contour has the following effects:
* Prints extremely fast.
* The surface becomes very smooth. There is no [Z seam](../troubleshooting/seam.md) any more where it moved to the next layer.
* The model will not be very strong. If the model is too big, it tends to split due to [warping](../troubleshooting/warping.md).
* It is difficult to get the print to be watertight if it is large.

Spiralize will not work well with prints with many horizontal surfaces. It doesn't handle overhangs at all, and doesn't print top surfaces so nothing will be able to lean on a horizontal surface. It also doesn't work well when there are multiple parts on a layer.