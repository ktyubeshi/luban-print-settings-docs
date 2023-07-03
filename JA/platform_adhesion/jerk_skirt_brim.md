スカート/ブリム ジャーク
====
### **説明**
この設定は、ノズルがスカートまたはブリムを印刷する際に角を通過する速度を決定します。初期層の残り部分とは別に設定することができます。

### **影響**
ノズルが角を通過しているとき、ツールヘッドは水平方向にだけでなく、ビルドプレートも垂直方向に振動します。この振動が原因で、スカートまたはブリムとビルドプレートとの間の接着が一定でなくなります。スカートやブリムの印刷中にジャークを減らすことで、プリントがビルドプレートから離れる可能性を減らすことができます。

### **使用方法**
スカートとブリムは常に初期層の一部であるにもかかわらず、[初期層印刷ジャーク](jerk_print_layer_0.md)はこれらに影響を及ぼしません。この設定は初期層印刷ジャークを上書きします。

---

Skirt/Brim Jerk
====
### **Description**
This setting determines the speed at which the nozzle can go through corners while printing the skirt or brim. It can be configured separately from the rest of the initial layer.

### **Influence**
When the nozzle is going through corners, the toolhead will not only vibrate horizontally, but the build plate can also vibrate vertically. This vibration causes the adhesion between the skirt or brim and the build plate to be less consistent. Reducing the jerk during the printing of the skirt or the brim can reduce the chance of the print letting go of the build plate.

### **Usage**
Even though the skirt and brim are always part of the initial layer, the [Initial Layer Print Jerk](jerk_print_layer_0.md) has no effect on them. This setting overrides the Initial Layer Print Jerk.

