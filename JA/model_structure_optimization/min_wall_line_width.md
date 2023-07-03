最小の壁線幅
====
薄いピースを印刷するとき、Curaはモデルの正確な幅に合わせて壁線の幅を調整します。また、Curaは壁線を減らすことも選択できます。この設定は、Curaが壁を削除するか既存の壁を薄くするかを決定する閾値を決定します。

![通常は線を広げてフィットさせます](../images/min_wall_line_width_0_34.png)
![最小線幅を減らすと、より多くの線を使用することを選択します](../images/min_wall_line_width_0_1.png)

壁の数が異なる
----
中央に単一の線があり、[Wall Distribution Count](wall_distribution_count.md)が1に設定されている場合、この設定はそのまま機能します。中央の線がある幅よりも薄くなると、他の線を広げるために削除されます。他のケースでは、計算はより複雑です。

これの正確な計算は複雑ですが、直感的な理解は有用です。実質的には、モデルの総幅を [通常の線幅](../resolution/wall_line_width.md) で割ることで、壁の数を特定できます。これは一部（例えば5.3の壁線幅）となる可能性があります。最小の壁線幅は、その小数部分（0.3の線幅）をとり、それが最小の壁線幅を超えると追加の壁を追加します。壁の数がわかれば、それに基づいて各線の幅をWall Distribution Countに従って決定します。

![最小の壁線幅は、新しい線を追加する閾値を左右にシフトします](../images/min_wall_line_width.svg)

これは実質的に、幅が調整される線が多ければ多いほど、線幅は最小の壁線幅が許可するほど極端にならないことを意味します。例えば、中央の2つの線が調整された場合、線幅は通常の線幅と最小の壁線幅の平均値以下にはなりません。

この設定は、[偶数](min_even_wall_line_width.md)と[奇数](min_odd_wall_line_width.md)の壁の数に対して別々に調整できます。壁が0のケースも別で、これは [最小フィーチャーサイズ](min_feature_size.md)の設定を使って調整できます。

調整
----
理論的には、この値を線幅の50%に設定することで、線幅が通常の線幅に最も近くなります。しかし、それよりも少し高く設定する方が良いです。ノズルサイズよりも広い線を印刷する方が、細い線を印刷するよりもプリンタにとっては楽であり、線の数が少なければ印刷も速くなります。

非常に粘度が高い材料を使用するか、印刷速度が速い場合は、最小の壁線幅を減らして、幅が広すぎる線を作らないようにするべきです。これらは、材料が十分に側面に流れ出る時間がない場合に印刷するのが難しいです。最小の壁線幅が高すぎると、壁がうまくくっつかず、印刷物が壊れやすくなります。

**この設定は通常の壁だけでなく、追加の皮膚壁、支持壁、充填壁、同心パターンにも適用されます。**

---

Minimum Wall Line Width
====
When printing thin pieces, Cura adjusts the width of wall lines to fit the exact width of the model. Cura can also decide to use fewer wall lines instead. This setting decides the threshold at which Cura decides to remove a wall instead of making the existing walls thinner.

![Normally the lines are made wider to fit](../images/min_wall_line_width_0_34.png)
![Reducing the minimum line width, it chooses to use more lines](../images/min_wall_line_width_0_1.png)

Different numbers of walls
----
If there is a single central line and the [Wall Distribution Count](wall_distribution_count.md) is set to 1, this setting functions exactly as it says. If the line in the middle gets thinner than a certain width, it gets removed in favour of making other lines wider. In other cases, the calculation is more complex.

The precise calculation of this is complex, but an intuitive understanding can be useful. Effectively, you can simply divide the total width of the model by the [ordinary line width](../resolution/wall_line_width.md) to arrive at a certain number of walls. This can be a fraction though (such as 5.3 wall line widths). The Minimum Wall Line Width takes just that fractional part (0.3 line widths) and adds an extra wall if it exceeds the Minimum Wall Line width. With the number of walls known, it then determines the width of each of the lines according to the Wall Distribution Count.

![Minimum Wall Line Width shifts the threshold of adding a new line left or right](../images/min_wall_line_width.svg)

Effectively this means that if there are more lines that get their width adjusted, the line width will never be as extreme as the Minimum Wall Line Width would allow. For example, if the middle two lines are adjusted, the line width will not drop below the average of the normal line width and the Minimum Wall Line Width.

The setting can separately be tuned for [even](min_even_wall_line_width.md) and [odd](min_odd_wall_line_width.md) number of walls. Having 0 walls is also a separate case, which can be tuned using the [Minimum Feature Size](min_feature_size.md) setting.

Tuning
----
In theory, setting this to 50% of the line width ensures that the line width stays closest to the ordinary line width. However it's better to stay a bit above that. It's easier for a printer to print lines wider than the nozzle size than it is to print thinner lines, and having fewer lines also means that the print will be faster.

With very viscous materials or when printing faster, the Minimum Wall Line Width should be decreased to prevent creating lines that are too wide. These are hard to print if the material doesn't get the time to flow out to the sides enough. If the Minimum Wall Line Width is too high, the walls don't stick well together which makes the print fragile.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**