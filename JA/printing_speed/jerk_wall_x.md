内壁ジャーク
====
### **説明**
この設定は、内壁を印刷する際にノズルがコーナーを通過する速度を決定します。これは外壁とは別に設定できます。

### **使用法**
外壁から見ると、内壁はほとんど見えません。リンギングの問題があまりないフラットな上下面を除いて。しかし、[外壁の前に内壁を印刷](../shell/outer_inset_first.md)する場合、内壁の振動が特定の場所で外壁を押しよせ、外壁を完璧な精度で印刷しても外側表面にリンギングの影響が及ぶ可能性があります。

外壁を最初に印刷すると、リンギング効果が低減されます。しかし、振動するノズルが部分的に外壁を通過すると、微かなリンギングが残ります。

このため、内壁ジャークは通常、外壁ジャークよりも大きくなりますが、他の印刷物よりも小さくなります。

jerk_wall_x.md

------------------

Inner Wall Jerk
====
### **Description**
This setting determines the speed at which the nozzle can go through corners while printing the inner walls. This can be configured separately from the outer wall.

### **Usage**
The inner walls are not very visible on the outside, except on flat top and bottom sides where ringing isn't much of an issue. However, when printing the [inner walls before the outer walls](../shell/outer_inset_first.md), the vibrations in the inner walls will push the outer wall aside in certain places, causing the ringing to affect the outside surface even if the outer wall would be printed with perfect accuracy. 

If the outer wall is printed first, the ringing effect will be reduced. However, having a vibrating nozzle pass along partially over the outer wall will still cause a faint ringing.

For this reason, the inner wall jerk is normally greater than the outer wall jerk, but still less than the rest of the print.