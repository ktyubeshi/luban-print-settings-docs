プリントアクセラレーション
====
### **説明**
この設定は、開始、停止、または方向転換時のツールヘッドの加速率を指します。車と同じように、ツールヘッドは速度または方向を変更するために加速する必要があります。

![ノズルを前後に移動させるときの時間経過による速度（V）のグラフ。加速は、開始、停止、または方向転換をするときの線の傾きです。](../images/velocity_acceleration_jerk.svg)

### **影響**
この設定を増やすと次の二つの効果があります：
* ツールヘッドは目標の速度と方向に早く到達するため、特に小さなパーツを印刷するときに印刷速度が速くなります。

* 振動が多くなり、これにより寸法精度が低下し、リングが発生する可能性があります。

---

Print Acceleration
====
### **Description**
This setting refers to the acceleration rate of toolhead towards the desired velocity when starting, stopping or changing direction. Just like a car, the toolhead needs to accelerate in order to change its speed or direction.

![A graph of the speed (V) over time when moving a nozzle back and forth. Acceleration is the slope of the line when it is starting, stopping or changing direction.](../images/velocity_acceleration_jerk.svg)

### **Influence**
Increasing this setting has the following two effects:
* The toolhead will reach the desired speed and direction sooner, which ensures faster print, especially when printing small parts.

* More vibrations will occur, which will reduce dimensional accuracy and cause ringing.