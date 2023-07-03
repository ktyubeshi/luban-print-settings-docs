通常/最大ファン速度閾値
====
### **説明**
通常/最大ファン速度閾値は、レイヤーの印刷時間の閾値を設定することで、そのレイヤーで使用されるファンの速度を決定します。

* レイヤーの印刷時間が通常/最大ファン速度閾値と同等またはそれ以上の場合、そのレイヤーは通常のファン速度で印刷されます。

* レイヤーの印刷時間が通常/最大ファン速度閾値より短く、最小レイヤー時間より長い場合、そのレイヤーのファン速度は以下のように計算されます：

    レイヤーのファン速度 = 最大ファン速度 - (最大ファン速度 - 通常ファン速度) / (通常/最大ファン速度閾値 - 最小レイヤー時間) × (レイヤーの印刷時間 - 最小レイヤー時間)

* レイヤーが最小レイヤー時間で印刷される場合、そのレイヤーは最大ファン速度で印刷されます。

![どのファン速度がどこで使用されるか](../images/cool_fan_speed.svg)

### **使用方法**
レイヤーの印刷時間が短いと、レイヤーが適切に冷却されない可能性があります。そのため、レイヤーが固化することを確保するために、ファンの速度を上げる必要があります。

---

Regular/Maximum Fan Speed Threshold
====
### **Description**
Regular/Maximum Fan Speed Threshold configures a threshold of the layer printing time to determine the fan speed used in the layer. 

* If the printing time of a layer is equal to or larger than the Regular/Maximum Fan Speed Threshold, then this layer will be printed with the Regular Fan Speed.

* If the printing time of a layer is smaller than the Regular/Maximum Fan Speed Threshold but larger than the Minimum Layer Time, then the fan speed of this layer is calculated as follows:

    Fan Speed of the Layer = Maximum Fan Speed - (Maximum Fan Speed - Regular Fan Speed)/(Regular/Maximum Fan Speed Threshold - Minimum Layer Time) × (Printing Time of the Layer - Minimum Layer Time)

* If a layer is printed with the Minimum Layer Time, then this layer will be printed with the Maximum Fan Speed.

![Which fan speed is used where](../images/cool_fan_speed.svg)

### **Usage**
If the printing time of a layer is short, the layer may not be able to cool down properly. That's why we need to increase the fan speed to ensure that the layer is solidified.