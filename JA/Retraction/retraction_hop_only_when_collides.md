印刷部品上のみのZホップ
====
### **説明**
[印刷部品を避ける](travel_avoid_other_parts.md)設定が有効になっている場合、ノズルは一箇所から別の箇所へ移動する際に他の部品を避けます。通常は、Zホップが適用されると、印刷部品を避ける必要はもうありません。この設定はそのロジックを反転させます：印刷部品を避けることができない場合、Zホップを適用します。

### **用途**
Zホップは、一部のプリンタのZ軸の消耗に問題を引き起こす可能性があります。この設定により、物体を垂直にではなく水平に回避することでZホップの量を減らすことができます。一部のプリンタでは、水平に移動する方が垂直に移動するよりも速く、これにより時間を節約できます。

---

Z Hop Only Over Printed Parts
====
### **Description**
If the [Avoid Printed Parts](travel_avoid_other_parts.md) setting is enabled, the nozzle will avoid other parts when travelling from one place to another. Normally, if a Z hop is applied, avoiding printed parts is not necessary any more. This setting switches that logic around: If avoiding printed parts is not possible, a Z hop is applied.

### **Usage**
Z hops can be problematic for the wear of the Z axis of some printers. This setting can reduce the amount of Z hops by going around an object horizontally instead of vertically. For some printers, moving horizontally can also be faster than moving vertically, and thus save time.