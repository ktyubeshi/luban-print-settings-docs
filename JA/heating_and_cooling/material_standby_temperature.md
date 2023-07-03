待機温度
====
### **説明**
待機温度は、デュアル押出印刷中の待機ノズルの温度です。

複数の押出機を持つプリンターでは、各押出機に対して待機温度を設定することができます。デュアル押出印刷中には、一つの押出機が印刷に忙しいとき、他の非アクティブな押出機はその待機温度を用います。

![青い押出機が印刷している間、赤い押出機は待機温度まで冷却します](../images/temperature_regulation.svg)

### **使用方法**
一般的に、待機温度は印刷温度よりも低く設定されます。これは、ノズルから無駄に多くの材料がにじみ出すのを防ぐためです。

また、ノズルの温度が高いまま押出機のモーターが動かないと、熱が後方および上方に広がり、モーター内部のフィラメントが溶ける可能性があります。この場合、ギアはフィラメントをノズルを通して押し出すことができず、フィラメントに穴をあけます。これを「熱クリープ」と呼び、ノズルが詰まる原因となります。

しかし、待機温度が低すぎると、他の押出機が作業を終えた後、押出機が印刷を続けるために再度加熱するのに時間がかかります。

---

Standby Temperature
====
### **Description**
Standby Temperature is the temperature of the stand-by nozzle during dual extrusion printing.

For printers that have more than one extruders, you can set Standby Temperature for each extruder. During dual extrusion printing, when one extruder is busy printing, the other extruder being inactive will use its standby temperature.

![While the blue extruder is printing, the red extruder cools down to the stand-by temperature](../images/temperature_regulation.svg)

### **Usage**
Generally, the Standby Temperature is set lower than the Printing Temperature. This is to prevent the nozzle from oozing out too much material in vain. 

Besides, if the nozzle temperature remains high while the extrusion motor does not move, the heat might extend back and upwards, melting the filament inside the motor. In this case, the gear will not be able to push forward the filament through the nozzle but chew a spot in the filament. This is known as “heat creep” and will cause your nozzle to clog.

However, if the Standby Temperature is set too low, the extruder will need more time to heat up to continue printing when the other extruders are done.

