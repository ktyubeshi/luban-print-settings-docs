Zギャップにスキンを適用しない
====
モデルに上部/下部のスキン厚みよりも小さいスリットがある場合、この設定はその上部と下部を完全にスキンで埋めることを省略します。これにより、スライスと印刷の時間を節約できますが、インフィルを空気に晒す可能性があります。

![通常は、小さい水平スリットの周りにスキンがあります](../images/skin_no_small_gaps_heuristic_disabled.png)
![これが有効になっていると、スキンを適切に閉じません](../images/skin_no_small_gaps_heuristic_enabled.png)

この設定の主な目的は、スライス時間を短縮することです。この設定は、スキンが配置されるべき解像度を効果的に減少させます。モデルの形状によりますが、スライス時間を5%から30%節約することができます。また、印刷時間も節約できます。なぜなら、スキンの代わりに小さなギャップにインフィルを印刷するからです。モデルにスキン厚みより小さいギャップがない場合、唯一の効果はスライス時間の短縮になります。

モデルにそのような小さなギャップが存在する場合、ギャップを通じてインフィルが露出する可能性があります。しかし、ギャップが十分に小さい場合、オーバーハングが壁を十分に垂れ下がらせるため、見えなくなるでしょう。

---

No Skin In Z Gaps
====
If your model has a small slit, smaller than the top/bottom skin thickness, this setting doesn't bother filling the top and bottom above/below that completely with skin. This saves on slicing and printing time, but might expose infill to the air.

![Normally there is skin around the small horizontal slit](../images/skin_no_small_gaps_heuristic_disabled.png)
![If this is enabled, it doesn't properly close the skin](../images/skin_no_small_gaps_heuristic_enabled.png)

The main intent of this setting is to reduce slicing time. This setting effectively reduces the resolution where skin should have been placed. Depending on the shape of the model, this could save anywhere between 5% and 30% on slicing time. It will also save on printing time, because instead of skin it will print infill in small gaps. If the model has no gaps smaller than the skin thickness, the only effect will be reducing slicing time.

If the model does have such small gaps, there might be infill exposed through the gaps. However if the gap is small enough, the overhang would make the walls sag down enough that it won't be visible anyway.