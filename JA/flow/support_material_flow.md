サポートフロー
====
### **説明**
この設定は、サポートの流れの速度を調整します。

### **使用方法**
サポートの流れの速度は、プリント全体の流れの速度とは別に調整することができます。

サポート中の流れの速度を調整することは、押出速度やサポートとプリントとの接着性を修正するための一時的な方法です。同様の効果は、サポートの[線幅](../resolution/support_line_width.md)や[線間距離](../support/support_line_distance.md)を調整することでも達成できますが、流れを調整する方が直感的かもしれません。

サポート中の押出速度や強度に問題がある場合は、[印刷速度](../speed/speed_support.md)や[温度](material_print_temperature.md)を見ることが良いでしょう。おそらくサポートと他の構造物との間の流れの差が大きすぎて、適切に押出すことができないかもしれません。サポートの流れの速度に関連するもう一つの一般的な問題は、[サポートパターン](../support/support_pattern.md)の中に交差点が多すぎることです。交差しないパターン、例えばGyroidやZigzagを選択することが役立つかもしれません。

---

Support Flow
====
### **Description**
This setting adjusts the flow rate for the support. 

### **Usage**
The flow rate for the support can be adjusted separately from the flow rate of the rest of the print.

Adjusting the flow rate during the support is a stop gap method to fix problems with extrusion rate or the adhesion between the support and the print. The same effect can be achieved by adjusting the [line width](../resolution/support_line_width.md) or [line spacing](../support/support_line_distance.md) of the support, but adjusting the flow may be more intuitive.

If there is a problem with extrusion rate or strength during the support, it is better to look at the [printing speeds](../speed/speed_support.md) and [temperature](material_print_temperature.md). Perhaps the flow difference between the support and the other structures is too great to properly extrude. Another common issue with the flow rate of support is that there are too many crossings in the [support pattern](../support/support_pattern.md). It could help to choose a pattern that doesn't cross itself, such as Gyroid or Zigzag.

