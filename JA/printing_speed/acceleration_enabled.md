加速度制御を有効にする
====
### **説明**
この設定は、ツールヘッドがどのような速度で動くかを構成します。

![ノズルを前後に移動したときの速度（V）の時間グラフ。加速度は、線が始まり、停止したり方向を変えたりするときの傾斜です。](../images/velocity_acceleration_jerk.svg)

### **影響**
この設定を増やすと、以下の2つの効果があります。
* ツールヘッドは、特に小さい部品を印刷するときにより迅速に目的の速度に達するため、より早く印刷が行われます。

* 振動が発生し、寸法精度が低下し、リンギングが発生する可能性があります。

### **使用法**
通常、プリンタはツールヘッドがどのような速度で方向を変え、速度を変えるかを自動的に決定しますが、この設定を有効にすると、Lubanが代わりに決定することができます。これにより、印刷の特徴ごとに異なる加速度を設定することができます。

----

Enable Acceleration Control
====
### **Description**
This setting configures how fast the toolhead should accelerate. 

![A graph of the speed (V) over time when moving a nozzle back and forth. Acceleration is the slope of the line when it is starting, stopping or changing direction.](../images/velocity_acceleration_jerk.svg)

### **Influence**
Increasing this setting have the following two effects:
* The toolhead will reach the desired speed sooner, which ensures faster print, especially when printing small parts. 

* More vibrations will occur, which will reduce dimensional accuracy and cause ringing.

### **Usage**
Normally the printer decides by itself how fast the toolhead should change direction and speed, but if this setting is enabled, Luban can decide this instead, which allows you to set different acceleration rates for each feature of a print.