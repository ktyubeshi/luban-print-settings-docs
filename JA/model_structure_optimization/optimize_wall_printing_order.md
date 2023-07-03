壁印刷順序の最適化
====
この機能が有効になっていると、Lubanは壁を印刷する順序を最適化するために追加のスライス時間を使います。目標は、同じ部品を囲む壁を一つずつ印刷することで移動回数とリトラクションの数を減らすことです。

![最適化無効](../images/optimize_wall_printing_order_disabled.gif)
![最適化有効](../images/optimize_wall_printing_order_enabled.gif)

この最適化が有効になっている場合、ノズルは次の部品に移動する前に、一つの部品を囲む全ての壁を先に印刷します。内側の壁全体を先に印刷してから外側の壁を印刷するのではなく。最適化は通常はプラスですが、部品によっては次に配置する壁がまだ固まっていない時に前の壁の寸法精度に影響を与える場合があります。

---

Optimize Wall Printing Order
====
If this is enabled, Luban will spend some extra slicing time to optimise the order in which the walls are printed. The goal is to reduce the number of travel moves and retractions by printing walls that surround the same part after one another.

![Optimisation disabled](../images/optimize_wall_printing_order_disabled.gif)
![Optimisation enabled](../images/optimize_wall_printing_order_enabled.gif)

If this optimisation is enabled, the nozzle will print all the walls around one part first before moving to the next part, instead of printing all of the inner walls first before printing the outer walls. Optimising is usually positive, but with some parts it may impact dimensional accuracy because the previous wall hasn't solidified yet when placing down the next one next to it.