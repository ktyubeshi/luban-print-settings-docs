初期レイヤーの印刷速度
====
### **説明**
この設定は、モデルの初期レイヤーを印刷する速度を制御します。

### **影響**
初期レイヤーの印刷速度を減らすことで、モデルとビルドプレート間の接着性が向上します。これは、材料が長時間高温の状態を保持するため、さらに流れ出すことができるからです。これにより、材料内部の応力が減少し、接触面積が増加するため、両方とも接着力が増します。

### **使用方法**
この設定を調整すると、最初のレイヤーでは押し出し動作の速度が調整されますが、移動速度は調整されません。そのためには、[初期レイヤー移動速度](speed_travel_layer_0.md)設定を調整してください。デフォルトでは、この設定は[スカート/ブリムの速度](skirt_brim_speed.md)設定に影響しますが、それでも別々に調整することができます。[ラフト基層の速度](../platform_adhesion/raft_base_speed.md)は影響を受けません。

---

Initial Layer Print Speed
====
### **Description**
This setting controls the speed when printing the initial layer of the model.

### **Influence**
Reducing the initial layer printing speed will improve the adhesion between the model and the build plate. This is because the material stays hotter for a longer time and can then flow out further. This reduces the internal stresses in the material and increases the contact area, both of which increase the adhesion.

### **Usage**
Adjusting this setting will adjust the speed of the extrusion moves in the first layer, but not the travel moves. For that, adjust the [Initial Layer Travel Speed](speed_travel_layer_0.md) setting. By default, this setting influences the [Skirt/Brim Speed](skirt_brim_speed.md) setting, but it can still be adjusted separately. The [speed of the raft base layer](../platform_adhesion/raft_base_speed.md) is not affected.
