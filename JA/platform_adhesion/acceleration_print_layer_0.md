初期レイヤー印刷加速度
====
### **説明**
この設定は、第一層で押し出しながらノズルがどれだけ速く異なる方向に加速するかを制御します。

### **影響**
高速での印刷加速はプリンタの振動を引き起こす可能性があります。特に、これらの振動はビルドプレートを上下に揺らすことがあり、これはビルドプレート上の印刷の接着にとって有害です。第一層の加速度を減らすことで、印刷プロセスのこの重要な部分での振動を減らすことが可能です。ただし、印刷にはより多くの時間がかかりますし、加速度をあまりにも多く減らすと、角部での押し出しが不一致になり、これもビルドプレートの接着にとって有害です。

### **使用方法**
最初のレイヤーの加速度は、印刷の残りの部分とは異なるレートに設定することができ、押し出し移動中の加速度は移動中の加速度とは異なるレートに設定することができます。

壁、プラットフォーム接着、底部、サポート、インフィルはすべて異なる加速度を持つことがありますが、初期レイヤーでは同じにされます。初期レイヤーの加速度は個々の構造の加速度を上書きします。[スカート/ブリム加速度](acceleration_skirt_brim.md) の設定は、初期レイヤーの印刷加速度を再度上書きします。

---

Initial Layer Print Acceleration
====
### **Description**
This setting controls how fast the nozzle accelerates into different directions while extruding in the first layer. 

### **Influence**
Printing at high rates of acceleration can cause vibrations of the printer. In particular, these vibrations can make the build plate shake up and down, which is detrimental to the adhesion of the print on the build plate. Reducing the acceleration for the first layer can reduce vibrations during this critical part of the printing process. It will take more time to print though, and reducing the acceleration rates too much can cause inconsistent extrusion in the corners which is also detrimental to build plate adhesion.

### **Usage**
The acceleration during the first layer can be set to a different rate than the rest of the print and the acceleration during the extrusion moves can be set to a different rate than the acceleration during travel moves.

While the walls, platform adhesion, bottoms, support and infill may all have different rates of acceleration, during the first layer they will be made the same. The initial layer acceleration rate will override the individual structures' acceleration rates. The [Skirt/Brim Acceleration](acceleration_skirt_brim.md) setting overrides the initial layer print acceleration again.

