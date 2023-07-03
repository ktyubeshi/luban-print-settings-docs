サポート壁行数
====
この設定は、サポートの周囲に壁を追加します。

![余分な壁なし](../images/support_wall_count_0.png)
![余分な壁3つ](../images/support_wall_count_3.png)

余分な壁はサポートに強度を加え、倒れる可能性を減らします。また、サポートがオーバーハングエリアの非常に端部をよりよく支えることを可能にします。鋭角な角を持つモデルでは、これらのエッジは線がそこで途中で終わるため問題となる傾向があります。この設定は、その代わりにサポートライン上で終わらせることができます。

しかし、余分な壁はさらに印刷時間がかかり、材料の消費が多くなる上、オブジェクトからのサポートの取り外しが困難になります。溶解性サポート素材を使用する場合、余分な壁は溶媒がサポート構造の側面から入れなくなるため、サポートが溶けるのに時間がかかります。

---

Support Wall Line Count
====
This setting adds a number of walls around the perimeter of the support.

![No extra walls](../images/support_wall_count_0.png)
![3 extra walls](../images/support_wall_count_3.png)

The extra walls add strength to the support, reducing the chance that they topple over. It also allows the support to better support the very edges of the overhang area. For models with sharp corners, these edges tend to be problematic because lines end in mid-air there. This setting can make them end on a support line instead.

However the extra walls also take more time to print, use more material and make the support harder to remove from the object afterwards. When working with soluble support materials, the extra walls cause the support to take longer to dissolve because the solvent cannot enter the support structure from the side any more.