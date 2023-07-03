ツリーサポート枝角度
====
### **説明**
この設定は、ツリーサポートの枝が許される最大のオーバーハング角度を決定します。角度を大きくすると、枝はもっと水平に印刷することができ、それによってさらに遠くに届くことが可能になります。 枝の角度を小さくすると、枝はより垂直になります。

![枝角度20°の例](../images/support_tree_angle_20.png)
![枝角度40°の例](../images/support_tree_angle_40.png)

### **影響**
ツリーサポート枝角度を大きくすると、枝はより大きなオーバーハング角度を持つことが可能になります。これにより、障害物のまわりをより遠くに届くことができ、サポートをビルドプレートにより頻繁に載せることができ、モデル上に載せることが少なくなります。

ツリーサポートの枝角度を大きくすることの最も重要な影響には、以下のようなものがあります：
* キズの軽減。モデルに対して支持が必要な部分が少なくなります。もし[サポート配置](../support/support_type.md)がビルドプレートに接触に設定されている場合、モデルの部分がより多く支持可能になります。
* 印刷時間と材料の使用量の削減。枝はより高い位置で分岐することができます。枝はオーバーハング全体に届くことができるようになるまさにその時に分岐します。
* 信頼性の削減。オーバーハング角度が大きすぎると、サポートは大幅に弱まり、サポートが折れたり転倒する可能性が増えます。

### **使用方法**
大きな枝角度は、[ツリーサポート衝突解決](support_tree_collision_resolution.md)設定の低い値と併用するのが最適です。これにより、衝突回避のためにツリーの位置がシフトすることが減ります。これは、衝突距離が調整されたときに、オーバーハング距離が大きすぎるのを防ぎます。

---

Tree Support Branch Angle
====
### **Description**
This setting determines the maximum overhang angle that the branches of tree support are allowed to make. If the angle is increased, the branches can be printed more horizontally, allowing them to reach farther. Reducing the branch angle will make the branches more vertical.

![A branch angle of 20°](../images/support_tree_angle_20.png)
![A branch angle of 40°](../images/support_tree_angle_40.png)

### **Influence**
If the Tree Support Branch Angle is increased, the branches will be allowed to have greater overhang angles. They can reach farther around obstacles, allowing the support to rest on the build plate more often, rather than on the model.

The most important effects of increasing the branch angle for tree support include:
* Reduced scarring. Less support needs to rest on the model. If [Support Placement](../support/support_type.md) is set to Touching Buildplate, more of the model can be supported.
* Reduced printing time and material usage. The branches can split off at higher elevations. The branches are split off just in time to be able to reach all of the overhang.
* Reduced reliability. If the overhang angle becomes too great, the support will be greatly weakened, increasing the chance that the support breaks or tumbles over.

### **Usage**
Large branch angles are best combined with low values for the [Tree Support Collision Resolution](support_tree_collision_resolution.md) setting. This will reduce the shifts in the tree's positions due to collision avoidance. That prevents the overhang distance from growing too big when the collision distance is adjusted.