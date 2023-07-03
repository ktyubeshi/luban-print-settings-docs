壁の前にインフィル
====
この設定が有効になっていると、レイヤー内の壁の前にインフィルが印刷されます。

![設定は無効になっているので、まず壁が印刷されます](../images/infill_before_walls_disabled.gif)
![設定が有効になると、まずインフィルが印刷されます](../images/infill_before_walls_enabled.gif)

この設定は精度と強度とのトレードオフです：
* 壁がインフィルの前に印刷される場合、壁がくっつくものが何もない場合、壁がさらに落ち込む可能性があります。ただし、壁は最初に固まっており、インフィルによって押し出されることはありません。これにより、インフィルが壁を通して光るのを防ぎます。
* インフィルが壁の前に印刷される場合、壁はインフィルが壁に取り付けられている場所で押し出され、壁があまり正確ではなくなり、インフィルが表面を通って光り、外側に見えるパターンを作り出すことがあります。ただし、インフィルは壁が印刷されている間、壁をよりしっかりと保持します。

---

Infill Before Walls
====
With this setting enabled, the infill will be printed before the walls in a layer.

![Setting is disabled, so walls are printed first](../images/infill_before_walls_disabled.gif)
![Setting is enabled, so infill is printed first](../images/infill_before_walls_enabled.gif)

This setting is a trade-off between accuracy and strength:
* If the walls are printed before the infill, the walls could have nothing to attach to, causing them to sag more. However, the walls will have solidified first and won't be pushed away by the infill, which prevents the infill from shining through the walls.
* If the infill is printed before the walls, the walls will get pushed away where infill is attached to the walls, which makes the walls less accurate and can cause the infill to shine through the surface, creating a pattern visible on the outside. However the infill will hold the walls in place better while they are printed.