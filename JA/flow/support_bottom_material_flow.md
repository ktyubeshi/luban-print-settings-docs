サポートフロアフロー
====
### **説明**
この設定は、サポートフロアのフローレートを調整します。

### **使用法**
サポートフロアのフローレートは、その他のサポートのフローレートとは別に調整することができます。

サポート底部でのフローレートの調整は、押出量やモデルとサポートの間の接着問題を修正するための一時的な方法です。同じ効果は、サポートフロアの[ライン幅](../resolution/support_bottom_line_width.md)や[ライン間隔](../support_adv/support_bottom_line_distance.md)を調整することで得られますが、フローレートを調整する方が直感的かもしれません。

押出量に問題がある場合、[印刷速度](../speed/speed_support_bottom.md)、[温度](material_print_temperature.md)、および[ライン幅](../resolution/support_bottom_line_width.md)を見る方が良いかもしれません。おそらく、サポートフロアのフローレートと層の他の構造体との間に大きな差があるのかもしれません。また、ライン幅が細すぎて適切に押し出すことができないかもしれません。

インターフェースが[異なる材料](../support/support_interface_extruder_nr.md)で印刷される場合、一般的な問題は、インターフェースが印刷される材料が適切に流れ始めるのに十分な時間がないことです。これは、[プライムタワー](../dual/prime_tower_enable.md)を使用するか、[サポートフロアの面積](../support_adv/support_bottom_offset.md)を増やすことで修正できます。

---

Support Floor Flow
====
### **Description**
This setting adjusts the flow rate for the support floor. 

### **Usage**
The flow rate for the support floor can be adjusted separately from the flow rate of the rest of the support.

Adjusting the flow rate during the support bottom is a stop gap method to fix problems with extrusion rate or adhesion between the model and support. The same effect can be achieved by adjusting the [line width](../resolution/support_bottom_line_width.md) or [line spacing](../support_adv/support_bottom_line_distance.md) of the support floor, but adjusting the flow rate may be more intuitive.

If there is a problem with extrusion rate, it is better to look at the [printing speeds](../speed/speed_support_bottom.md), [temperature](material_print_temperature.md) and [line width](../resolution/support_bottom_line_width.md). Perhaps there is too great of a difference between the flow rate of the support floor and the other structures on the layer. Perhaps the line width is too thin to extrude properly. 

If the interface is printed with a [different material](../support/support_interface_extruder_nr.md), a common problem is that the material that the interface is printed with doesn't get enough time to start flowing properly. This can be fixed by using a [prime tower](../dual/prime_tower_enable.md) or increasing the [area of the support floor](../support_adv/support_bottom_offset.md).


