タワーサポート可能な最大直径
====
この設定は、通常のサポートとサポートタワーの選択に使用されるオーバーハング部分の直径のしきい値です。パーツがこのしきい値より薄い場合、[支持タワー](support_use_towers.md)で支持されます。この閾値よりも幅広い場合、通常のサポート構造で支持されます。

![剣は最小直径よりも小さいオーバーハング部分を持っています](../images/support_use_towers.svg)

非常に細いストリップのオーバーハングがサポートが必要な場合、通常のサポートでは倒れてしまいます。代わりに、より堅固なタワーが生成されます。

この設定を増やすと、タワーがより頻繁に生成されます。これにより、サポートの信頼性が向上しますが、わずかに多くの材料と印刷時間が必要になります。

---

Maximum Tower-Supported Diameter
====
This setting is a threshold for the diameter of a piece of overhang to choose between normal support and support towers. If the piece is thinner than this threshold, it'll get supported by a [support tower](support_use_towers.md). If it is wider than this threshold, it'll get supported by the ordinary support structures.

![The sword has an overhang area smaller than the minimum diameter](../images/support_use_towers.svg)

If a very thin strip of overhang needs support, normal support would topple over. Instead, a more sturdy tower is generated.

Increasing this setting will cause towers to be generated more frequently. This increases the reliability of the support, but also requires slightly more material and printing time.