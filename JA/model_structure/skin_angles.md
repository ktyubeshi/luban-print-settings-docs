上/下線の方向指定
====
### **説明**
この設定は、上部と下部のラインが印刷される方向を変更することができます。この設定は、直線とジグザグパターンの両方に適用されます。

角度（度単位）のカンマ区切りリストを指定すると、ラインの方向が層ごとに交互に変わります。例えば、**[0,90,180,270]**を設定すると、ラインは層ごとに90°回転します。

![0°, 60°, 120°の角度が交互に変わるラインパターン](../images/skin_angles.gif)

デフォルトでは、ラインは2つの対角方向に印刷されます。カルテジアンガントリシステムの場合、これが最も正確です。なぜなら、プリンターは次のラインに向けてノズルを加速するためにXモーターとYモーターの両方を使用することができるからです。

### **影響**
これらの方向を変更する理由はいくつかあります：
* 光学的な効果を得るため。
* 強度を最適化するため。
* オーバーハングを減らすため。インフィルに対して垂直な方向を選択することも可能です。これにより、インフィル上のオーバーハングを最小化し、より良いトップ面の品質を実現することができます。

---

Top/Bottom Line Directions
====
### **Description**
This setting allows you to change the direction in which the lines of the top and bottom are printed. This setting applies to both Lines and Zigzag patterns.

You can specify a comma-separated list of angles (in degrees), and the lines will alternate directions per layer. For example, you can set **[0,90,180,270]**, and the lines will rotate by 90° per layer.

![Lines pattern with 0°, 60° and 120° angles alternating](../images/skin_angles.gif)

By default, lines are printed in the two diagonal directions. For Cartesian gantry systems this is the most accurate, because the printer can use both the X and Y motors to accelerate the nozzle when turning around for the next line.

### **Influence**
There can be several reasons to change these directions:
* To achieve an optical effect.
* To optimise strength.
* To reduce overhang. You can also choose a direction that is perpendicular to the infill. This can minimise overhang over infill and achieve a better top surface quality.