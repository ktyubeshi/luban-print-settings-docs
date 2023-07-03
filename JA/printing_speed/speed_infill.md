Infill Speed（インフィルスピード）
====
### **説明**
Infill Speedは、インフィル材料が印刷される速度を指します。この設定は、通常の印刷速度とは別に設定できます。

![Various structures printed at different speeds](../images/speed_difference.png)

### **使用法**
インフィルの視覚的な品質は通常重要ではありませんので、インフィルをかなりの高速で印刷して時間を節約できます。一方、Infill Speedを高めると、ノズルが壁により多く揺れ動くため、インフィルが壁を通してより明るくなります。

Infill Speedを高い値に設定すると、流量の変化が大きくなります。特に、[Infill Layer Thickness](../infill/infill_sparse_thickness.md)のような設定と組み合わせると、インフィルに必要な流量と残りの印刷に必要な流量との比率が非常に大きくなります。ノズルを介して流量を調整する際に大きな遅延があるため、インフィルを残りと比べて速くすると、流量が正確でなくなる可能性があります。


speed_infill.md

----


Infill Speed
====
### **Description**
Infill Speed refers to the speed at which the infill material is printed. This setting can be configured separately from the normal print speed.

![Various structures printed at different speeds](../images/speed_difference.png)

### **Usage**
The visual quality of infill is not usually important, so the infill can be printed at a fairly high speed to save time. On the other hand, increasing the Infill Speed also makes the infill shine through the walls more, because the nozzle will wobble more into the walls.

Setting the Infill Speed at a high value can induce a significant flow change. Especially when combined with settings like [Infill Layer Thickness](../infill/infill_sparse_thickness.md), the difference in the flow rate required for the infill and the flow rate required for the rest of the print can be very large. There is a large delay when adjusting the flow rate through the nozzle, so if the infill is made too fast compared to the rest, the flow could be inaccurate.