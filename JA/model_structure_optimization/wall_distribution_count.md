壁の分配数
====
Curaは、印刷している形状により適合するように壁ラインの幅を調整することができますが、すべての壁を同じ量で調整する必要はありません。モデルの内側に向かって壁の幅を変えることを優先します。この設定は、利用可能なスペースに合わせて調整される壁の数を、内側から外側に向かって数えて決定します。

![中央に集中し、そこでライン幅に大きな変動がある](../images/wall_distribution_count_1.png)
![多くの壁に広がる](../images/wall_distribution_count_5.png)

幅が変化する壁は、単純な定常幅の壁よりも印刷するのが難しいです。ノズルからの流量を調整するには時間がかかり、また遷移するためには鋭い角を作る必要があり、これがリンギングを引き起こす可能性があります。これらのことはすべて、印刷の表面で見える場所からできるだけ遠くで行うのが最善です。そのため、Curaはライン幅の調整を最も内側の壁に集中します。

一方で、変動を集中させるということは、中央のラインの幅が大きく異なることを意味します。それをより多くのラインに広げると、変動の振幅を小さくすることができ、可変ライン幅の影響を減らすことができます。

この設定では、利用可能なスペースを埋めるためにライン幅を調整できる壁の数を内側から選択します。これは中心から両方向に数えますので、この設定が2に設定されている場合、最大4つの壁を中心に調整することができます。調整は、それらの壁内で均等に広がっていません。中心部の壁は常に外側に近い壁よりもわずかに多く調整されます。

外壁は常に可能な限り名目ライン幅に保たれます。この壁は印刷品質にとって非常に重要なので、表面をできるだけ滑らかにするために、一定のライン幅を保つようにしています。もしピースが薄くなって外壁だけで構成されるようになった場合のみ、これらの壁が調整されます。

実際には、中心部の不完全性を隠すことは、複数の壁に不完全性を広げるよりもほぼ常に良い戦略です。その結果、この設定はできるだけ低く保つことが最善です。押出しや流れの変更が困難な材料、例えば柔軟な材料を使用する際は、この設定を増やして流れの変更を減らすのが助けになります。しかし、それが流れの変更を完全に防ぐことはありません。

**この設定は通常の壁だけでなく、追加の肌壁、サポート壁、インフィル壁、同心円パターンにも適用されます。**

---

Wall Distribution Count
====
Cura can adjust the width of wall lines to better fit the shape you're printing, but it doesn't have to adjust every wall by the same amount. It prefers to change the width of walls further towards the inside of the model. This setting determines the number of walls, counting from the inside out, that get adjusted to fit the available space.

![Concentrated in the middle, with big variations in line widths there](../images/wall_distribution_count_1.png)
![Spread out over many walls](../images/wall_distribution_count_5.png)

Walls with varying width are harder to print than simple constant-width walls. It takes some time to adjust the flow rate out of the nozzle, and to transition it also needs to make some sharp corners which can cause ringing. All of this is best done as far away from the outside as possible, where it would be visible on the surface of the print. So Cura will concentrate the line width adjustments on the innermost walls.

On the other hand, concentrating the variation also means that those lines in the middle will have widely diverging widths. Spreading that out over more lines means that the amplitude of the variations can be smaller, reducing the impact of variable line width instead of hiding it on the inside.

This setting selects a number of walls from the inside among which the line width can be adjusted to fill the available space. This counts in both directions from the centre, so if this is set to 2, up to 4 walls can be adjusted in the centre. The adjustment is not evenly spread out within those walls either. The walls in the centre will always be adjusted slightly more than walls closer to the outside.

The outer wall is always kept at the nominal line width where possible. This wall is so influential on the print quality that it is kept at a constant line width to make the surface as smooth as possible. Only if the piece becomes so thin that it consists solely out of outer walls will those walls be adjusted.

In practice, hiding the imperfections in the centre is almost always a better strategy than spreading the imperfections over multiple walls. As a result, it's best to keep this setting as low as possible. When working with materials that are difficult to extrude or change the flow of, such as flexible materials, it helps to increase this setting to reduce flow changes. It can never prevent those flow changes entirely though.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**