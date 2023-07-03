水平拡張
====
### **説明**
この設定により、モデル全体がわずかに広くなるか細くなります。これは印刷プロセスの欠陥を補正するための措置です。

![元のモデル](../images/xy_offset_neutral.png)
![水平方向に拡大した場合、ネジの穴が小さくなります](../images/xy_offset_wider.png)
![負の値を設定するとモデルが縮小し、ネジの穴が大きくなります](../images/xy_offset_slimmer.png)

正の値を設定すると、印刷物が太くなります。これによりキャビティーのサイズが小さくなります。負の値を設定すると、印刷物が細くなり、キャビティーのサイズが大きくなります。

### **使用法**
印刷物の許容差が重要な場合、この設定は非常に有用です。プラスチックの歪みにより、実際の寸法がデジタルモデルの寸法と完全に一致しない可能性があります。ゲインエラーは単純にモデルをスケープすることで補正できますが、印刷方法によるオフセットエラーはこの設定で補正できます。

もしプリンタが余分な押出や動作不正確などの理由で常に広く印刷されることがわかっている場合、この設定でそれを補正することもできます。

xy_offset.md

----

Horizontal Expansion
====
### **Description**
This setting causes the entire model to be slightly wider or slimmer. It is a compensating measure for dimensional inaccuracies of the printing process.

![The original model](../images/xy_offset_neutral.png)
![Horizontally expanded, the screw holes are smaller now](../images/xy_offset_wider.png)
![A negative value shrinks the model, making the screw holes wider](../images/xy_offset_slimmer.png)

A positive value will make the print fatter. This reduces the size of cavities. A negative value will make the print slimmer and increase the size of cavities.

### **Usage**
If the tolerance of a print is important, this setting can be very useful. Due to a slight deformation of plastics, the actual dimensions of the print may not completely correspond with the dimensions of the digital model. Gain errors can be compensated for by simply scaling the model, but offset errors due to the print method can be compensated for with this setting.

If you know that your printer always prints too wide due to some overextrusion or inaccuracy in its movement, you can also compensate for that with this setting.