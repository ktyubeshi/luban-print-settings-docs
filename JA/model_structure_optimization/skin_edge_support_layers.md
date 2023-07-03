スキンエッジサポートレイヤー
====
凹状の形状を印刷する際、一部のトップスキンはインフィルの途中で終わります。この設定は、スキンのエッジをサポートするためにインフィルを通じて追加のラインを追加し、それが少しもたれるのを防ぎます。

![スキンのエッジはインフィルで十分にサポートされていません](../images/skin_edge_support_thickness_0.png)
![スキンのエッジの下のインフィルを通じて周囲が描かれます](../images/skin_edge_support_thickness.png)

インフィルの隙間を通る単一のラインはまだ垂れますので、ラインはサポートが必要なスキンのエッジの下の複数のレイヤーに描かれる場合があります。この設定は、このラインがスキンのエッジの下で描かれるレイヤーの数を設定します。あるいは、ラインが描かれるレイヤーの[厚さ](skin_edge_support_thickness.md)を調整することもできます。

レイヤーの数を増やすと、一般的に印刷に対して以下の効果があります：
* スキンのエッジがより良くサポートされ、スキンが一方から他方まで完全にブリッジすることができるため、トップ面が滑らかになります。
* 印刷時間がわずかに長くなり、材料の使用量が増えます。

インフィル率が高い場合、この設定はトップ表面にほとんど影響を与えず、インフィルで[過剰押出](../troubleshooting/overextrusion.md)を引き起こす可能性があります。その場合、レイヤーは0にしておくのが最善です。

---

Skin Edge Support Layers
====
When printing concave shapes, there will be some top skin that ends somewhere halfway through the infill. This setting adds an extra line through the infill to support the edge of the skin, so that it sags a little bit less.

![The edge of the skin is not well supported by infill](../images/skin_edge_support_thickness_0.png)
![A perimeter is drawn through the infill under the edge of the skin](../images/skin_edge_support_thickness.png)

A single line through the gaps in the infill will still sag, so the line may be drawn on multiple layers underneath the edge of the skin that needs supporting. This setting configures the number of layers through which this line will get drawn underneath the edge of the skin. Alternatively you can adjust the [thickness](skin_edge_support_thickness.md) of the layers through which the line gets drawn.

Increasing the number of layers will generally have the following effects on the print:
* The edge of the skin will get supported better, leading to a more smooth top side because the skin can bridge completely from one side to the other.
* It takes slightly longer to print, and will use more material.

If the infill rate is high, this setting will hardly have any effect on the top surface and could cause [overextrusion](../troubleshooting/overextrusion.md) in the infill. It is best left at 0 layers then.