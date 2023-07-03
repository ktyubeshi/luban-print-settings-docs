単調鉄線順序
====
通常、ルーバンは鉄線の順序を小さな移動距離となるように指定します。この設定を有効にすると、隣接するラインは常に同一の方向で重なるように印刷されるようになります。

鉄線はデフォルトで、印刷されるノズルよりも薄くなっているので、隣接するラインと大きく重なります。この重なりがラインにわずかな傾斜を与え、ライトの反射角度を変えます。隣接するラインが異なる重なりを持つと、この反射が変化します。これが最終結果に見て取れます。それは表面の異なるエリアに異なる光沢を与えます。単調な順序で印刷することで、反射の違いがないように全体の表面上の重なりが同じになります。これにより表面がより一貫した滑らかな見た目になります。

しかし、[上面/底面のラインに相当する] (skin_monotonic.md)効果とは反対に、これはアイロンが非常に低い流れの速さを持っているため、普通のプリントから来る流れの変化が大きいので、これはアイロニングには適していません。これにより、印刷が始まるとアイロニング層が厚くなり、印刷が中断された部分には明らかな境界線が残ります。単調な順序では、これらの境界線を取り除くことはありません。表面がわずかに滑らかに見えるかもしれませんが、実際にはフローレートに非常に正確な制御を持つプリンターでない限り、単調な順序で鉄線を印刷することはほとんど効果がありません。

単調な順序は移動距離をわずかに長くしますが、この効果は非常に微弱です。

滑らかな表面を得るために、この設定と[Combingモード](../travel/retraction_combing.md)をスキンを避けるように設定し、[Zホップ](../travel/retraction_hop.md)を有効にすることを考慮してください。

---

Monotonic Ironing Order
====
Normally, Luban orders ironing lines such that the travel distance between them is small. If this setting is enabled, it will order the ironing lines such that adjacent lines are always printed overlapping in the same direction.

Ironing lines are by default much thinner than the nozzle they are printed with, so the lines will overlap a lot with the lines next to them. This overlap gives the lines a slight slope, causing them to reflect light differently in different directions. If adjacent lines overlap differently, this reflection changes. You can see this in the final result. It gives different areas of the surface a different shine. Printing in a monotonic order ensures that the overlap is the same on the entire surface, so there is no difference in how it reflects light. This makes the surface look more consistent and smooth.

However, contrary to [the equivalent for top/bottom lines](skin_monotonic.md), this effect is for ironing is overwhelmed by a different effect. Ironing has such a low flow rate that the flow change coming from ordinary printing is very large. This makes the ironing layer thicker when it starts printing, and still leaves a noticeable border where printing was interrupted. A monotonic order will not remove these borders. While the surface might look slightly smoother, in practice printing the ironing lines in monotonic order is largely ineffective unless your printer has very accurate control over flow rate.

The monotonic order will slightly increase the length of travel moves, but this effect is very minimal.

To achieve a smooth surface, consider pairing this setting with setting the [Combing Mode](../travel/retraction_combing.md) to avoid skin, and perhaps to enable [Z Hops](../travel/retraction_hop.md).