トップサーフェススキンレイヤー
====
### **説明**
トップサーフェススキンとは、プリントのトップサーフェスで皮膚を構成する最上層を指します。トップサーフェススキンレイヤーは、トップサーフェススキンのために印刷されるレイヤーの数を設定します。

トップサーフェススキンレイヤーはトップレイヤーの一部です。しかし、トップサーフェススキンレイヤーは他のトップレイヤーとは異なる設定を構成できます。

![トップの最上層はスキンの残り部分（緑）よりも遅く印刷されます（青）](../images/roofing_layer_count.png)

### **使用方法**
すべてのトップレイヤーの設定を調整することで、トップサーフェスの品質を向上させることができますが、それは材料と時間のコストがかかります。ただし、設定を非常に上層または2層だけに調整し、残りの上層を高速で印刷すれば、材料と時間を節約しながら同等の効果を得ることができます。

トップサーフェススキンのために調整できる設定：
* [トップサーフェススキン押出機](roofing_extruder_nr.md)
* [トップサーフェススキンフロー](../material/roofing_material_flow.md)
* [トップサーフェススキン速度](../speed/speed_roofing.md)
* [トップサーフェススキン加速](../speed/acceleration_roofing.md)
* [トップサーフェススキンジャーク](../speed/jerk_roofing.md)
* [トップサーフェススキンライン幅](../experimental/roofing_line_width.md)
* [トップサーフェススキンパターン](../experimental/roofing_pattern.md)
* [トップサーフェススキンライン方向](../experimental/roofing_angles.md)

よりよいトップサーフェスを得るためには、速度を減らしジャークを増やすことを試してみてください。

[トップサーフェススキン押出機](roofing_extruder_nr.md)設定を使用して、異なる色でトップサーフェスを印刷する場合、通常、他の色で1層以上を印刷する必要があります。そうしなければ、元の色はまだ透けて見えます。

---

Top Surface Skin Layers
====
### **Description**
Top Surface Skin refers to the topmost layers that constitute the skin at the top surface of the print. Top Surface Skin Layers configures how many layers are printed for the top surface skin of the print.

The top surface skin layers are part of the top layers. However, you can configure different settings for the top surface skin layers from the rest of the top layers.

![The highest layer of the top is printed slower (blue) than the rest of the skin (green)](../images/roofing_layer_count.png)

### **Usage**
By adjusting settings for all the top layers, you can improve the the quality of the top surface, but that will also cost more material and time. However, if you adjust those settings only for the very top layer or two and print the rest of the top layers faster, you can achieve a similar effect with less material and time.

Settings that can be adjusted for the top surface skin:
* [Top Surface Skin Extruder](roofing_extruder_nr.md)
* [Top Surface Skin Flow](../material/roofing_material_flow.md)
* [Top Surface Skin Speed](../speed/speed_roofing.md)
* [Top Surface Skin Acceleration](../speed/acceleration_roofing.md)
* [Top Surface Skin Jerk](../speed/jerk_roofing.md)
* [Top Surface Skin Line Width](../experimental/roofing_line_width.md)
* [Top Surface Skin Pattern](../experimental/roofing_pattern.md)
* [Top Surface Skin Line Directions](../experimental/roofing_angles.md)

To achieve a nicer top surface, try reducing the speed and increasing the jerk.

When printing the top surface in a different colour (using the [Top Surface Skin Extruder](roofing_extruder_nr.md) setting), it is often necessary to print more than one layer in the other colour. Otherwise the original colour will still bleed through.