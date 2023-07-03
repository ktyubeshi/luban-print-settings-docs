外部壁の重複を補償する
====
### **説明**
この設定を有効にすると、ツールヘッドが薄いエリアを二度通過する必要がある場合、外部壁の押し出しが減少します。この方法により、薄い部分の両壁を重ならずに印刷できます。この設定は外部壁にのみ適用されます。

![線幅が減少する場所](../images/travel_compensate_overlapping_walls_enabled_schematic.svg)
![すべてのラインが全幅で押し出され、部品が広すぎる部分が作られます](../images/travel_compensate_overlapping_walls_enabled_disabled.png)
![ラインの半分が幅を減らし、より正確な印刷結果になります](../images/travel_compensate_overlapping_walls_enabled_enabled.png)

### **使用法**
重複する壁のライン幅は、重複するエリアの分だけ減少します。これにより、過剰な押し出しを補償し、寸法精度が向上します。

ただし、流れの速度が不均一になるという欠点があります。これは、一部で押し出しが足りなくなり、他の部分で押し出しが多くなる結果となります。また、流れの速度は、ノズルと押出機の設定の最小流量以下になる場合があり、流れが不均一になり、ビーズが形成されます。この影響を軽減するために、[最小壁の流れ](wall_min_flow.md)を設定することができます。これにより、最も薄い壁の一部が寸法精度を犠牲にして移動するようになります。

この設定はレイヤービューでは見づらくなる傾向があります。実際の印刷では、ライン間に境界はありません。レイヤービューはGコードのパスのみを表示し、実際には重複する他の壁によって材料が押し出されます。また、流速の微調整はノズルを通過する速度をそんなに速く調整できないため、実際の印刷には現れません。そのため、実際の印刷はレイヤービューが予測するよりも滑らかに出力されます。

---

Compensate Outer Wall Overlaps
====
### **Description**
With this setting enabled, the extrusion for outer walls is reduced when the toolhead has to go over a thin area twice. This way, both walls in the thin part are printed without overlapping. This setting applies only to the outer walls.

![Where the line width gets reduced](../images/travel_compensate_overlapping_walls_enabled_schematic.svg)
![All lines are extruded with their full width, creating a part that will be too wide](../images/travel_compensate_overlapping_walls_enabled_disabled.png)
![Half of the lines have reduced their width, resulting in a more accurate print](../images/travel_compensate_overlapping_walls_enabled_enabled.png)

### **Usage**
The line width of the wall that overlaps another wall is reduced by the overlapping area. This compensates for the overextrusion and increases dimensional accuracy.

However, the disadvantage is that the flow rate becomes less even, which causes underextrusion in some places and overextrusion in others. Also, the flow rate can be reduced below the minimum flow rate of the nozzle and extruder set-up, leading to inconsistent flow and beading. To reduce this effect, you can set the [Minimum Wall Flow](wall_min_flow.md) which will turn some of the thinnest walls into travel moves at the cost of dimensional accuracy.

This setting tends to look messier in layer view. In the actual print, there are no borders between lines. The layer view shows only the paths of the g-code, but in actuality the material gets pushed aside by the other wall that it overlaps with. Also, tiny reductions in flow will not manifest itself in the actual print since the flow rate through the nozzle can't adjust that fast. Therefore, the actual print will come out smoother than layer view predicts.