最終印刷温度
====
### **説明**
最終印刷温度は、デュアル押出印刷において、このノズルが印刷のターンを終えて待機モードに入る際のノズルの温度を指します。

通常、最終印刷温度は通常の印刷温度よりもわずかに低く設定されます。これにより、押出機が印刷を完了する前にノズルがわずかに早く冷却します。最終印刷温度は、押出機のスイッチが行われる正確な時点で達成されます。その後、待機温度に向けて冷却を続けます。

![ノズルのスイッチが行われるときにノズルが最終印刷温度まで冷却するように、冷却開始（プレクール）のタイミングが計算されます](../images/temperature_regulation.svg)

### **使用法**
最終印刷温度が通常の印刷温度よりもわずかに低い場合、他のノズルが印刷中にノズルが待機状態で多くの材料を滴下することはありません。

---

Final Printing Temperature
====
### **Description**
Final Printing Temperature refers to the temperature of the nozzle at the time when this nozzle is about to end a turn of printing and enter stand-by mode in dual extrusion printing. 

Generally, Final Printing Temperature is set slightly lower than the normal printing temperature. In effect, this causes the nozzle to cool down slightly earlier before the extruder has completed printing. The Final Printing Temperature is reached exactly when the extruder switch happens. After that, it will continue cooling down towards the standby temperature.

![The moment to start cooling down (precool) is calculated such that the nozzle can cool down to the Final Printing Temperature when the nozzle switch happens](../images/temperature_regulation.svg)

### **Usage**
If the Final Print Temperature temperature is slightly lower than the normal printing temperature, the nozzle won't ooze as much material on standby while the other nozzle is printing.