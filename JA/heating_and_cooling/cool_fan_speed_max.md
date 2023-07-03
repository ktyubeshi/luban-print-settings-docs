最大ファン速度
====
### **説明**
ミニマムレイヤータイムでレイヤーが印刷されるときに、ツールヘッド内のファンがどの速さで回転するかを表します。

![どのファン速度がどこで使用されるか](../images/cool_fan_speed.svg)

Lubanは各レイヤーの印刷時間を計算し、それによってそのファン速度を決定します。レイヤーの印刷時間が最小レイヤータイムより長く、一方でレギュラー/最大ファン速度閾値より短い場合、そのレイヤーのファン速度は次のように計算されます：

レイヤーのファン速度 = 最大ファン速度 - (最大ファン速度 - レギュラーファン速度) / (レギュラー/最大ファン速度閾値 - 最小レイヤータイム) × (レイヤーの印刷時間 - 最小レイヤータイム)

### **使用法**
最大ファン速度を使用することで、印刷時間の短い層はより速く冷却し、次の層が上に乗せられる前に固化することができます。これにより、たわみの防止が可能となります。

---

Maximum Fan Speed
====
### **Description**
The speed at which the fans in the toolhead will spin when the layer is printed with the Minimum Layer Time.

![Which fan speed is used where](../images/cool_fan_speed.svg)

Luban will calculate the printing time of each layer so as to determine its fan speed. If the printing time of a layer is larger than the Minimum Layer Time but smaller than the Regular/Maximum Fan Speed Threshold, then the fan speed of this layer is calculated as follows:

Fan Speed of the Layer = Maximum Fan Speed - (Maximum Fan Speed - Regular Fan Speed)/(Regular/Maximum Fan Speed Threshold - Minimum Layer Time) × (Printing Time of the Layer - Minimum Layer Time)

### **Usage**
By using the Maximum Fan Speed, layers whose printing time is short can cool down faster and solidify before the next layer gets put on top of it, and therefore prevents sagging.