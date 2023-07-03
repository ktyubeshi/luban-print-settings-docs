サポートインフィルレイヤー厚さ
====
### **説明**
サポートの視覚的な品質や解像度が重要でないため、サポートを印刷する際に厚いレイヤーを使用して印刷時間を短縮できます。この設定は、サポートが印刷されるレイヤーの厚さを設定します。

レイヤー表示では、サポートラインがかなり広くなったように見えます。実際に印刷すると、サポートラインは水平方向に広がる代わりにより下に落ちます。

![サポートインフィルレイヤー厚さがレイヤー高さの3倍に設定されています](../images/support_infill_sparse_thickness.png)

### **使用法**
サポートインフィルレイヤー厚さは、通常のレイヤー高さの倍数でなければなりません。そうでない場合、サポートインフィルレイヤー厚さは最も近いレイヤー高さに丸められます。

この設定は、サポートの屋根や床には適用されません。サポートの主体構造にのみ適用されます。

この設定は、印刷物の残りの部分と異なる材料でサポートを印刷する場合に特に便利です。そして、その材料が押出しにくい（PVAなど）場合には、さらに便利です。サポートがすべてのレイヤーで押出しされないため、プリンターはより頻繁にエクストルーダーを切り替える必要がなくなり、多くの時間を節約できます。レイヤーが印刷されるときにより多くの材料が押出されるため、流れを開始するのに時間がかかる材料はより信頼性の高い印刷が可能になります。

これをあまり大きくしすぎないように注意してください。サポートへの移行と復帰時に、ノズルを通しての流量が劇的に加速・減速する必要があります。加速・減速には一定の時間差があるため、サポートの開始時にノズルから少なすぎる量が押出され、サポートの終了後に多すぎる量が押出される可能性があります。

support_infill_sparse_thickness.md

----------------

Support Infill Layer Thickness
====
### **Description**
Since the visual quality and resolution of support is not important, you can use thicker layers for the support to reduce printing time. This setting configures how thick the layers will be that the support is printed with.

In layer view, it will look as if the support lines have become much wider. When actually printed, the support lines will drop down further instead of spreading out horizontally.

![Support Infill Layer Thickness is set to three times the layer height](../images/support_infill_sparse_thickness.png)

### **Usage**
The Support Infill Layer Thickness must be a multiple of the ordinary layer height. Otherwise, the Support Infill Layer Thinkness will be rounded to the closest layer height.

This setting does not apply to the support roof or floor, only to the main structure of the support.

This setting is particularly useful when printing the support with a different material as the rest of the print, and even more when that material is hard to extrude, such as PVA. Because the support is not extruded on every layer, the printer won't need to switch extruders as often, saving a lot of time. Because more material is extruded on layers that are printed, materials that take some time to get the flow starting will be printed more reliably.

Be careful with increasing this too much. When switching to and from support, the flow rate through the nozzle needs to accelerate and decelerate significantly. There is some delay on the acceleration and deceleration, so the toolhead will extrude too little at the beginning of the support and too much after the end of the support.