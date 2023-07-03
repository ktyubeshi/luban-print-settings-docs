壁の移行フィルター距離
====
いくつの壁を使うかが異なる閾値周りに浮かぶようなモデルがある場合、実際の幅がそれほど変わらないにも関わらず壁の数が交互に切り替わってしまうことがあります。この交互は印刷品質を台無しにし、多くの流量変更を必要とし、さらに移動移動を追加します。この機能を使用すると、特定の距離内でバックアンドフォースに移行した場合、移行が削除されます。

![フィルターなしでは2と3の壁が交互になります](../images/wall_transition_filter_off.png)
![フィルターを使用すると、交互にならなくなります](../images/wall_transition_filter_on.png)

移行が削除されると、一時的にいくつかの線が広すぎたり狭すぎたりして、[最小壁線幅](min_wall_line_width.md)を超えてしまう可能性があります。移行がないので、理想的な数よりも低いか高い数の壁を使用し、それらの壁の幅が適切に調整されます。これは[壁の移行フィルターマージン](wall_transition_filter_deviation.md)まで許可されます。壁の幅があまりにも変化しすぎる場合、移行は削除されません。

このフィルターは、低解像度の3Dメッシュを使用した薄い部品に共通する問題を解決することを目的としています。3Dモデルは、平らな三角形から構成されており、曲線を正確に表現することはできませんが、それを近似することはできます。曲線には端があり、その間に平らな面があります。常に同じ幅を持つ曲線をモデリングする場合、外側の端が内側の端と一致することが重要です。一致しない場合、リングの幅がわずかに変化し、上記の画像で示されているような効果が引き起こされます。一致している場合、移行フィルターがそれがあまり影響を与えないようにすることができます。

距離を増やすことで、いくつかの場合に小さな線分を作成するのを防ぐことができます。これは印刷が早くなり、表面がより滑らかに見えるようになります。しかし、より多くの印刷物が極端な線幅を持つようになるため、ノズルからうまく押出できない可能性があります。薄い部品を低解像度で印刷する場合、距離を増やすことで品質を向上させることができます。困難な材料の場合は、安全な側にとどめる方が良いでしょう。

**この設定は現在ユーザーには表示されません。フィルターは[壁の移行フィルターマージン](wall_transition_filter_deviation.md)を使用して調整するだけです。通常の壁だけでなく、追加のスキン壁、サポート壁、インフィル壁、同心パターンにも影響します。**

wall_transition_filter_distance.md

----

Wall Transitioning Filter Distance
====
Some models have thin pieces hovering around the threshold where different numbers of walls get used. This could make the number of walls alternate back and forth even though the actual width of the piece doesn't vary much. The alternation ruins the print quality, requiring lots of flow changes and adding more travel moves. Using this feature, transitions are removed if it would have transitioned back and forth within a certain distance.

![Without filter, it alternates between 2 and 3 walls](../images/wall_transition_filter_off.png)
![With filter, it no longer alternates](../images/wall_transition_filter_on.png)

When a transition gets removed, then temporarily some of the lines can get too wide or too thin, exceeding the [Minimum Wall Line Width](min_wall_line_width.md). After all, there was a transition there to fit better with the width of the part. Without that transition, it will use a lower or higher amount of walls than would be ideal, and the width of those walls will be adjusted accordingly. This is allowed up to the [Wall Transitioning Filter Margin](wall_transition_filter_deviation.md). If the width of the walls varies too much, the transition is not removed.

This filter aims to solve a common problem with thin parts using low resolution 3D meshes. The 3D model, consisting of flat triangles, can't represent a curve exactly but only approximates it. The curve will have edges, with flat surfaces between them. When modelling a curved part with a constant width, it's important that the edges on the outside line up with the edges on the inside. If they don't, the width of the ring varies slightly, which can cause the effect shown above. If it does, the transitioning filter should prevent it from having too much of an effect.

Increasing the distance prevents creating small line segments in some cases. This is quicker to print and can make the surface look smoother. However it also causes more of the print to have extreme line widths, which may not extrude well out of your nozzle. When printing low-resolution models with thin pieces, increasing the distance may help to improve quality. With difficult materials, it's better to stay on the safe side.

**This setting is currently not visible to the user. The filter can only be adjusted using the [Wall Transitioning Filter Margin](wall_transition_filter_deviation.md). It affects not just the normal walls, but also extra skin walls, support walls, infill walls and concentric patterns.**