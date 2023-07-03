スプリットミドルライン閾値
====
薄い部品を印刷する場合、Curaはモデルの正確な幅に合わせて壁のラインの幅を調整します。また、Curaは壁のラインを少なくすることも可能です。この設定は、パートの幅が増える際にCuraが中央の単一ラインを2つに分割する閾値です。これは[中心ラインが新たに追加される閾値](wall_add_middle_threshold.md)とは別に調整することができます。

この設定は[最小均一壁ライン幅](min_even_wall_line_width.md)と同じですが、異なる単位を使用します。この設定の単位は、部品の幅が中心線を二つに分割するほど増加する必要があるライン幅の分数です。幅の差は分割後の中央の二つの線間で割り当てられるため、小さな最小均一壁ライン幅は、奇数の壁を取り除く場合よりもはるかに小さなスプリットミドルライン閾値に相当します。

![中心線が合うように広げられている](../images/min_wall_line_width_0_34.png)
![この設定を減らすと、2つの線を代わりに使用します](../images/min_wall_line_width_even_0_1.png)

偶数ライン vs. 奇数ライン
----
この設定では、ラインが偶数になる特定の場合にラインを追加するための閾値を調整することができます。これは、中心に単一ラインではなく2つのラインがあるときです。これは中心のラインが2つのラインに分割するときを決定します。

中心ラインを分割するための閾値は、中心ラインを追加するための閾値とは異なる可能性があります。これは、これらのラインがどのように結合するかによるものです。偶数のラインは、端部が近づくことで端部で結合します。これらのラインとの一部重複があり、過剰押し出しが発生する可能性があります。これは、奇数の壁がある場合とは異なります：そのときは中央のラインがそのまま停止し、印刷に隙間を残します。 スプリットミドルライン閾値を減らすと、偶数から奇数のラインへの移行時の過剰押出しを減らすことができます。 Add Middle Line Thresholdを減らすと、奇数から偶数のラインへの移行時のギャップのサイズを減らすことができます。

中心ラインを追加するときに残される隙間は、ジョイントでの過剰押出しよりも最終結果でより視認性が高いため、スプリットミドルライン閾値を Add Middle Line Thresholdよりも少し高く設定するとよいかもしれません。

この設定を減らすと、以下の結果につながります：
* 2つのラインが一つに結合するところで重なりが少なくなります。
* 単一の中心ラインの最大幅が減少します。
* 細いラインが増え、よく押し出しが行われない可能性があります。
* より多くのラインが増え、印刷に時間がかかるようになります。

**この設定は通常の壁だけでなく、追加のスキン壁、サポート壁、インフィル壁、同心円パターンにも適用されます。**

---

Split Middle Line Threshold
====
When printing thin pieces, Cura adjusts the width of wall lines to fit the exact width of the model. Cura can also decide to use fewer wall lines instead. This setting is the threshold at which Cura will split a single line in the centre into two, when the width of the part increases. It can be adjusted separately from the [threshold at which a new centre line is added](wall_add_middle_threshold.md).

This setting is the same as the [Minimum Even Wall Line Width](min_even_wall_line_width.md), but uses a different unit. The unit of this setting is in fractions of a line width that the width of a part needs to increase to split the centre line into two. Because the difference in width is divided over the two lines in the middle after splitting, a smaller Minimum Even Wall Line Width is equivalent to a much smaller Split Middle Line Threshold than in the case of removing an odd wall.

![The centre line is made wider to fit](../images/min_wall_line_width_0_34.png)
![Reducing this setting, it uses two lines instead](../images/min_wall_line_width_even_0_1.png)

Even vs. Odd Lines
----
This setting allows adjusting the threshold for adding lines specifically when it becomes an even number of lines. This is when there are two lines in the centre rather than a single line. It determines when a line in the centre splits into two lines.

The threshold for splitting a middle line might be different from the threshold for adding a centre line because of the way they join together. Even lines join at their ends by making the ends come closer together. There is some overlap with these lines there, leading to overextrusion. This is different from when there is an odd number of walls: The line in the middle then just stops, leaving a gap in the print. Reducing the Split Middle Line Threshold reduces the overextrusion at the transitions from even to odd lines. Reducing the Add Middle Line Threshold reduces the size of the gap at the transitions from odd to even lines.

The gaps left when adding a centre line are more visible in the end result than a bit of overextrusion at a joint, so it could help to set the Split Middle Line Threshold a bit higher than the Add Middle Line Threshold.

Reducing this setting leads to:
* Reduced area of overlap where two lines join together to merge into one line.
* Reduced maximum width of single centre lines.
* Thinner lines, which may not extrude well.
* More lines, which take longer to print.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**