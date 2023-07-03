最小層時間
====
### **説明**
最小層時間は、許容されるプリント層の最短時間を設定します。プリンタは、この時間より短い時間で層をプリントすることは許されません。

これにより、小さな層は次の層が上に乗せられる前に十分に冷却・固化されるため、たわみが防止されます。

![どのファン速度がどこで使われるか](../images/cool_fan_speed.svg)

### **使用方法**
もしレイヤーがあまりにも小さく、通常のプリント速度でプリントすると最小レイヤー時間より短い時間でプリントされてしまう場合、その実際のプリント速度はレイヤーが最小レイヤー時間でプリントされるように低下します。ただし、プリント速度は[最小速度](cool_min_speed.md)設定より低くなることはありません。最小速度でレイヤーをプリントすると最小レイヤー時間よりも短い時間になる場合、ツールヘッドは最小レイヤー時間が経過するまでレイヤーの終了位置で待機します。

最小層時間でプリントされる層では、ツールヘッドは層を速く冷却するために[最大ファン速度](cool_fan_speed_max.md)を使用します。

---

Minimum Layer Time
====
### **Description**
Minimum Layer Time configures the shortest duration of printing a layer that is allowed. The printer is not allowed to print a layer using any less time than this.

This ensures that a small layer has enough time to cool down and solidify before the next layer gets put on top of it, and therefore prevents sagging.

![Which fan speed is used where](../images/cool_fan_speed.svg)

### **Usage**
If a layer is so small that it would take less than the Minimum Layer Time to print at regular printing speed, then its actual printing speed will be reduced so that the layer still takes the Minimum Layer Time to print. But the printing speed will not be reduced below the [Minimum Speed](cool_min_speed.md) setting). If printing the layer at the minimum speed would take less than the Minimum Layer Time, the toolhead will wait at the end of the layer until the Minimum Layer Time has passed.

For a layer that is printed with the minimum layer time, the toolhead will use the [Maximum Fan Speed](cool_fan_speed_max.md) so as to cool down the layer faster.