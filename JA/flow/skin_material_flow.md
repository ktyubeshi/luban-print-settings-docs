上/下流れ
====
### **説明**
この設定は、上部と下部の流れの速度を調整します。

### **使用法**
上部および下部の流れの速度は、プリントの残りの部分の流れの速度とは別に調整することができます。

上部および下部での流れの速度を調整することは、押し出し速度の問題を解決するための一時的な方法であり、また密閉性がない問題を解決するための方法です。

上部印刷中に押し出し速度の問題がある場合は、上部側がブリッジする必要がある距離を減らすために、[infill density](../infill/infill_sparse_density.md) および [pattern](../infill/infill_pattern.md)、あるいは[v段階的な充填](../infill/gradual_infill_steps.md)を見る方が良いでしょう。

下部印刷中に押し出し速度の問題がある場合は、支持用の [density](../support/support_infill_rate.md)、[pattern](../support/support_pattern.md) および[v段階的な充填](../support_adv/gradual_support_infill_steps.md)を確認してください。温度と印刷速度も良好で一貫した押し出しを達成するための重要な要素です。

---

Top/Bottom Flow
====
### **Description**
This setting adjusts the flow rate for the top and bottom. 

### **Usage**
The flow rate for the top and bottom can be adjusted separately from the flow rate of the rest of the print.

Adjusting the flow rate during the top and bottom is a stop gap method to fix problems with extrusion rate or not being water tight.

If there is a problem with extrusion rate during the printing of the top side, it is better to look at the [infill density](../infill/infill_sparse_density.md) and [pattern](../infill/infill_pattern.md) or perhaps [gradual infill](../infill/gradual_infill_steps.md), in order to reduce the distance the top side needs to bridge. 

If there is a problem with extrusion rate during the printing of the bottom side, take a look at the [density](../support/support_infill_rate.md), [pattern](../support/support_pattern.md) and [gradual infill](../support_adv/gradual_support_infill_steps.md) for support. The temperature and printing speed are also important factors for achieving good, consistent extrusion.

