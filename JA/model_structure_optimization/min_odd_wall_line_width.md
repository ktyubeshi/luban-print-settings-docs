最小の奇数壁ライン幅
====
細いパーツを印刷する際、Curaはモデルの正確な幅に合わせて壁ラインの幅を調整します。Curaは、壁ラインを少なくすることも決定できます。この設定は、Curaが中央のラインを削除するしきい値です。これは、[中央の2つのラインが結合するしきい値](min_even_wall_line_width.md)とは別に調整できます。

![中央のラインが小さすぎると、その周りの2つのラインが幅広になります](../images/min_wall_line_width_0_34.png)
![この設定を減少させると、中央のラインが始まりと終わりがはるかに小さくなります](../images/min_wall_line_width_odd_0_1.png)

偶数対奇数ライン
----
この設定は、行が奇数のときに特定の行を削除するためのしきい値を調整することができます。これは、中央に単一の行があり、2つではない場合です。この単一のラインが、その周りの2つの行を少しだけ幅広にするために削除されるタイミングを決定します。

最小の奇数壁ライン幅と最小の偶数ライン幅は、遷移の仕方により異なる可能性があります。奇数のラインが削除されると、遷移の前に停止し、周囲の壁が閉じ込められます。遷移中には、周囲のラインがまだ完全に結合していない隙間が少しあります。これは、壁の数が偶数の場合と異なります: 中央の2つのラインが一緒に崩れ、それらをわずかに重ねます。最小の奇数壁ライン幅を減らすと、奇数から偶数のラインへの遷移時の隙間のサイズが減ります。最小の偶数壁ライン幅を減らすと、偶数から奇数のラインへの遷移時の過押出が減ります。

奇数のラインが終わるときに残される隙間は、ジョイントでの過押出よりも最終結果で目立つため、最小の奇数壁ライン幅を最小の偶数壁ライン幅よりも少し低く設定すると良いかもしれません。

この設定を減らすと次の結果につながります。
* 中央のラインが終わるときの隙間が小さくなります。
* 一対の偶数中心ラインの最大幅が減少します。
* より細いラインが描かれ、うまく押し出されない可能性があります。
* より長いラインが描かれ、印刷に時間がかかる。

**この設定は、通常の壁だけでなく、追加のスキン壁、サポート壁、インフィル壁、同心パターンにも適用されます。**

---

Minimum Odd Wall Line Width
====
When printing thin pieces, Cura adjusts the width of wall lines to fit the exact width of the model. Cura can also decide to use fewer wall lines instead. This setting is the threshold at which Cura will remove a line in the centre. It can be adjusted separately from the [threshold at which the middle two lines combine](min_even_wall_line_width.md).

![When the centre line is too small, the two lines around it are made wider](../images/min_wall_line_width_0_34.png)
![Reducing this setting, the centre line starts and ends much smaller](../images/min_wall_line_width_odd_0_1.png)

Even vs. Odd Lines
----
This setting allows adjusting the threshold for removing lines specifically when there is an odd number of lines. This is when there is a single line in the centre rather than two. It determines when this single line is removed in favour of having the two lines around it be slightly wider.

The minimum odd wall line width might be different from the minimum even line width because of the way they transition. When an odd line is removed, it stops before the transition and lets the surrounding walls close in. During the transition there is a bit of a gap where the surrounding lines haven't quite come together yet. This is different from when there is an even number of walls: The two lines in the middle then collapse together, overlapping them slightly. Reducing the minimum odd wall line width reduces the size of the gap at the transitions from odd to even lines. Reducing the minimum even wall line width reduces the overextrusion at the transitions from even to odd lines.

The gaps left when an odd line ends are more visible in the end result than a bit of overextrusion at a joint, so it could help to set the Minimum Odd Wall Line Width a bit lower than the Minimum Even Wall Line Width.

Reducing this setting leads to:
* Smaller gaps when a central line ends.
* Reduced maximum width of a pair of even centre lines.
* Thinner lines, which may not extrude well.
* Longer lines, which take longer to print.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**