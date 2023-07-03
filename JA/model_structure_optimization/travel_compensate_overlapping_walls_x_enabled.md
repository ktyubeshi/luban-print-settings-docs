内壁のオーバーラップを補償する
====
### **説明**
この設定を有効にすると、ヘッドが薄いエリアを二回通過する必要がある場合、内壁の押出し量が減少します。このようにして、薄い部分の両壁が重ならないように印刷されます。

この設定は内壁にのみ適用されます。内壁でのオーバーラップの補償は外側からはあまり見えません。

![全てのラインは全幅で押し出され、幅が広すぎる部品が作られます](../images/travel_compensate_overlapping_walls_x_enabled_disabled.png)
![ラインの半分が幅を縮小し、より正確なプリントが得られます](../images/travel_compensate_overlapping_walls_x_enabled_enabled.png)

### **使用法**
一方の壁が他の壁に重なる部分の壁の線幅は、重なる領域により減少します。これにより過剰押出しを補償し、寸法精度を向上させます。

ただし、欠点は、流量が均等でなくなり、一部の場所での押出し不足、他の場所での過剰押出しを引き起こすことです。さらに、流量は押出し器のセットアップの最小流量以下に減少する場合があり、流量やビーズが不規則になります。この効果を軽減するために、[最小壁流量](wall_min_flow.md)を設定することで、最薄の壁の一部を寸法精度を犠牲にしてトラベルムーブに変更できます。

この設定はレイヤービューでは乱雑に見えがちです。実際の印刷では、ラインの間に境界はありません。レイヤービューではg-codeのパスのみが表示されますが、実際には材料は重なっている他の壁に押し込まれます。また、微小な流量の減少は、ノズルを通過する流量をその速さで調整できないため、実印刷では現れません。したがって、実際の印刷はレイヤービューが予測するよりも滑らかに出力されます。

---

Compensate Inner Wall Overlaps
====
### **Description**
With this setting enabled, the extrusion for inner walls is reduced when the toolhead has to go over a thin area twice. This way, both walls in the thin part are printed without overlapping. 

This setting applies only to the inner walls. Compensating for overlap in the inner walls is less visible on the outside.

![All lines are extruded with their full width, creating a part that will be too wide](../images/travel_compensate_overlapping_walls_x_enabled_disabled.png)
![Half of the lines have reduced their width, resulting in a more accurate print](../images/travel_compensate_overlapping_walls_x_enabled_enabled.png)

### **Usage**
The line width of the wall that overlaps another wall is reduced by the overlapping area. This compensates for the overextrusion and increases dimensional accuracy.

However, the disadvantage is that the flow rate becomes less even, which causes underextrusion in some places and overextrusion in others. Also, the flow rate can be reduced below the minimum flow rate of the extruder set-up, leading to inconsistent flow and beading. To reduce this effect, you can set the [Minimum Wall Flow](wall_min_flow.md) which will turn some of the thinnest walls into travel moves at the cost of dimensional accuracy.

This setting tends to look messier in layer view. In the actual print, there are no borders between lines. The layer view shows only the paths of the g-code, but in actuality the material gets pushed aside by the other wall that it overlaps with. Also, tiny reductions in flow will not manifest itself in the actual print since the flow rate through the nozzle can't adjust that fast. Therefore, the actual print will come out smoother than layer view predicts.