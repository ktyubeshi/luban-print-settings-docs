Infill Line Directions
====
## 説明
インフィルラインは通常45度の角度で方向を指定します。この角度では、一般的なカルテシアギャントリー機構を使用しているプリンタで、XおよびYモーターが最大の加速度を得るために協力しています。

この設定では、この角度を調整できます。特定のモデルの強度を高めるために特化させたり、特定のギャントリーシステムの加速度を高めるために使用することができます。

![Lines infill with default angles of 45 and 135 degrees](../images/infill_angles_45_135.png)
![Lines infill with customised angles of 0 and 30 degrees](../images/infill_angles_0_30.png)

## 使用法
この設定の値は、カンマ区切りの角度のリスト（例えば、[0,60,120]）でなければなりません。角度0度はY軸に平行なラインを生成します。角度のリストはレイヤー間で交互に使用されます。
* 最終的なプリントはインフィルラインの方向で最も強固になります。プリントが水平方向に特定の力をかける必要がある場合は、インフィルラインをその方向に向けるのが有用です。
* 空のリストを使用してデフォルト設定を使用するには、設定を空のリストにします。
* デフォルト設定はインフィルパターンによって異なります：
  * CrossおよびCross 3Dインフィルパターンの場合、デフォルト値は[22]です。これは可能な限り多くのラインを斜めに近づけます。
  * LinesおよびZigzagインフィルパターンの場合、デフォルトは[45,135]です。これにより、2つの斜め間でレイヤー間で交互に方向を変えるようになります。
  * その他のパターンはデフォルトで[45]を使用します。これにより、可能な限り多くのラインを斜めに近づけます。

infill_angles.md

 --------------------

Infill Line Directions
====
### **Description**
Infill lines are usually directed at a 45 degree angle. At this angle, both the X and Y motor work together to obtain maximum acceleration of the toolhead, when using a printer with the common Cartesian gantry mechanism.

With this setting, you can adjust this angle. You can specialise it to create greater strength for your specific model, or achieve greater acceleration for your specific gantry system.

![Lines infill with default angles of 45 and 135 degrees](../images/infill_angles_45_135.png)
![Lines infill with customised angles of 0 and 30 degrees](../images/infill_angles_0_30.png)

### **Usage**
The value of this setting needs to be a comma-separated list of angles with brackets around it (for example, [0,60,120]). An angle of 0 degrees will result in a line parallel with the Y axis. The list of angles will be alternated over the layers.
* The final print will be strongest in the directions of the infill lines. If you need the print to carry a specific force in a horizontal direction, it is useful to orient the infill lines around that direction.
* Leave the setting an empty list to use the default setting.
* The default setting depends on the infill pattern:
  * For Cross and Cross 3D infill patterns, the default value is [22]. This orients as many lines as possible close to the diagonals.
  * For Lines and Zigzag infill patterns, the default is [45,135]. This causes the orientation to alternate layer by layer between the two diagonals.
  * All other patterns use a default of [45]. This orients as many lines as possible close to the diagonals.