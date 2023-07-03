上/下線の幅
====
### **説明**
上/下線の幅とは、描かれる上部および下部のすべての線の幅を指します。 線の幅は、必要な量よりも多くまたは少なく材料を押出することによってノズルサイズとは異なることができます。 もしもっと材料を押出すると、プラスチックは側面に流れ込み、線が太くなります。 もし材料を押出する量が少ない場合、材料の表面張力が材料をノズルの経路の中心線に引き寄せようとします。

![The skin lines are significantly wider than the rest](../images/skin_line_width.png)

### **影響**
スキンラインを広げることは、オブジェクトの上部と下部を印刷するために必要な行数を減らす簡単な方法です。 しかし、この設定をあまりにも大きくすると、大きな押出変動が発生します。 これは、スキンを印刷する際にアンダーエクストルージョンが発生し、次に印刷されるものについてはオーバーエクストルージョンが発生する可能性があるためです。ノズルの流れが十分に早く調整できないからです。 スキンラインの幅を増やすと、表面に穴が現れる可能性が高くなり、水密性を持たない印刷物になってしまいます。

### **使用法**
スキンラインの幅を縮小すると、より良い上面が得られますが、印刷時間が大幅に増加します。 [アイロニング](../shell/ironing_enabled.md)などの別の技術を使用するか、[Top Surface Skin Lines](../experimental/roofing_line_width.md)を調整することがより効果的です。


skin_line_width.md

-----------------

Top/Bottom Line Width
====
### **Description**
The Top/Bottom Line Width refers to the width of every line of the top and bottom being drawn. The width of a line can be different from the nozzle size simply by extruding more or less material than needed. If more material is extruded, the plastic will flow towards the sides, making the line thicker. If less material is extruded, the surface tension of the material tends to pull the material towards the centre line of the nozzle's path.

![The skin lines are significantly wider than the rest](../images/skin_line_width.png)

### **Influence**
Making the skin lines wider is an easy way to reduce printing time, because fewer lines will be necessary to print the top and bottom sides of the object. However, increasing this setting too much can cause great extrusion fluctuations. This will cause underextrusion when printing the skin and overextrusion when printing whatever comes next, because the flow through the nozzle cannot adjust fast enough. Increasing the skin line width will also increase the chance of holes to appear in the surface, which is not pretty and prevents the print from being water tight.

### **Usage**
Reducing the width of the skin lines tends to produce a nicer top surface, but significantly increases the printing time. It is often more effective to use a different technique such as [Ironing](../shell/ironing_enabled.md) or only adjusting the [Top Surface Skin Lines](../experimental/roofing_line_width.md).