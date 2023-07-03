初期レイヤー移動時のジャーク
====
### **説明**
この設定は、初期レイヤーの間にノズルがビルドプレートを横切る旅行中の角を通過できる速度を決定します。これは初期レイヤーの押し出し動作とは別に設定できます。

### **影響**
旅行の動作の間、印刷物とビルドプレートとの接着は振動によって影響を受けません。しかし、ビルドプレートが強く振動すると、ノズルはまだ印刷物をビルドプレートから剥がすことができます。

### **使い方**
過度のビルドプレート振動を避けるために、初期レイヤーの旅行動作のジャークは、押し出し動作のジャークよりも高く設定することができますが、それでも異なるレイヤーの旅行動作のジャークよりも低く設定することができます。

---

Initial Layer Travel Jerk
====
### **Description**
This setting determines the speed at which the nozzle can go through corners while travelling across the build plate during the initial layer. This can be configured separately from the extrusion moves during the initial layer.

### **Influence**
During the travel moves, the adhesion between the print and the build plate is not affected by vibrations. If the build plate vibrates too much, the nozzle can still rip the print off the build plate though.

### **Usage**
To avoid excessive build plate vibrations, the jerk during the travel moves of the initial layer can be set higher than the jerk during the extrusion moves, but still lower than the jerk during travel moves on different layers.