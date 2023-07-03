壁の重なりを補償する
====
### **説明**
この設定を有効にすると、ツールヘッドが薄い箇所を二度動かさなければならない場合に、壁の押し出し量が減少します。これにより、薄い部分の両壁が重ならずに印刷されます。この設定は、外壁または内壁に対して個別に有効にすることができます。

![線の幅が縮小する場所](../images/travel_compensate_overlapping_walls_enabled_schematic.svg)
![全ての線はその全幅で押し出され、部品が広すぎる結果となる](../images/travel_compensate_overlapping_walls_enabled_disabled.png)
![半数の線がその幅を縮小し、より正確な印刷が得られる](../images/travel_compensate_overlapping_walls_enabled_enabled.png)

二つの壁が狭い印刷部分で互いに重なっている場合、過度の押し出しが引き起こされます。補償する壁の重なりを有効にすると、壁の線幅が減少し、この過度の押し出しを防ぎ、より良い寸法精度を達成します。

### **使用法**
上記のように、この機能は寸法精度を向上させる傾向にあります。しかし、欠点としては、流量が均等ではなくなり、一部で押し出しが少なくなり、他の部分では押し出しが多くなります。また、流量がエクストルーダーの設定の最小流量以下に減少することがあり、流れが不均一になり、ビーズ（串珠）が形成されることがあります。この影響を軽減するために、寸法精度を犠牲にして、最薄の壁の一部を移動として設定することで、[最小壁流量](wall_min_flow.md)を設定できます。

この設定は、層ビューでは見づらくなりがちです。実際の印刷では、線の間に境界線はありません。レイヤー・ビューはGコードのパスを表示しますが、実際には重なっている別の壁によって材料が押しのけられます。また、微量の流量の減少は、ノズルを通る流量がそれほど迅速に調整できないため、実際の印刷では現れません。したがって、実際の印刷はレイヤービューが予測するよりも滑らかに出力されます。

---

Compensate Wall Overlaps
====
### **Description**
With this setting enabled, the extrusion for walls is reduced when the toolhead has to go over a thin area twice. This way, both walls in the thin part are printed without overlapping. The setting can be enabled for the outer or the inner walls separately.

![Where the line width gets reduced](../images/travel_compensate_overlapping_walls_enabled_schematic.svg)
![All lines are extruded with their full width, creating a part that will be too wide](../images/travel_compensate_overlapping_walls_enabled_disabled.png)
![Half of the lines have reduced their width, resulting in a more accurate print](../images/travel_compensate_overlapping_walls_enabled_enabled.png)

If two walls overlap with each other in a narrow print part, they will cause overextrusion. After you enable Compensate Wall Overlaps, the line width of a wall will be reduced, thus preventing this overextrusion and achieving a better dimensional accuracy.

### **Usage**
As described above, this feature tends to improve dimensional accuracy. However, the disadvantage is that the flow rate becomes less even, which causes underextrusion in some places and overextrusion in others. Also, the flow rate can be reduced below the minimum flow rate of the extruder set-up, leading to inconsistent flow and beading. To reduce this effect, you can set the [Minimum Wall Flow](wall_min_flow.md) which will turn some of the thinnest walls into travel moves at the cost of dimensional accuracy.

This setting tends to look messier in layer view. In the actual print, there are no borders between lines. The layer view shows only the paths of the g-code, but in actuality the material gets pushed aside by the other wall that it overlaps with. Also, tiny reductions in flow will not manifest itself in the actual print since the flow rate through the nozzle can't adjust that fast. Therefore, the actual print will come out smoother than layer view predicts.