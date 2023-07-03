壁転換閾値角度
====
この角度は、Curaが適切に空間を埋めるための転換を作り始める角度を示しています。この角度より鋭角のすべての角は、変数幅の線で埋められます。

![10°より広いと、転換を作り続けることはない](../images/wall_transition_angle.png)

これは、特定の角で可変ライン幅をオンまたはオフにすることになります。もし二つの対向壁がほぼ平行で、この設定で指定した角度よりも小さければ、その間の領域は幅が変化する可能性のある線で埋められます。もし互いに角度が大きければ、その間にある空間は幅が一定の壁で埋められます。

いつものように、これはトレードオフです。幅を可変にすることはいくつかの利点があります：
* 線の間に隙間を残しません。
* 同じ空間を何度も埋めることはありません。
* プリントの寸法はそこでより精確になります。

しかし、いくつかの欠点もあります：
* 表面に波状の凹凸を発生させる可能性のある薄片に角を導入します。
* 追加の移動を生成します。
* プリンタは連続的にラインの幅を正確に変更することができないかもしれません。

実際には、層ビューで見ることができる鋭角の隙間の大きさを減らすために、この角度を十分に大きくすることがよいですが、それ以外の場合は可能な限り小さくすることがよいです。角度が小さい方が表面は一般的に滑らかに見えます。

可変ライン幅を完全になくすために角度を0°に減らすことはできません。平行な反対側の壁は常にその空間に合うように線幅を調整します。

**この設定は、通常の壁だけでなく、追加のスキン壁、サポート壁、インフィル壁、集中パターンにも適用されます。**

---

Wall Transitioning Threshold Angle
====
This angle indicates the angle at which Cura starts creating transitions to properly fill the space. Any corners that are sharper than this angle will get filled with variable-width lines.

![Wider than 10°, it's no longer creating transitions](../images/wall_transition_angle.png)

Effectively this turns variable line widths on or off for certain corners. If two opposite walls are almost parallel, smaller than the angle specified in this setting, the area between them gets filled with lines that may vary in their width. If they are at a greater angle from one another, the space between them gets filled with constant-width walls.

As always, this is a trade-off. Using a variable width has some advantages, such as:
* It leaves no gaps between the lines.
* It doesn't fill the same space multiple times.
* The dimensions of the print will be more accurate there.

However it also has some disadvantages:
* It introduces corners in thin pieces that may appear as ripples on the surface.
* It creates extra travel moves.
* The printer may not accurately change the line width in quick succession.

In practice, it's good to make this angle large enough to reduce the size of the gaps in sharp corners, as can be seen in layer view, but as small as possible otherwise. A smaller angle generally makes the surface look smoother.

It's not possible to reduce the angle to 0° to get rid of variable line widths altogether. Parallel opposite walls will always get their line width adjusted to fit the space.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**