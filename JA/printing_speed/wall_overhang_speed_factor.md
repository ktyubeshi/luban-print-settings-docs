# オーバーハングウォールスピード
### **説明**
この設定では、[オーバーハングウォール](wall_overhang_angle.md)を印刷する速度を調整できます。速度は、[外壁スピード](../speed/speed_wall_0.md)または[内壁スピード](../speed/speed_wall_x.md)のいずれかの普通の印刷速度の比率として設定されます。
低速でオーバーハングを印刷すると、ドロープを減らす効果があります。これには、プリントに対して複数のポジティブな効果があります。
* 壁は、前のレイヤーの隣接する壁によりよく取り付けられるようになります。これは、ドロープを減らすのに役立ちます。
* ファンスピードが高く設定されている場合、ファンはフィラメントをより早く冷やす時間を得ます。これにより、材料はより早く固まります。印刷速度が高い場合、材料はより長い時間ドロープダウンします。
* オーバーハング内の材料は、ノズルから出てくるビーズにまだ接続されています。低速で印刷すると、固化中にノズルは近くに留まります。つまり、材料に対するノズルのプルの効果がより高くなり、固化中にビーズを高く保つことができます。

しかし、低速（または異なる速度）でオーバーハングを印刷すると、負の効果もあります。
* 印刷が完了するのに明らかに時間がかかります。
* 印刷速度が異なる境界部分は、外側で非常に目立つ可能性があります。これは、プリントに望ましくない可視的な境界を導入します。
* 速度を低下させると、ノズル室内の圧力が高くなるため、一時的にノズルから過押出が発生する可能性があります。これは、ブリップを引き起こしたり、オーバーハングの品質を悪くする可能性があります。速度を上げると、不足押出が発生します。一般的に、この技術は小さなオーバーハング領域よりも大きな領域によりよく機能します。

wall_overhang_speed_factor.md

--------

Overhanging Wall Speed
====
### **Description**
With this setting, the speed can be adjusted at which [overhanging walls](wall_overhang_angle.md) are printed. The speed is set as a ratio of their normal print speed, which is either the [Outer Wall Speed](../speed/speed_wall_0.md) or the [Inner Wall Speed](../speed/speed_wall_x.md).

Printing overhang at lower speeds can be very effective to reduce droop. This has a number of positive effects on your print.
* The walls get more time to attach to adjacent walls in the previous layer. This helps them stay upright better, which reduces droop.
* If your fan speed is set up high, the fans get more time to cool down the filament. This makes it solidify faster. If the printing speed were high, the material gets more time to droop down.
* The material in the overhang is still connected to a bead coming out of the nozzle. When printing slower, the nozzle stays closer during the solidification, meaning that the pull of the nozzle on the material is more effective to keep the bead up high while it's solidifying.

However printing overhang at lower (or different speeds can also have negative effects):
* The print will obviously take longer to complete.
* The border where the print speed is different may be very visible on the outside. This introduces a visible border in your print which may not be desirable.
* When reducing speed, there will briefly be some overextrusion out the nozzle due to high pressure in the nozzle chamber. This can lead to blips or make the overhang quality worse. When increasing speed, there will be some underextrusion. In general this technique works better for large areas of overhang rather than small ones.