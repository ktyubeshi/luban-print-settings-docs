Travel Jerk
====
### **説明**
この設定は、ビルドボリュームを横断している間にノズルがコーナーを通過する速度を決定します。

### **影響**
ジャークをあまりに高く設定すると、モーターがいくつかのステップを失う可能性があり、レイヤーシフトを引き起こす可能性があります。

### **使用法**
Lubanを[旅行中に印刷物を回避するように構成した場合](../travel/travel_avoid_other_parts.md)、[距離](../travel/travel_avoid_distance.md)を十分に保つことで、ノズルが印刷物に衝突することを防ぐことができます。したがって、旅行移動中にジャークを非常に高く設定して印刷時間を節約するのに役立ちます。

この設定は、ノズルが材料を押出しているときとは別に構成することができます。

jerk_travel.md

----

Travel Jerk
====
### **Description**
This setting determines the speed at which the nozzle can go through corners while travelling across the build volume. 

### **Influence**
Setting the jerk too high can cause the motors to lose some steps, which can lead to a layer shift.

### **Usage**
If you've configured Luban to [avoid printed parts when travelling](../travel/travel_avoid_other_parts.md), then keeping a sufficient [distance](../travel/travel_avoid_distance.md) will prevent the nozzle from hitting your print even if it vibrates a bit. It's therefore useful to set the jerk very high during the travel moves to save printing time.

This setting can be configured separately from when the nozzle is extruding material.