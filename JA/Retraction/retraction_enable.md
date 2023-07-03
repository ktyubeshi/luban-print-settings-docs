リトラクションを有効にする
====

### **説明**
3Dプリンターが材料を押し出すのを停止しても、ノズルの端から材料がすぐに流れるのを止めることはできません。ノズル内の残留材料は流れ続けます。材料の流れを実際に停止させるには、プリンターがノズルの開口部から材料を後退させる必要があります。これは、弦のないクリーンな移動を行うために必要です。

![リトラクション無効化](../images/retraction_enable_disabled.png)
![後退した移動はより淡い青として表示される](../images/retraction_enable_enabled.png)

リトラクションを有効にすると、エクストルーダーは特に弦に敏感な移動を行う際に材料を後退させます。インフィルを通り抜けたりサポートからサポートへ移動するだけの場合、エクストルーダーは後退を実行しません。また、材料が後退できる頻度には限界があり、[最大リトラクション数](retraction_count_max.md)および [最小押出距離ウィンドウ](retraction_extrusion_window.md)の設定を通じて制御されます。

リトラクションの利点
* 弦を大幅に減らすことができます。
* ノズルがパートの周囲に入る表面上のブロブの量とサイズを大幅に減らすことができます。

リトラクションの欠点
* 後退するのに少し時間がかかります。
* リトラクションが発生すると材料の流れが中断されます。これは次元精度に悪影響を与え、不足押出しにつながる可能性があります。
* リトラクションが多すぎるとフィラメントが摩耗し、フィーダーが材料をつかむことができなくなる可能性があります。

### **使用方法**
柔軟な材料は後退させるのが難しく、フィラメントを引っ張るとノズル先端から後退する代わりにフィラメントが伸びます。そのため、このような材料でリトラクションを有効にすると、非常に時間がかかることもあれば、あまり効果的でないこともあります。

---

Enable Retractions
====
### **Description**
When a 3D printer stops pushing material, the material won't immediately stop flowing from the end of the nozzle. The residual material in the nozzle will keep oozing out. To actually stop the material from flowing, the printer needs to retract the material backward from the nozzle opening. This is necessary to make clean travel moves without stringing.

![Retractions disabled](../images/retraction_enable_disabled.png)
![Retracted travel moves show as a lighter blue](../images/retraction_enable_enabled.png)

After you enable retractions, the extruder will retract material while making travel moves that are particularly sensitive to stringing. For travel moves that only pass through infill or from support to support, the extruder will not perform retraction. There is also a limit to how often the material can be retracted, through the [Maximum Retraction Count](retraction_count_max.md) and [Minimum Extrusion Distance Window](retraction_extrusion_window.md) settings.

Advantages of Retraction
* It'll reduce stringing significantly.
* It will significantly reduce the amount and size of blobs on the surface where the nozzle enters the perimeter of a part.

Disadvantages of Retraction
* It takes a bit of time to retract.
* The material flow gets interrupted when a retraction happens. This has negative consequences for dimensional accuracy, and may lead to underextrusion.
* The filament could wear down when too many retractions happen, preventing the feeder from gripping the material.

### **Usage**
Flexible materials are harder to retract, because pulling on the filament makes the filament stretch instead of retracting backward from the nozzle tip. It may be very time consuming and relatively ineffective to enable retraction with such materials.

