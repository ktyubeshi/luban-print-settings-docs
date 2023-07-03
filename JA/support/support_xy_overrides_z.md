サポート距離の優先順位
====
サポートX/Y距離とサポートZ距離が互いに衝突することはよくあります。サポート距離の優先順位設定は、これら2つの間での優先度を決定するために使用されます。

X/Y が Z を上書き
----
![X/Y overrides Z](../images/support_xy_overrides_z.svg)

X/Y距離がZ距離を上書きする場合、X/Y距離は常に一定に保たれます。それは、Z距離が異なるレイヤーで変化することを意味しています。しかし、Z距離は最小距離として保持されるので、オーバーハングが非常に水平な場合、Z距離が起動し、X/Y距離が理想的な値よりも大きくなります。

Z が X/Y を上書き
----
![Z overrides X/Y](../images/support_z_overrides_xy.svg)

Z距離がX/Y距離を上書きする場合、Z距離は常に一定に保たれます。それは、X/Y距離が異なるレイヤーで変化することを意味してます。その後、X/Y距離はZ距離が影響を及ぼさない場所での印刷に対してのみ影響を及ぼします、つまり、サポート構造の上部ではなく、側面だけです。

最小のX/Y距離は依然として観察されます。オーバーハングが非常に垂直な場合、X/Y距離はサポートがモデルの側面に溶接してしまうほど小さくなってしまうかもしれません。 [最小X/Y距離](support_xy_distance_overhang.md) はそれを防ぎます。

---

Support Distance Priority
====
It is common that the Support X/Y Distance and Support Z Distance conflict with each other. The Support Distance Priority setting is used to determine the preference between the two.

X/Y overrides Z
----
![X/Y overrides Z](../images/support_xy_overrides_z.svg)

If the X/Y distance overrides the Z distance, then the X/Y distance is always kept constant, even if that means that the Z distance is changing at different layer. The Z distance is still held as a minimum distance though, so if the overhang is very horizontal, the Z distance still kicks in, making the X/Y distance greater than desired.

Z overrides X/Y
----
![Z overrides X/Y](../images/support_z_overrides_xy.svg)

If the Z distance overrides the X/Y distance, then the Z distance is always kept constant, even if that means that the X/Y distance is changing at different layer. The X/Y distance then only gets any influence over the print in locations where the Z distance does not come into play, not at the top of the support structures but only at the sides.

A minimum X/Y distance is still observed though. If the overhang is very vertical, the X/Y distance would become so small that the support may fuse to the sides of the model. The [Minimum X/Y Distance](support_xy_distance_overhang.md) prevents that.