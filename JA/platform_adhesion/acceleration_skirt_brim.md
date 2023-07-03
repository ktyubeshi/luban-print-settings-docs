スカート/ブリム加速
====
### **説明**
この設定は、スカートまたはブリムを印刷する際に、ノズルがさまざまな方向にどれだけ速く加速するかを制御します。

### **影響**
ブリムはベッド接着に重要なため、ブリムの印刷中に加速率を下げると、ブリムが印刷されている間の振動が減少し、ブリムのビルドプレートへの接着性が向上し、少ない印刷時間でブリムの効果を高めることができます。

ただし、ブリムとスカートに対する加速の影響は通常、非常に小さく、これは、ブリムとスカートが滑らかな曲線で構成されているためです。加速は、ほとんどの場合、[スカート/ブリムジャーク](jerk_skirt_brim.md)設定によって完全に引き継がれます。

### **使用法**
スカートまたはブリムの加速は、印刷全体とは異なる速度に設定できます。スカートとブリムは常に初期レイヤーに限定されていますが、この設定は [初期レイヤーの印刷加速](acceleration_print_layer_0.md)設定を上書きします。ブリムまたはスカートは、この設定で決定した加速を使用して印刷され、一般的な初期レイヤーの設定ではなく。

---

Skirt/Brim Acceleration
====
### **Description**
This setting controls how fast the nozzle accelerates into different directions while printing the skirt or the brim. 

### **Influence**
The brim is crucial for bed adhesion, so reducing the acceleration rates during the printing of the brim can reduce vibrations while the brim is printed and then make the adhesion of the brim to the build plate better, increasing the effectiveness of the brim at a minor printing time cost.

The effect of acceleration on the brim and skirt is usually extremely small though, because the brim and skirt consist of lines with smooth curves. The acceleration is often completely taken over by the [Skirt/Brim Jerk](jerk_skirt_brim.md) setting.

### **Usage**
The acceleration during the skirt or the brim can be set to a different rate than the rest of the print. Even though the skirt and brim are always exclusive to the initial layer, this setting overrides the [Initial Layer Print Acceleration](acceleration_print_layer_0.md) setting. The Brim or skirt will be printed using the acceleration determined with this setting, not the setting for the initial layer in general.



