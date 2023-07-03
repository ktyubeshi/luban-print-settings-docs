インフィルレイヤーの厚さ
====
**説明**
この設定により、複数の塗りつぶしレイヤーが結合されます。この設定を有効にすると、ツールヘッドは一部のレイヤーで塗りつぶしを印刷しない代わりに、最も高い結合レイヤーでより多くの材料を押出します。

レイヤービューでは、塗りつぶし線がかなり広がったように見えます。実際に印刷すると、塗りつぶし線は水平方向に広がる代わりに下に落ちます。

![Infill Layer Thickness is set to three times the layer height](../images/infill_sparse_thickness.png)

**使用法**
塗りつぶしのレイヤーの高さは視覚的な品質には重要ではないため、印刷時間を短縮するために厚いレイヤーを使用できます。

Infill Layer Thicknessは通常のレイヤーの高さの倍数である必要があります。そうでなければ、この設定は最も近いレイヤーの高さに丸められます。

* この設定をあまり大きくしすぎないように注意してください。塗りつぶしの開始と終了の間で、ノズルからの流量は加速したり減速したりする必要があります。加速と減速には少し遅れがあるため、塗りつぶしの開始時にノズルから少なすぎる材料が押出され、塗りつぶしの終了後には多すぎる材料が押出されます。
* 隣接するレイヤーに塗りつぶしがないレイヤーでは、ツールヘッドは低いレイヤーの高さで塗りつぶしを印刷し続けます。これにより傾斜壁に沿って小さな塗りつぶし線が印刷される可能性があります。


infill_sparse_thickness.md


----------------------

Infill Layer Thickness
====
### **Description**
This setting causes multiple infill layers to be combined together. When this setting is enabled, the toolhead will then not print any infill on some of the layers, but in the highest of the combined layers it will extrude more material to make up for it.

In layer view, it will look as if the infill lines have become much wider. When actually printed, the infill lines will drop down further instead of spreading out horizontally.

![Infill Layer Thickness is set to three times the layer height](../images/infill_sparse_thickness.png)

### **Usage**
Since the layer height of the infill is not important for visual quality, you can use thicker layers for the infill to reduce the printing time. 

The Infill Layer Thickness must be a multiple of the ordinary layer height. Otherwise, this setting will be rounded to the closest layer height.

* Be careful with increasing this setting too much. When switching to and from infill, the flow rate through the nozzle needs to accelerate and decelerate significantly. There is some delay on the acceleration and deceleration, so the nozzle will extrude too little at the beginning of the infill and too much after the end of the infill.
* In the in-between layers, the toolhead will still print infill with a lower layer thickness where there is no infill in the layers around it. This can cause small lines of infill to be printed alongside sloping walls.