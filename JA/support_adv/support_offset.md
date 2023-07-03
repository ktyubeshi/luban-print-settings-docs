以下の英語テキストをMarkdown形式で日本語に翻訳してください:

水平方向へのサポートの拡張
====
この設定により、サポートが若干広くなり、全方向に水平に広がります。

![サポートは、モデルを支えるのに必要な範囲よりも広い](../images/support_offset.png)

この設定は、サポートに使用される材料やサポートが必要なモデルのタイプにより、複数の用途があります：
* この設定を増やすと、サポートが広くなり、それに伴い堅牢になります。これは、オーバーハング部が非常に小さい高さのモデルに便利で、サポート無しでは非常に高い、細いサポートピラーでしかオーバーハング部を支えられないためです。水平拡張があれば、それは非常に高いが少し広いサポートピラーになります。
* また、この設定を増やすと、サポートエリアに一定の最小面積が確保されるようになり、安全対策としても機能します。これは、PVAなどの押し出しが困難な材料に必要です。
* この設定を減らすと、サポートの材料使用量と印刷時間が削減されます。もちろん、増やすと必要な材料と印刷時間も増えます。また、[円錐サポート](../experimental/support_conical_enabled.md)機能も参照してください。これは、サポートが支えるエリアを妥協することなく、サポートの幅を縮小します。
* また、この設定を負の値にすると、細いサポートピラーを完全に取り除くことも可能です。

---

Support Horizontal Expansion
====
This setting causes the support to become slightly wider, expanding horizontally in every direction.

![The support is wider than necessary to support the model](../images/support_offset.png)

This setting has multiple uses, depending on the material used for support and the type of model that needs supporting:
* Increasing this setting will make support wider and thus sturdier. This is useful for tall models with small areas of overhang, since the overhang would otherwise be supported with a very tall, thin pillar of support. With some horizontal expansion, it becomes a very tall but slightly wider pillar of support.
* Increasing this setting also functions as a safety measure to make sure that support areas have a certain minimum area. This is necessary for materials that are hard to extrude, such as PVA.
* Reducing this setting will reduce material usage and printing time for support. Increasing it will increase the required material and printing time, of course. See also the [conical support](../experimental/support_conical_enabled.md) feature, which reduces the width of support without compromising the area that the support supports.
* Setting it to a negative value can also remove thin pillars of support completely.