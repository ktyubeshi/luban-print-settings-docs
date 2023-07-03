初期レイヤー速度
====
### **説明**
この設定は、モデルの初期レイヤーが形成される速度を調整します。

### **使用法**
初期レイヤー速度を減らすと、モデルとビルドプレートとの間の密着性が向上します。これは、材料が長期間熱を保持し、その結果、さらに流れ出ることができるためです。これは密着性を高めることができます。

初期レイヤーでは、[印刷速度](speed_print_layer_0.md)は[移動速度](speed_travel_layer_0.md)とは別に調整することができます。また、[縁取りとスカート](skirt_brim_speed.md)の印刷速度も調整できます。デフォルトでは、この設定はそれらすべてに影響を与えます。しかし、[ラフトの基底層の速度](../platform_adhesion/raft_base_speed.md)には影響を与えません。

---

Initial Layer Speed
====
### **Description**
This setting adjusts the speed at which the initial layer of the model is formed.

### **Usage**
Reducing the initial layer speed will improve the adhesion between the model and the build plate. This is because the material stays hotter for a longer time and can then flow out further, which can increase the adhesion.

For the initial layer, the [printing speed](speed_print_layer_0.md) can be adjusted separately from the [travel speed](speed_travel_layer_0.md). The speed at which the [brim and skirt](skirt_brim_speed.md) is printed can also be adjusted. By default, this setting affects all of those. However the [speed of the base layer of the raft](../platform_adhesion/raft_base_speed.md) is not affected.
