サポートブリムを有効にする
====
サポートブリムを有効にすると、最初のレイヤーのサポートエリア内部に追加のブリムが描かれます。

![サポートブリム](../images/support_brim_4mm.png)

サポートブリムは、普通のブリムとは異なり、*内側*に向かって描かれます。もし[ビルドプレート接着タイプ](../platform_adhesion/adhesion_type.md)がブリムに設定されている場合、サポートの*周囲*にももう一つのブリムが描かれます。

このブリムの目的は、サポートがビルドプレートに接着できる表面積を増やすことです。これは[初期レイヤーサポートライン距離](../support/support_initial_layer_line_distance.md)を調整することによっても達成できますが、この機能を使用すると、接着力はサポートエリアのエッジ周辺に集中し、そこが反り防止により効果的となります。

サポートブリムはサポートを大幅に強化することができます。また、印刷時間と材料費がわずかに増加しますが、これは最初のレイヤーのみに適用されるため、非常に小さい影響です。

---

Enable Support Brim
====
When the support brim is activated, an additional brim will be drawn inside the support area on the first layer.

![The support brim](../images/support_brim_4mm.png)

The support brim is drawn towards the *inside*, unlike the ordinary brim. If the [Build Plate Adhesion Type](../platform_adhesion/adhesion_type.md) is set to Brim, another brim will also be drawn *around* the support.

The purpose of this brim is to give the support more surface area where it can adhere to the build plate. This can also be achieved by adjusting the [Initial Layer Support Line Distance](../support/support_initial_layer_line_distance.md), but with this feature the adhesion will be concentrated around the edge of the support area, where it is more effective to prevent warping.

A support brim can significantly make the support stronger. It will also slightly increase the printing duration and material cost, but since it's only on the first layer this is very minimal. 
