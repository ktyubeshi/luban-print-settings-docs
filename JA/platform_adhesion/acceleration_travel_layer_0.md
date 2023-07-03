初期層の移動加速度
====
### **説明**
この設定は、ノズルが最初の層の間にビルドプレートを横切りながら様々な方向に加速する速度を制御します。

### **影響**
高加速度での印刷はプリンタの振動を引き起こす可能性があります。特に、これらの振動によりビルドプレートが上下に振動し、その結果、ノズルがビルドプレートに当たりプリンタが損傷する可能性があります。

また、振動は旅行動作が終了した後も続き、押出に影響を及ぼす可能性があります。これは、モデルとビルドプレートの間の接着力に悪影響を与えます。

最初の層の旅行動作の加速度を他の層と比較して減少させることで、これらの影響を防ぐことができます。ただし、時間を節約するために、振動は通常、押出の間だけ問題となるため、最初の層の間の移動中に加速度は最初の層の押出動作よりも高くすることができます。

### **使用法**
最初の層の移動中の加速度は、プリントの残りの部分の移動動作や最初の層の押出動作とは異なるレートに設定できます。

---

Initial Layer Travel Acceleration
====
### **Description**
This setting controls how fast the nozzle accelerates into different directions while travelling across the build plate during the first layer. 

### **Influence**
Printing at high rates of acceleration can cause vibrations of the printer. In particular, these vibrations can make the build plate shake up and down, which can cause the nozzle to hit the build plate and damage the printer. 

The vibrations can also continue on after the travel move and affect extrusion, which is detrimental to the adhesion between the model and the build plate. 

Reducing the acceleration of travel moves during the first layer compared to other layers can prevent these effects. However to save time, the acceleration during travelling in the first layer can still be higher than during the extrusion moves of the first layer, because vibrations are usually only a problem while extruding.

### **Usage**
The acceleration during travels on the first layer can be set to a different rate from the travel moves in the rest of the print or the extrusion moves of the first layer.






