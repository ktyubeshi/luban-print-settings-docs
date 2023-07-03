最小サポート領域
====
### **説明**
この設定は、サポートのピースに対する最小許容サイズを課します。特定のレイヤーでこの設定の値よりも小さな領域を持つサポートのピースがある場合、その場所でサポートは省略されます。

![面積のフィルタリングなし（最小面積は0）](../images/minimum_support_area_0.png)
![小さなサポートのピースは省かれます](../images/minimum_support_area_10.png)

細いサポートの柱は倒れやすいです。また、サポートなしでも十分に印刷可能な小さな機能をサポートする傾向があります。サポートが倒れると、印刷上に多くのブロブが残る可能性があります。したがって、これらの細い柱を省略する方が良いかもしれません。この設定は、柱の断面積によってサポートをフィルタリングする方法を提供します。

### **影響**
領域を大きくすると、印刷されるサポートの量が減少し、時間と材料の使用が少し減る。より重要なことに、サポートの柱が倒れる可能性が減るため、印刷の信頼性が向上します。しかし、印刷物の小さな特徴のためのサポートも取り除かれるため、そのような部分のオーバーハングの品質が悪化する可能性があります。

一部の形状では、これが厄介な副作用をもたらすことがあります。つまり、上部がしきい値の領域以下になるが下部ではない場合、サポートの上部を取り除く。これにより、通常はサポートが期待される部分がサポートされない状態になる可能性があります。

![アーチの先端は、その層の面積が小さすぎるためサポートされていません](../images/minimum_support_area_problem.png)

---

Minimum Support Area
====
### **Description**
This setting imposes a minimum allowed size for pieces of support. If a piece of support has less area than the value of this setting on a certain layer, the support is left out there.

![No filtering on area (minimum area is 0)](../images/minimum_support_area_0.png)
![Small pieces of support are left out](../images/minimum_support_area_10.png)

Thin pillars of support are like to topple over. They also tend to be supporting small features that would probably print fine without support. If the support topples, lots of blobs will be left on the print. So it may be better to leave these thin pillars out. This setting provides a way to filter support away by the cross sectional area of the pillar.

### **Influence**
Increasing the area will reduce the amount of support printed, reducing time and material usage slightly. More importantly, it improves reliability of the print since there is less chance of support pillars toppling over. However it will also remove support for small features in your print, so the overhang quality can worsen for those pieces.

For some shapes this can have the nasty side effect of removing the top part of support if the top part falls beneath the threshold area but the bottom part doesn't. This can leave parts unsupported that you'd normally expect to be supported.

![The tip of the arc is not supported because the area on those layers is too small](../images/minimum_support_area_problem.png) 