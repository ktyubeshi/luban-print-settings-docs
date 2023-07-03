壁遷移フィルタマージン
====
いくつかのモデルでは、薄い部分が異なる数の壁が使われる閾値付近で浮遊しています。これにより、部分の実際の幅があまり変わらなくても、壁の数が前後に切り替わる可能性があります。この交互変化は印刷品質を低下させ、流量の変更や移動の追加を必要とします。この機能を使用すると、前後に遷移することがある場合は、遷移が除去されます。

遷移が除去されると、一時的に一部の線が広すぎるか狭すぎる場合があります。この設定は、線がどれだけ広くまたは狭くなることを許可するかに制限を設けることで、フィルタリングされる遷移を制限します。

![低マージンでは、2と3の壁の間で交互に変化します](../images/wall_transition_filter_off.png)
![マージンを大きくすると、もう交互に変化しません](../images/wall_transition_filter_on.png)

具体的には、線は[最小壁線幅](min_wall_line_width.md)よりもこのマージンだけ狭くなることが許可されます。これは、異なる数の壁の間での往復を防ぐためです。同様に、線はこのマージンだけ広がることも許可されます。これは、最小壁線幅の追加の壁が収まる余地がある場合でもです。

このフィルタは、低解像度の3Dメッシュを使用した薄い部分についての一般的な問題を解決することを目指しています。3次元モデルは、フラットな三角形で構成されており、曲線を正確に表現することはできませんが、それを近似します。曲線にはエッジがあり、その間にフラットな表面があります。一定幅の曲線部分をモデリングする際には、外側のエッジが内側のエッジと一致することが重要です。そうでないと、リングの幅がわずかに変動し、上記のような効果を引き起こす可能性があります。一致している場合、遷移フィルタはそれがあまりにも効果を持つのを防ぐべきです。

マージンを増やすことで、一部の場合に小さな線分を作成するのを防ぐことができます。これにより印刷速度が上がるだけでなく、表面が滑らかに見えることもあります。ただし、より極端な線幅が許容されるようになり、これがノズルからの押し出しを困難にする可能性があります。薄い部分のある低解像度モデルを印刷する際には、マージンを増やすことで品質を改善するかもしれません。難易度の高い素材を使用する場合には、安全側に留まる方が良いです。

**この設定は通常の壁だけでなく、追加のスキン壁、サポート壁、インフィル壁、同心パターンにも適用されます。**

---

Wall Transitioning Filter Margin
====
Some models have thin pieces hovering around the threshold where different numbers of walls get used. This could make the number of walls alternate back and forth even though the actual width of the piece doesn't vary much. The alternation ruins the print quality, requiring lots of flow changes and adding more travel moves. Using this feature, transitions are removed if it would have transitioned back and forth.

When a transition gets removed, then temporarily some of the lines can get too wide or too thin. This setting puts a limit on which transitions are filtered out by limiting how much wider or thinner the line is allowed to be.

![With a low margin, it alternates between 2 and 3 walls](../images/wall_transition_filter_off.png)
![With a higher margin, it no longer alternates](../images/wall_transition_filter_on.png)

To be precise, the lines are allowed to become thinner than the [Minimum Wall Line Width](min_wall_line_width.md) by this margin if that prevents going back and forth between different numbers of walls. Similarly, lines are also allowed to become slightly wider by this margin, even if an extra wall of the Minimum Wall Line Width could have fit in too.

This filter aims to solve a common problem with thin parts using low resolution 3D meshes. The 3D model, consisting of flat triangles, can't represent a curve exactly but only approximates it. The curve will have edges, with flat surfaces between them. When modelling a curved part with a constant width, it's important that the edges on the outside line up with the edges on the inside. If they don't, the width of the ring varies slightly, which can cause the effect shown above. If it does, the transitioning filter should prevent it from having too much of an effect.

Increasing the margin prevents creating small line segments in some cases. This is quicker to print and can make the surface look smoother. However it also allows for more extreme line widths, which may not extrude well out of your nozzle. When printing low-resolution models with thin pieces, increasing the margin may help to improve quality. With difficult materials, it's better to stay on the safe side.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**