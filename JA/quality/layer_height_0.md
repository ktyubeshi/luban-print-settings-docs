ファーストレイヤーの高さ
====
### **説明**
この設定は、プリントの最初の層の厚さを定義します。

![初期層は残りの層よりも厚い](../images/layer_height_0.png)

### **影響**
初期層の厚さを増加させると、ノズルが同じ距離でより多くの材料を押し出し、その結果、材料は全線幅を埋めるために脇へ広がるため、追加の力が必要になります。この追加の力により、材料がビルドプレートにより良く定着します。さらに、厚い層は表面の平坦性の不規則性を取り扱います。ビルドプレートが少し曲がっている場合、その変動は最初の層の厚さに吸収され、そうでなければノズルが二層目を印刷するときに最初の層を削り取る可能性があります。

### **使用法**
初期層は通常、ビルドプレートとの強い粘着性を作り出すために残りの部分よりも厚く印刷されます。この設定を使用すると、プリントの残りの部分の解像度を下げずに、最初の層の厚さを増加させることができます。

初期層が厚すぎると、最初の層がよりたわみやすくなり、象の足が発生します。[初期層の水平方向の拡大](../shell/xy_offset_layer_0.md) 設定は、小さな負の値を設定することで象の足を防ぐことができます。


layer_height_0.md

-------

Initial Layer Height
====
### **Description**
This setting defines the thickness of the first layer of your print. 

![The initial layer is thicker than the rest of the layers](../images/layer_height_0.png)

### **Influence**
Increasing the initial layer's thickness causes the nozzle to extrude more material over the same distance, which takes extra force, as the material spreads out to the sides to fill the full line width. This extra force causes the material to stick better to the build plate. Additionally, the thicker layer will tackle any irregularities in the flatness of the surface. If the build plate is slightly bent, the variability will be absorbed by the thickness of the first layer, otherwise the nozzle could scrape off the first layer when printing the second layer.

### **Usage**
The initial layer is normally printed thicker than the rest in order to create a stronger adhesion with the build plate. With this setting, the initial layer's thickness can be increased without reducing the resolution of the rest of the print.

Having too thick of an initial layer causes the first layer to sag more, which causes elephant's feet. The [Initial Layer Horizontal Expansion](../shell/xy_offset_layer_0.md) setting can prevent the elephant's feet by setting a small negative value.