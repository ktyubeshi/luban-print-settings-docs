最小偶数の壁ライン幅
====
薄いパーツを印刷する際には、Curaは壁線の幅をモデルの正確な幅に合わせて調整します。また、Curaは壁線の数を減らすことも可能です。この設定は、Curaが2つの線を1つに結合する閾値です。[中央線が削除される閾値](min_odd_wall_line_width.md)とは別に調整することができます。

![中心線が合うように広がっています](../images/min_wall_line_width_0_34.png)
![この設定を減らすと、代わりに2本の線を使用します](../images/min_wall_line_width_even_0_1.png)

偶数対奇数の線
----
この設定は、特に偶数の線がある場合に線を削除する閾値を調整することができます。これは、中央に1本の線ではなく、2本の線がある場合です。それは、中央の2本の線が1本の線に結合するときに決定されます。

最小偶数壁ライン幅は、結合の方法により、最小奇数壁ライン幅と異なる可能性があります。偶数ラインは、端部が近づくことで端部で結合します。そこではこれらのラインが一部重なり、過押出が発生します。これは、奇数の壁がある場合とは異なります：その場合、中央の線はただ止まり、印刷に隙間を残します。最小偶数壁ライン幅を減らすと、偶数から奇数のラインへの遷移時の過押出が減ります。最小奇数壁ライン幅を減らすと、奇数から偶数のラインへの遷移時の隙間の大きさが減ります。

奇数の線が終わるときに残される隙間は、ジョイントでの過押出よりも最終結果で目立つことが多いので、最小偶数壁ライン幅を最小奇数壁ライン幅よりも少し高く設定すると役立つかもしれません。

この設定を減らすと以下の効果が生じます：
* 二つの線が一つに合体して結合する部分の面積が減少します。
* 単一の中心線の最大幅が減少します。
* 薄い線が形成され、押出しがうまくいかない可能性があります。
* 印刷時間が長くなる多くの線が形成されます。

**この設定は、普通の壁だけでなく、余分な皮膚の壁、サポート壁、インフィル壁、同心円パターンにも適用されます。**

---

Minimum Even Wall Line Width
====
When printing thin pieces, Cura adjusts the width of wall lines to fit the exact width of the model. Cura can also decide to use fewer wall lines instead. This setting is the threshold at which Cura will combine two lines into one. It can be adjusted separately from the [threshold at which the middle line is removed](min_odd_wall_line_width.md).

![The centre line is made wider to fit](../images/min_wall_line_width_0_34.png)
![Reducing this setting, it uses two lines instead](../images/min_wall_line_width_even_0_1.png)

Even vs. Odd Lines
----
This setting allows adjusting the threshold for removing lines specifically when there is an even number of lines. This is when there are two lines in the centre rather than a single line. It determines when these two lines in the middle combine into a single line.

The minimum even wall line width might be different from the minimum odd wall line width because of the way they join together. Even lines join at their ends by making the ends come closer together. There is some overlap with these lines there, leading to overextrusion. This is different from when there is an odd number of walls: The line in the middle then just stops, leaving a gap in the print. Reducing the minimum even wall line width reduces the overextrusion at the transitions from even to odd lines. Reducing the minimum odd wall line width reduces the size of the gap at the transitions from odd to even lines.

The gaps left when an odd line ends are more visible in the end result than a bit of overextrusion at a joint, so it could help to set the Minimum Even Wall Line Width a bit higher than the Minimum Odd Wall Line Width.

Reducing this setting leads to:
* Reduced area of overlap where two lines join together to merge into one line.
* Reduced maximum width of single centre lines.
* Thinner lines, which may not extrude well.
* More lines, which take longer to print.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**