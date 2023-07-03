インフィルラインの距離
====
### **説明**
[インフィル密度](infill_sparse_density.md)をパーセンテージで設定する他に、隣接するインフィルライン間の距離を設定することでインフィル密度を調整することもできます。インフィルライン間の距離を大きくすると、インフィル密度は低くなります。

通常、インフィルラインの距離は、選択したインフィルパターンとライン幅に依存して、希望のインフィル密度から計算されます。

![ライン間距離4mm、密度20%結果](../images/infill_sparse_density_high.png)
![ライン間距離8mm、密度10%結果](../images/infill_sparse_density_low.png)

### **使用法**
インフィルラインの距離は、インフィル密度を見るもう一つの視点を提供します。インフィルの上側では、上層のラインは一つのインフィルラインから次へと移動しなければなりません。インフィルラインの距離を縮小すると、ブリッジの距離が短くなり、上面の品質が向上します。

インフィル密度を増加させる（ライン間距離を縮小する）と、印刷に大きな影響が出ます。具体的には、次のとおりです：

* 印刷品がより強くなります。
* 上面がよりよくサポートされ、滑らかになり、水密性が向上します。
* ピローイング効果が軽減され、熱のポケットが小さくなります。
* 印刷品にはより多くの材料が必要となるため、その結果、重くなります。
* 印刷にはより長い時間がかかります。

---

Infill Line Distance
====
### **Description**
Besides setting the [Infill Density](infill_sparse_density.md) as a percentage, you can also adjust infill density by setting the distance between adjacent infill lines. A greater distance between infill lines will result in a lower infill density.

Normally the Infill Line Distance is computed from the desired infill density, depending on the selected infill pattern and line width.

![4mm distance between lines, resulting in 20% density](../images/infill_sparse_density_high.png)
![8mm distance between lines, resulting in 10% density](../images/infill_sparse_density_low.png)

### **Usage**
Infill Line Distance provides another perspective to look at infill density. On the top of the infill, the top layer lines have to cross from one infill line to the next. Reducing the Infill Line Distance reduces the bridged distance and improves the quality of the top surfaces.

Increasing the infill density (by reducing the line distance) has a big effect on your print, namely:
* Your print will be stronger.
* The top surface will be supported better, becoming smoother and more watertight.
* The pillowing effect will be reduced because the pockets of heat will be smaller.
* Your print will require more material and as a result will be heavier.
* It takes longer time to print.