初期レイヤーの加速度
====
### **説明**
この設定は、最初のレイヤーを印刷する際にノズルが異なる方向にどれだけ早く加速するかを制御します。最初のレイヤーの加速度は、印刷の残りの部分とは異なるレートに設定できます。

### **影響**
高い加速度で印刷すると、プリンターが振動する可能性があります。特に、これらの振動はビルドプレートを上下に揺らす可能性があり、これはビルドプレート上の印刷の接着に悪影響を及ぼします。

最初のレイヤーの加速度を減らすことで、印刷プロセスのこの重要な部分での振動を減らすことができます。ただし、印刷にはより多くの時間がかかり、加速度をあまりにも低く設定すると、角での押出が不均一になる可能性があり、これもビルドプレートの接着に悪影響を及ぼします。

### **使用法**
壁、プラットフォームの粘着、底部、サポート、インフィルなど、すべてが異なる加速度を持つこともありますが、最初のレイヤーでは同じにされます。初期レイヤーの加速率は、個々の構造物の加速率を上書きします。旅行の移動は、[初期レイヤーの旅行加速度](acceleration_travel_layer_0.md)と[初期レイヤーの印刷加速度](acceleration_print_layer_0.md)の設定を通じて、押出の動きよりも異なる加速度を持つことがあります。[スカート／ブリム加速度](acceleration_skirt_brim.md)の設定は、初期レイヤーの印刷加速度を上書きします。

---

Initial Layer Acceleration
====
### **Description**
This setting controls how fast the nozzle accelerates into different directions while printing the first layer. The acceleration during the first layer can be set to a different rate than the rest of the print.

### **Influence**
Printing at high rates of acceleration can cause vibrations of the printer. In particular, these vibrations can make the build plate shake up and down, which is detrimental to the adhesion of the print on the build plate. 

Reducing the acceleration for the first layer can reduce vibrations during this critical part of the printing process. It will take more time to print though, and reducing the acceleration rates too much can cause inconsistent extrusion in the corners which is also detrimental to build plate adhesion.

### **Usage**
While the walls, platform adhesion, bottoms, support and infill may all have different rates of acceleration, during the first layer they will be made the same. The initial layer acceleration rate will override the individual structures' acceleration rates. The travel moves may still have a different acceleration rate from the extrusion moves through the [Initial Layer Travel Acceleration](acceleration_travel_layer_0.md) and [Initial Layer Print Acceleration](acceleration_print_layer_0.md) settings. The [Skirt/Brim Acceleration](acceleration_skirt_brim.md) setting overrides the initial layer print acceleration as well.


