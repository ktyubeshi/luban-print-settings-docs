サポートX/Y距離
====
これは、サポートとモデルの間に横方向にどれだけの距離を保つ必要があるかを示しています。

![サポートとモデルの間の水平方向の隙間](../images/support_xy_distance.png)

水平距離は、サポートがモデルに当たって表面に傷をつけるのを防ぐためのものです。しかし、これによりモデルとサポート構造の間の距離が大きくなり、オーバーハングがある部分にサポートがない状態になります。

X/Y距離とZ距離
----
X/Y距離とZ距離は互いに競合する可能性があります。この場合、[サポート距離優先](support_xy_overrides_z.md)設定を用いて、どちらを優先するかを決定することができます。

![X/YがZを上書き](../images/support_xy_overrides_z.svg)

X/YがZを上書きする場合、X/Y距離を保持し、それがZ距離が大きすぎることを意味してもです。Z距離は最小限に保たれます。

![ZがX/Yを上書き](../images/support_z_overrides_xy.svg)

ZがX/Yを上書きする場合、Z距離を保持し、それがX/Y距離が短すぎることを意味してもです。X/Y距離は、Z距離が影響を及ぼさないサポートの上部から離れたところでしか影響を持ちません。

---

Support X/Y Distance
====
This indicates how much distance must be kept horizontally between the support and the model.

![A horizontal gap between the support and the model](../images/support_xy_distance.png)

The horizontal distance is meant to prevent the support from hitting the model, where it would leave a scar on the surface. However, this also creates a larger distance between the model and the support structure where the overhang is, leaving some overhangs unsupported.

X/Y Distance and Z Distance
----
The X/Y distance and the Z distance could conflict with each other. In this case, the [Support Distance Priority](support_xy_overrides_z.md) setting can be used to determine the preference between the two.

![X/Y overrides Z](../images/support_xy_overrides_z.svg)

If X/Y overrides Z, the X/Y distance is held, even if that means that the Z distance is too great. The Z distance is still held as minimum.

![Z overrides X/Y](../images/support_z_overrides_xy.svg)

If Z overrides X/Y, the Z distance is held, even if that means that the X/Y distance is too small. The X/Y distance then only has any influence away from the top of the support where the Z distance has no influence.