木のサポート枝の直径角度
====
### **説明**
木のサポートの枝は上部に行くほど下部よりも細くなり、サポートがどれだけ高くなっても枝が安定していることを保証します。木のサポート枝の直径角度設定で、サポートが広がる速度を制御することができます。

![直径角度5°の枝の形状](../images/support_tree_branch_diameter_1_4mm_5.png)
![直径角度10°の枝の形状](../images/support_tree_branch_diameter_angle_10.png)

### **影響**
角度が大きければ大きいほど、特に高層モデルでは木の支持体の底部が広くなります。これはいくつかの効果を持ちます：
* 底部が広いほど、支持体が倒れにくくなります。これにより、木のサポートの信頼性が向上します。
* 底部が広いほど、材料と印刷時間を多く必要とします。
* サポートの角度は、枝が張り出すことができる最大[角度](support_tree_angle.md)に加わるため、非常に大きな値では木のサポートがいくつかのケースでより弱くなる可能性があります。
* 広い枝はメッシュの周りを移動するのが難しくなり、結果として、建造プレートから張り出し部分の一部に到達するのが難しくなります。その結果、サポートは建造プレートではなくモデル上で休む必要があるかもしれませんが、これによってスカーリングの量が増えます。
* Lubanが計算する木の衝突回避が難しくなり、スライス時間が増加します。これは[Tree Support Collision Resolution](support_tree_collision_resolution.md)設定を増やすことで対処できますが、それにより木の支持体の構造的な完全性が減少します。

一般的には、木のサポートが任意の高さで自己を支えられるだけの広さがありながらも不安定になりすぎないように、角度を設定したいところでしょう。

---

Tree Support Branch Diameter Angle
====
### **Description**
The branches of tree support are thinner towards the top than they are at the bottom, which ensures that the branches remain stable no matter how tall the support gets. With the Tree Support Branch Diameter Angle setting, you can control the rate at which the support gets wider.

![The shape of a branch with a diameter angle of 5°](../images/support_tree_branch_diameter_1_4mm_5.png)
![The shape of a branch with a diameter angle of 10°](../images/support_tree_branch_diameter_angle_10.png)

### **Influence**
The greater the angle, the wider the bottom of the tree support will become, especially with tall models. This has several effects:
* The wider bottom ensures that the support is harder to topple. This increases the reliability of the tree support.
* The wider bottom takes more material and time to print.
* The support angle adds up to the maximum [angle](support_tree_angle.md) at which the branches can overhang, so very high values may cause the tree support to be less sturdy as well in some cases.
* The wider branches have a harder time navigating around the mesh, making it harder to reach some parts of overhang from the build plate. As a result, the support may need to rest on the model instead of on the build plate, increasing the amount of scarring.
* The collision avoidance of the tree is harder to calculate for Luban, resulting in increased slicing time. This can be counteracted by increasing the [Tree Support Collision Resolution](support_tree_collision_resolution.md) setting, but that reduces the structural integrity of the tree support as well.

In general, you'll want the angle to be such that the tree support is just wide enough to support itself at any height without becoming too wobbly.