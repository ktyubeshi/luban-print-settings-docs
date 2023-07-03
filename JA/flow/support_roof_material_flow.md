サポートルーフフロー
====
### **説明**
この設定では、サポートルーフの流量を調整します。

### **使用法**
サポートルーフの流量は、サポートの残りの部分の流量とは別に調整することができます。

サポートルーフ中の流量を調整することは、押出し率やモデルとサポート間の接着力の問題を修正するための一時的な方法です。同じ効果は、サポートルーフの [線幅](../resolution/support_roof_line_width.md) や [線間隔](../support_adv/support_roof_line_distance.md)を調整することによっても達成できますが、流量を調整する方が直感的に理解しやすいかもしれません。

押出し率に問題がある場合は、[印刷速度](../speed/speed_support_roof.md)、[温度](material_print_temperature.md)、[線幅](../resolution/support_roof_line_width.md)を見る方が良いでしょう。おそらくサポートルーフの流量とレイヤー上の他の構造物の流量との間に大きな差があるのかもしれません。おそらく線幅が薄すぎて適切に押出すことができないのかもしれません。

インターフェースが[異なる材料](../support/support_interface_extruder_nr.md)で印刷されている場合、よくある問題は、インターフェースが印刷されている材料が適切に流れ始めるまでに十分な時間がないことです。これは、[プライムタワー](../dual/prime_tower_enable.md)を使用するか、[サポートルーフの面積](../support_adv/support_roof_offset.md)を増やすことで修正することができます。

サポートがモデルに強く接着する場合、[線幅](../resolution/support_roof_line_width.md)を調整する方が通常より効果的です。なぜなら、これによって同じサポート充填密度を達成するために、線が密着するようになるからです。

---

Support Roof Flow
====
### **Description**
This setting adjusts the flow rate for the support roof. 

### **Usage**
The flow rate for the support roof can be adjusted separately from the flow rate of the rest of the support.

Adjusting the flow rate during the support roof is a stop gap method to fix problems with extrusion rate or adhesion between the model and support. The same effect can be achieved by adjusting the [line width](../resolution/support_roof_line_width.md) or [line spacing](../support_adv/support_roof_line_distance.md) of the support roof, but adjusting the flow rate may be more intuitive.

If there is a problem with extrusion rate, it is better to look at the [printing speeds](../speed/speed_support_roof.md), [temperature](material_print_temperature.md) and [line width](../resolution/support_roof_line_width.md). Perhaps there is too great of a difference between the flow rate of the support roof and the other structures on the layer. Perhaps the line width is too thin to extrude properly. 

If the interface is printed with a [different material](../support/support_interface_extruder_nr.md), a common problem is that the material that the interface is printed with doesn't get enough time to start flowing properly. This can be fixed by using a [prime tower](../dual/prime_tower_enable.md) or increasing the [area of the support roof](../support_adv/support_roof_offset.md).

If the support sticks too well to the model, adjusting the [line width](../resolution/support_roof_line_width.md) will usually be more effective since it also causes the lines to be closer together to achieve the same support infill density.


