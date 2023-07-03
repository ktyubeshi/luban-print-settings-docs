押し出し冷却速度修正
====
ノズルチャンバー内で材料が加熱されると、それはノズルから熱を奪います。素材をより早く押し出すことは、ノズルからより多くの熱を奪う傾向があります。温度プローブがノズルの先端に正確にない場合、それは素材を押し出すときのノズルの温度がアイドル時よりもわずかに低くなる原因となります。この設定は、印刷中のノズルで熱がどれほど早く失われるかを説明しています。

[自動温度](../experimental/material_flow_dependent_temperature.md)が有効になっている場合、熱がどれほど早く失われるかによって印刷温度が調整されます。押し出しによって失われた余分な熱は、Gコードからの希望する印刷温度を上昇させることで補償されます。

設定の値は、ノズルの設計、印刷素材の熱容量、押し出し速度によって異なります。

---

Extrusion Cool Down Speed Modifier
====
When the material is heated up inside the nozzle chamber, it will take away heat from the nozzle. Extruding material faster tends to take away more heat from the nozzle. If the temperature probe is not exactly at the tip of the nozzle, that will cause the nozzle to have a slightly lower temperature while extruding material than when idle. This setting describes how soon the heat is lost in the nozzle while printing.

If [Auto Temperature](../experimental/material_flow_dependent_temperature.md) is enabled, the printing temperature will be adjusted depending on how soon the heat is lost. The extra heat lost by extruding will then be compensated for by increasing the desired printing temperature from the G-code.

The setting's value depends on the nozzle design, the heat capacity of the printed material and the extrusion rate.