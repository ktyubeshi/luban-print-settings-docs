サポートインフィルラインの方向
====
### **説明**
サポートパターンは通常、そのラインがサポートするもののほとんどに対して垂直になるように向きを決められます。このようにすることで、サポートされる素材がブリッジしなければならない距離を最小限にすることが可能です。この設定を使用すると、サポートラインの向きをカスタム化することができます。

![角度0°の場合](../images/support_infill_angle_0.png)
![30°と60°を交互](../images/support_infill_angles.png)

この設定では、複数の角度をカンマで区切って入力することができます。複数の角度が入力されると、Lubanはこれらの角度をレイヤーにわたって交互に切り替えます。

### **使い方**
[上部/下部ラインの方向](skin_angles.md)がモデルに対して調整されている場合、サポートの角度もそれに応じて調整して、下部側のラインに対してまだ垂直であるようにすることが賢明です。これにより、これらの下部ラインがサポートの上に適切に休まることを可能にします。ラインとジグザグの[サポートパターン](../support/support_pattern.md)では、サポートラインの間で直線が長くサポートが提供されない場所には特に重要です。

---

Support Infill Line Directions
====
### **Description**
The support pattern is normally oriented such that the lines are perpendicular to most things it supports. This way, the distance that the supported material has to bridge is minimised. With this setting, the orientation of the support lines can be customised.

![An angle of 0°](../images/support_infill_angle_0.png)
![Alternating between 30° and 60°](../images/support_infill_angles.png)

This setting allows multiple angles to be entered, separated by commas. When multiple angles are entered, Luban will alternate between these angles over the layers.

### **Usage**
If the [Top/Bottom Line Directions](skin_angles.md) have been adjusted for the model, it is wise to adjust the angle of the support accordingly, so that it is still perpendicular to the lines of the bottom side of the print. This allows these bottom lines to rest properly on the support, rather than falling in between support lines. This is particularly important for lines and zigzag [Support Patterns](../support/support_pattern.md) where there are long straights between the support lines that don't provide any support.
