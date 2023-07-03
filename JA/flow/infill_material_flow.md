Infill Flow
====
### **説明**
この設定は、インフィルの流量を調整します。

### **使用方法**
インフィル中の流量を調整することは、押出速度や強度の問題を修正するための一時的な方法です。同じ効果は、[ライン間の距離](../infill/infill_line_distance.md)やインフィルの[ライン幅](../resolution/infill_line_width.md)を調整することで達成できますが、この設定の方が直感的かもしれません。

押出速度やインフィルの強度の問題は、主にインフィルパターンの交差や、インフィルと他の構造物との間の流量の変化が大きすぎることが原因です。この流量を調整するよりも、[インフィルパターン](../infill/infill_pattern.md)や[ライン幅](../resolution/infill_line_width.md)を調整する方が効果的かもしれません。互いに交差しないインフィルパターン、例えばジグザグを選択します。ライン幅を強度のために増やす必要があるが、流量が制限されている場合は、流量を増やす代わりに[インフィルマルチプライヤー](../infill/infill_multiplier.md)を使用するといいでしょう。

------------------------------------------------------------------------------------------------------------------
Infill Flow
====
### **Description**
This setting adjusts the flow rate for the infill. 


### **Usage**
Adjusting the flow rate during the infill is a stop gap method to fix problems with extrusion rate or strength. The same effect can be achieved by adjusting the [distance between lines](../infill/infill_line_distance.md) and [line width](../resolution/infill_line_width.md) of the infill, but this setting may be more intuitive.

Problems with extrusion rate or strength of the infill are mainly caused by crossings in the infill pattern, or too much of a change in flow rate between the infill and other structures. Rather than adjusting this flow rate, it may be more effective to adjust the [infill pattern](../infill/infill_pattern.md) or the [line width](../resolution/infill_line_width.md). Choose an infill pattern that doesn't cross itself, such as zigzag. If the line width needs to be increased for strength but is limited in the flow rate, it's a good idea to use the [infill multiplier](../infill/infill_multiplier.md) instead of increasing the flow.