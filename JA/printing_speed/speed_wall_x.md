内壁速度
====
### **説明**
内壁速度とは、内壁を印刷する速度のことです。この設定は、通常の印刷速度と外壁とは別に設定できます。

![Various structures printed at different speeds](../images/speed_difference.png)

### **使用法**
内壁は、外壁よりも視覚的な品質にとって重要ではありません。しかし、[外壁が内壁の後に印刷される場合](../shell/outer_inset_first.md)、外壁の位置が変わり、外壁の材料が外に押し出される可能性があります。また、外壁が最初に印刷される場合、外壁が直接押し出される可能性があります。したがって、内壁を正確に印刷することが重要ですが、時間を節約するために外壁よりも少し早く印刷することができます。

内壁の速度を低下させると、この構造物を印刷する際の振動が減少し、リングが減少します。また、ツールヘッド上のファンが材料を冷却する時間が増えるため、オーバーハングも改善されます。

しかし、内壁の印刷速度が低すぎると、流量変化が大きすぎるリスクがあります。ノズルが突然ゆっくりと押し出す必要がある場合、ノズル室内の圧力が低下するため、壁の始まりでツールヘッドが過剰押出しを行います。

内壁も印刷時間の大部分を占めるため、内壁の印刷速度を低下させると、印刷時間が大幅に増加します。

speed_wall_x.md

-----------

Inner Wall Speed
====
### **Description**
Inner Wall Speed refers to the speed at which the inner walls are printed. This setting can be configured separately from the normal print speed and the outer wall.

![Various structures printed at different speeds](../images/speed_difference.png)

### **Usage**
The inner walls are less important for visual quality than the outer walls. However they will influence the placement of the outer walls, causing the material for the outer walls to be pushed outside if the [outer wall is printed after the inner walls](../shell/outer_inset_first.md), or directly pushing the outer wall out if the outer wall is printed first. Therefore, it is important to print the inner walls accurately, but they can be printed a bit faster than the outer walls in order to save time.

Reducing the speed of the inner wall will reduce vibrations while printing this structure, which reduces ringing. It also improves overhang, because the fans on the toolhead get more time to cool the material down while it's still being held taut by the nozzle.

If the inner wall printing speed is too low however, there is a risk of introducing too great of a flow change. If the nozzle suddenly has to extrude much more slowly, it will extrude a lot of material for a while. During this process, the pressure in the nozzle chamber drops, so at the beginning of the wall the toolhead will overextrude.

The inner walls are also a significant part of the printing time, so reducing the speed at which the inner walls are printed will drastically increase the printing time.