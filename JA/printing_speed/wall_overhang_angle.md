オーバーハングウォール角度
====
### **説明**
この設定は、壁が「オーバーハングウォール」としてマークされる閾値の角度を示します。これらのオーバーハングウォールは、[オーバーハングウォールスピード](wall_overhang_speed_factor.md)設定を使用して異なるスピードで印刷できます。

この設定を0°に設定すると、すべての壁がオーバーハングウォールとして扱われます。この設定を90°に設定すると、オーバーハングウォールとして扱われる壁はありません。サポート上に接地している壁もオーバーハングウォールとして扱われません。

この機能の目的は、[サポート](../support/support_enable.md)によって支持される必要があるかどうかの近い領域により良いオーバーハング品質を提供することです。サポートを追加して時間と材料を費やし、サポートを取り除くときに表面を傷つける代わりに、これらのオーバーハングウォールを少し遅く印刷して[サポートオーバーハング角度](../support/support_angle.md)をやや高く設定することができます。これにより、より段階的なアプローチで増加するオーバーハング角度をより良く印刷できます。

サポートオーバーハング角度よりもこの設定を高く設定すると、サポート上にある壁がオーバーハングウォールとしてマークされないため、この機能の効果が大幅に低下します。しかし、サポートが無効になっている場合や、[最小サポート面積](../support_adv/minimum_support_area.md)などの理由でサポートされていないオーバーハング部分などでは、この機能はまだ効果があります。

wall_overhang_angle.md

-----------

Overhanging Wall Angle
====
### **Description**
This setting indicates the threshold angle after which a wall will be marked as an "overhanging wall". These overhanging walls can be printed at a different speed using the [Overhanging Wall Speed](wall_overhang_speed_factor.md) setting.

If this setting is set to 0°, all walls will be treated as overhanging walls. If this setting is set to 90°, no walls will be treated as overhanging walls. Walls that rest on support are not treated as overhanging walls either.

The aim of this feature is to provide better overhang qualities for areas that would almost need to be supported by [support](../support/support_enable.md), but not quite. Instead of spending extra time and material on support and scarring the surface when removing that support, you can choose to print these overhanging walls a bit slower and set the [Support Overhang Angle](../support/support_angle.md) somewhat higher. This achieves a more staged approach to printing increasing overhang angles better.

Setting this setting higher than the Support Overhang Angle reduces the effect of this feature greatly since walls on top of support are not marked as overhanging walls, and so any walls that are printed at an overhang angle that would be considered an overhanging wall would also be supported and not printed at different speeds. However this feature still has an effect then if support is disabled or for parts of overhang that are not supported for other reasons, such as [Minimum Support Area](../support_adv/minimum_support_area.md).
