ツリーサポートの枝の直径
====
### **説明**
この設定は、ツリーサポートの末端の枝の直径を決定します。

![直径1.4mmの枝の形状](../images/support_tree_branch_diameter_1_4mm_5.png)
![直径5mmの枝の形状](../images/support_tree_branch_diameter_5mm.png)

通常のサポートとは異なり、ツリーサポートは大きな平らな屋根を持つモデルをサポートしません。代わりに、ツリーサポートは疎らな小枝でモデルをサポートし、多くの小さな接触点を作り出します。ツリーサポートの枝の直径を設定することで、実際には接触点の直径、すなわちツリーの枝の頂点の直径を調整しています。

ツリーのように、ツリーサポートの枝の底部は広く、[ツリーサポートの枝の直径の角度](support_tree_branch_diameter_angle.md) 設定に基づいて上部に向かって次第に細くなります。

### **影響**
枝が広いほど安定します。これにより、ツリーが倒れる可能性が減ります。

しかし、枝が広いと取り除くのが難しくなります。また、枝が広いとモデルの周りを移動するのが難しくなるため、サポートがモデル上に乗っている部分がビルドプレート上に乗っている部分よりも多くなる可能性があります。その結果、サポート構造を取り除いた後にモデルに多くの傷が付く可能性があります。

---

Tree Support Branch Diameter
====
### **Description**
This setting determines the diameter of very end branches of the tree support.

![The shape of a branch with a diameter of 1.4mm](../images/support_tree_branch_diameter_1_4mm_5.png)
![The shape of a branch with a diameter of 5mm](../images/support_tree_branch_diameter_5mm.png)

Unlike Normal Support, the Tree Support does not support the model with a large flat roof. Instead, the tree support supports the model with sparse small branches, thus creating a lot of small contact points. By setting Tree Support Branch Diameter, you actually adjust the diameter of each contact point, namely the top of the tree's branches. 

Like that of a tree, the bottom of the tree support's branches is wider and towards the top it gradually becomes thinner based on the [Tree Support Branch Diameter Angle](support_tree_branch_diameter_angle.md) setting. 

### **Influence**
Wider branches are more stable, reducing the chance that the tree topples over. 

However, wider branches will be hard to remove. Besides, wider branches will also have a harder time navigating around your model. This may cause more of the support to be resting on the model rather than on the build plate. As a result, your model may have more scarring after removal of the support structures.