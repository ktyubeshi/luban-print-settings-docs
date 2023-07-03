最低速度
====
最低速度は、許可される最低印刷速度を設定します。この設定は、[最小層時間](cool_min_layer_time.md)を使用する層の印刷速度を制限するためのものです。

ある層が非常に小さく、通常の印刷速度で印刷すると最小層時間よりも短い時間で印刷できる場合、その層の実際の印刷速度は、層が最小層時間で印刷できるように減少します。しかし、印刷速度は最低速度以下には減少しません。最小速度で層を印刷すると最小層時間よりも短い時間で印刷できる場合、ツールヘッドは最小層時間が経過するまで層の終わりで待機します。

印刷速度があまりにも遅いと、ノズルからの熱が下の層や隣の壁に広がる時間ができます。その結果、印刷面が乱れたり、局所的に凹みが発生する可能性があります。それが最低印刷速度を設定する必要性です。

---

Minimum Speed
====
Minimum Speed configures the lowest printing speed that is allowed. This setting is to limit the printing speed of layers that use the [Minimum Layer Time](cool_min_layer_time.md).

If a layer is so small that it would take less than the Minimum Layer Time to print at regular printing speed, then its actual printing speed will be reduced so that the layer still takes the Minimum Layer Time to print. But the printing speed will not be reduced below the Minimum Speed. If printing the layer at the minimum speed would take less than the Minimum Layer Time, the toolhead will wait at the end of the layer until the Minimum Layer Time has passed.

If the printing speed is too slow, the heat from the nozzle will have time to spread out to lower layers and adjacent walls. As a result, the print surface may become messy and localised sagging may happen. That is why we need to set a minimum printing speed as a limit. 