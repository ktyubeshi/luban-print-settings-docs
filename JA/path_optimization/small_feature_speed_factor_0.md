小さな特徴の初期レイヤー速度
====
[Small Feature Max Length](small_feature_max_length.md)より短い輪郭は、速度を下げて印刷できます。この設定では、これらの輪郭が最初のレイヤーで印刷される速度を、[通常の印刷速度](../speed/speed_wall.md)の要素として指定できます。これは、[その他のレイヤー](small_feature_speed_factor.md)での小さな特徴の印刷速度とは別に設定できます。

小さな輪郭は、ビルドプレートにひっつく表面積があまりありません。特に、[インフィルよりも前に壁を印刷する](../infill/infill_before_walls.md)場合、小さな穴の壁はビルドプレート上に小さな円として配置されることが多いです。ノズルが後で移動するときにそれらを越えて行くと、ビルドプレートから弾き飛ばされる可能性があります。このため、小さな輪郭の印刷速度は他の輪郭と比べて低くする必要があります。これにより、材料がもっと流出してビルドプレートによりよく融合し、プレートから引き離す確率を減らします。

小さな輪郭の印刷速度を下げると、印刷速度に非常に小さい影響を及ぼします。幸いなことに、これらの輪郭は定義上小さく、最初のレイヤーにしか関係しないため、追加される印刷時間はそれほど大きくありません。

---

Small Feature Initial Layer Speed
====
Contours that are shorter than the [Small Feature Max Length](small_feature_max_length.md) can be printed at a reduced speed. With this setting, you can indicate the speed at which these contours should be printed on the first layer, as a factor of their [normal printing speed](../speed/speed_wall.md). This can be configured separately from the print speed of small features on the [rest of the layers](small_feature_speed_factor.md).

Small contours don't have a lot of surface area to stick to the build plate. Especially when [printing the walls before the infill](../infill/infill_before_walls.md), the walls for small holes are often just tiny circles laying on the build plate. If the nozzle strikes past them in a travel move later, they might get torn off the build plate. For this reason, the printing speed of these small contours need to be reduced compared to the other contours. This allows the material to flow out more and fuse to the build plate better, reducing the chance to pull them off the build plate.

Reducing the printing speed of these small contours has a very minor negative impact on the printing speed. Luckily, since these contours are small by definition and it only concerns the first layer, the total added print time is not significant.