外壁フロー
====
### **説明**
この設定は外壁の流量を調整します。

### **使い方**
外壁の流量は、内壁の流量とは別に調整することができます。

外壁の流量を調整することは、押し出し率や寸法精度の問題を解決するための一時しのぎの方法です。同様の効果は、[外壁ライン幅](../resolution/wall_line_width_0.md)および[外壁インセット](../shell/wall_0_inset.md)の設定を調整することでも達成できますが、この設定は最初に調整するのに直感的な方法であるかもしれません。

外壁の押し出し率に問題がある場合は、[印刷速度](../speed/speed_wall_0.md)と[印刷温度](material_print_temperature.md)を確認する方が良いです。 おそらく、素材がノズルから十分な勢いで出ないと、印刷速度を上げると助けになるかもしれません。 おそらく、ラインが適切に押し出すには細すぎるかもしれません。 おそらく、素材が冷たすぎるか暑すぎるかもしれません。

寸法精度に問題がある場合は、[ライン幅](../resolution/wall_line_width_0.md)、[水平方向の拡大](../shell/xy_offset.md)、および[印刷順序](../shell/outer_inset_first.md)を確認する方が良いです。

---

Outer Wall Flow
====
### **Description**
This setting adjusts the flow rate for the outer wall. 

### **Usage**
The flow rate for the outer wall can be adjusted separately from the flow rate of the inner walls.

Adjusting the flow rate during the outer wall is a stop gap method to fix problems with extrusion rate or dimensional accuracy. The same effect can also be achieved by adjusting the [Outer Wall Line Width](../resolution/wall_line_width_0.md) and [Outer Wall Inset](../shell/wall_0_inset.md) settings, but this setting could be a more intuitive way to tune initially.

If there is a problem with extrusion rate during the outer wall, it is better to look at the [printing speeds](../speed/speed_wall_0.md) and [printing temperature](material_print_temperature.md). Perhaps the material doesn't get enough momentum out the nozzle and a greater print speed could help. Perhaps the lines are too thin to extrude properly. Perhaps the material is too cool or too hot.

If there is a problem with dimensional accuracy, it is better to look at [line widths](../resolution/wall_line_width_0.md), [horizontal expansion](../shell/xy_offset.md) and the [printing order](../shell/outer_inset_first.md).


