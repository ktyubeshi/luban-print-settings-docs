塗り線の幅
====
### **説明**
塗り線の幅とは、描かれる塗りの線の幅を指します。

![塗りの線は他のものよりもはるかに太い](../images/infill_line_width.png)

### **影響**
線の幅は、必要な量よりも多くの材料を押出することでノズルサイズとは異なることができます。もし材料を多く押出すると、プラスチックは側面に流れて、線が太くなります。材料を少なく押出すると、材料の表面張力がノズルの経路の中心線に材料を引っ張ります。

### **使用法**
塗りの線を太くすることで、印刷物の強度が上がり、印刷時間も短縮されます。しかし、この設定をあまりに大きくすると、押出量の変動が大きくなります。これは、塗りを印刷する際に押出不足が起こり、塗りの後に何かを印刷する際には押出過剰が起こる可能性があります。なぜなら、ノズルの流量が十分に調整できないからです。

**[塗り層の厚さ](../infill/infill_sparse_thickness.md)の設定を変更した場合、実際の塗りの線はこの設定よりも太くなる可能性があります。**


infill_line_width.md

---

Infill Line Width
====
### **Description**
The Infill Line Width refers to the width of every line of infill being drawn. 

![The infill lines are significantly wider than the rest](../images/infill_line_width.png)

### **Influence**
The width of a line can be different from the nozzle size simply by extruding more or less material than needed. If more material is extruded, the plastic will flow towards the sides, making the line thicker. If less material is extruded, the surface tension of the material tends to pull the material towards the centre line of the nozzle's path.

### **Usage**
Making the infill lines wider can make your print stronger and reduce printing time as well. However, increasing this setting too much can cause great extrusion fluctuations. This will cause underextrusion when printing the infill and overextrusion when printing whatever comes after infill, because the flow through the nozzle cannot adjust fast enough.

**The actual infill lines may come out wider than what this setting says, if you've adjusted the [Infill Layer Thickness](../infill/infill_sparse_thickness.md) setting.**