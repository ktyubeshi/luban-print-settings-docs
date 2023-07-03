後退を優先
====
### **説明**
壁の重複を補償すると、一部の壁ラインのフローレートが減少します。このフローレートが [最小壁フロー](wall_min_flow.md)設定の値以下になると、壁ラインを印刷する代わりに移動操作が行われます。

この設定が有効になっている場合、その移動操作の間にフィラメントが後退します。

### **使用法**
この設定の目的は、壁におけるにじみを減らすことです。「最小壁フロー」設定の目的は、見栄えの良くない極端に薄い壁からのにじみを減らすことです。それは「後退を優先」を有効にすることでさらに改善することができます。

ただし、外壁で後退すると、フィラメントが後退している間ノズルが一時的に停止します。これにより、後退が行われた場所の表面に塊が残ります。また、印刷時間が増加し、フィラメントがより早く摩耗します。

---

Prefer Retract
====
### **Description**
Compensating for wall overlaps will reduce the flow rate of some of the wall lines. If this flow rate gets below the value of the [Minimum Wall Flow](wall_min_flow.md) setting, a travel move is made instead of printing the wall line.

If this setting is enabled, the filament will be retracted during that travel move.

### **Usage**
The intended effect of this setting is to reduce oozing on the walls. The intent of the Minimum Wall Flow setting is to reduce the ooze from extremely thin walls which doesn't look nice. That can be improved even further by enabling Prefer Retract.

However retracting on the outer walls will cause the nozzle to pause momentarily while the filament is retracted. This leaves a blob on the surface where the retraction was made. It also increases printing time and wears down the filament faster.