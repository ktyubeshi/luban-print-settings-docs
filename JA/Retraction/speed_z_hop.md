Z ホップ速度
====
### **説明**
この設定は、Zホップでの垂直移動の速度を設定します。 Zホップの水平移動には影響しない、それらは[移動速度](speed_travel.md)によって設定されます。

![垂直移動はZホップ速度で行われます](../images/speed_z_hop.svg)

### **影響**
ほとんどのプリンターでは、Z軸は頑丈に作られていますが、移動速度は遅いです。 Zホップ速度を上げると、Z軸の移動の限界をテストすることになり、その結果、Zモーターが一部のステップをスキップする可能性があります。その結果、ノズルはZホップ後に異なる高さになる可能性があります。 この速度を下げると、そのようなことが起こる可能性が減ります。

一方、Zホップ速度を上げると、ノズルが印刷面からより速く動きます。これにより、ブロブのサイズを小さくすることができます。

低いZ軸加速度のため、Zホップの高さが非常に高いか、速度が非常に低い場合でないと、希望するZホップ速度が達成されることは稀です。

---

Z Hop Speed
====
### **Description**
This setting configures the movement rate at which the vertical movements are made in a Z Hop. The horizontal movements of a Z Hop are unaffected, since those are configured by the [Travel Speed](speed_travel.md).

![The vertical movement is made at the Z Hop Speed](../images/speed_z_hop.svg)

### **Influence**
For most printers, the Z axis is built to be sturdy but slow. Increasing the Z Hop Speed will test the limits of the Z movement, which can cause the Z motor to skip some steps. As a result, the nozzle could end up at a different height after the Z hop. Reducing this speed reduces the chances of that happening.

On the other hand, a greater Z Hop Speed will make the nozzle move away from the printed surface more quickly. This can reduce the size of blobs.

Due to low Z-axis acceleration rates, it is uncommon that the desired Z Hop Speed is reached unless the Z Hop height is very high or the speed very low.