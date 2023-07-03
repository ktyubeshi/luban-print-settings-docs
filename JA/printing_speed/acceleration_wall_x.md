内壁の加速
====
### **説明**
この設定は、内壁を印刷するときにノズルが異なる方向へどれだけ早く加速するかを制御します。

### **影響**
この設定を調整すると、印刷物の寸法精度と一般的な滑らかさに影響します。高い加速度は、プリンタ全体に衝撃波を引き起こします。これらの衝撃波は、ノズルまたはビルドプレートが振動するときに印刷物に見られます。

内壁は外側から見えませんが、上下側を除いて、外壁よりも先に印刷すると、外壁が不正確に印刷された内壁の周りに押し出されます。外壁を最初に印刷すると、内壁の加速の影響は少なくなりますが、ノズルが通過すると外壁が再溶融するため、今でも存在します。

### **使用法**
内壁を印刷するときに、外壁よりも加速度を高くして印刷時間を節約するのが一般的ですが、他の印刷物よりも低い加速度です。

内壁の加速度は、外壁とは異なるレートに設定できます。

acceleration_wall_x.md

----

Inner Wall Acceleration
====
### **Description**
This setting controls how fast the nozzle accelerates into different directions while printing the inner walls. 

### **Influence**
Adjusting this setting will affect the dimensional accuracy and general smoothness of the print. High acceleration rates cause shock waves throughout the printer. These shock waves can be seen in the print when the nozzle or build plate vibrates. 

The inner walls are not visible from the outside except on the top and bottom side, but if they are printed before the outer walls, the outer walls get pushed more towards the outside where the inner walls were printed inaccurately. If the outer walls were printed first, the effect of inner wall acceleration is less visible, but still present due to the outer wall re-melting when the nozzle passes over.

### **Usage**
It's common to have the inner walls printed with a higher rate of acceleration than the outer walls, to save printing time, but a lower acceleration rate than the rest of the print.

The acceleration rate for the inner walls can be set to a different rate than the outer walls.