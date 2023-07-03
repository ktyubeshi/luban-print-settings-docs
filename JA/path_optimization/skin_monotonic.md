単調な上/下順序
====
通常、Curaは、上下のライン間の移動距離が小さくなるようにラインを並べます。この設定を有効にすると、隣り合うラインが常に同じ方向に重なるように上下のラインを並べます。

上下のラインを印刷する場合、ラインの形状が完全な四角形でないため、ラインは通常、隣のラインと少し重なります。この重なりがラインにわずかな傾斜を与え、異なる方向で光を反射します。隣接するラインが違うように重なると、この反射は変化します。これは最終結果で見ることができます。表面の異なるエリアに異なる光沢を与えます。単調な順序で印刷することで、全面での重なりが同じになるため、光の反射方法に差がありません。これにより、表面は一貫性があり、滑らかに見えます。

![単調な順序ではない](../images/skin_monotonic_disabled.gif)
![常に右下の角からの単調な順序](../images/skin_monotonic_enabled.gif)

単調な順序は移動距離をわずかに長くしますが、その影響は非常に小さいです。印刷に視覚的な影響を与えるだけです。単調な順序には機械的な利点はありません。

滑らかな表面を得るために、この設定と[Combing Mode](../travel/retraction_combing.md)をスキンを避けるように設定すること、または[Z Hops](../travel/retraction_hop.md)を有効にすることを検討してみてください。あるいは、[ironing](ironing_enabled.md)も有効にすることができますが、それはこの設定の有用性を完全に覆します。アイロニングには独自の[単調な選択肢](ironing_monotonic.md)があります。

![ラインが一貫していない順序で印刷されると、きらめきが違います](../images/skin_monotonic_disabled.jpg)
![単調な順序で、きらめきはどこでも同じです](../images/skin_monotonic_enabled.jpg)

---

Monotonic Top/Bottom Order
====
Normally, Cura orders top/bottom lines such that the travel distance between them is small. If this setting is enabled, it will order the top/bottom lines such that adjacent lines are always printed overlapping in the same direction.

When printing top/bottom lines, the lines usually overlap a bit with the lines next to them, because the shape of a line is not a perfect rectangle. This overlap gives the lines a slight slope, causing them to reflect light differently in different directions. If adjacent lines overlap differently, this reflection changes. You can see this in the final result. It gives different areas of the surface a different shine. Printing in a monotonic order ensures that the overlap is the same on the entire surface, so there is no difference in how it reflects light. This makes the surface look more consistent and smooth.

![Not a monotonic order](../images/skin_monotonic_disabled.gif)
![Monotonic order, always from the bottom-right corner](../images/skin_monotonic_enabled.gif)

The monotonic order will slightly increase the length of travel moves, but this effect is very minimal. It only has a visual effect on the print. There are no mechanical advantages to the monotonic ordering.

To achieve a smooth surface, consider pairing this setting with setting the [Combing Mode](../travel/retraction_combing.md) to avoid skin, and perhaps to enable [Z Hops](../travel/retraction_hop.md). Alternatively you could also enable [ironing](ironing_enabled.md), but that completely overrides the usefulness of this setting. Ironing has its own [monotonic option](ironing_monotonic.md).

![The shimmer is different when lines are printed in inconsistent order](../images/skin_monotonic_disabled.jpg)
![With monotonic order, the shimmer is the same everywhere](../images/skin_monotonic_enabled.jpg)