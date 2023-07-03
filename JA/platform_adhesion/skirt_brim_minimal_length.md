スカート/ブリム 最小長
====
### **説明**
スカート/ブリムの長さは、スカートまたはブリムを印刷する際にノズルをプライムするために必要な押出全長を参照します。この設定は、[スカートライン数](skirt_line_count.md)または[ブリムライン数](brim_line_count.md)の設定で最初に要求されたものよりも多くのスカートまたはブリムラインを追加することで、ノズルが印刷を開始する前に十分にプライムされることを確認します。この設定の最小長さが、追加されたすべてのスカートまたはブリムラインの総周長によって達成されない場合、さらにコンターが追加されます。

この設定の値は、この最小長さによって押し出される体積が、印刷前にノズルをプライムするのにちょうど十分な量であるように設定する必要があります。

### **使用法**
この設定が大きい場合、フチに小さなオブジェクトを置くと、プリンターが作業エリアの外側に移動する可能性があります。**

---

Skirt/Brim Minimum Length
====
### **Description**
The skirt/brim length refers to the total length of extrusion required to prime the nozzle when printing the skirt or brim. This setting makes sure that the nozzle is primed enough before starting a print, by adding more skirt or brim lines than originally requested by the [Skirt Line Count](skirt_line_count.md) or [Brim Line Count](brim_line_count.md) setting. If the minimum length in this setting is not reached by the total circumference of all the skirt or brim lines added together, more contours will be added.

The value of this setting should be set such that the volume extruded by this minimal length is just enough to prime the nozzle before a print.

### **Usage**
Placing tiny objects at the edge of your printer when this setting is large can cause the printer to move outside the working area.**

