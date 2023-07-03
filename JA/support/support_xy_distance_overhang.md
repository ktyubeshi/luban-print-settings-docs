最小のサポートX/Y距離
====
### **説明**
Z距離のサポートをX/Y距離よりも優先する場合、モデルとサポートの間の水平距離は、必要な[Zサポート距離](support_z_distance.md)を満たすために、[サポートX/Y距離](support_xy_distance.md)の設定より短くなることが許されます。

この設定は、Z距離に関係なく保持する必要がある最小のX/Y距離を定義します。この最小X/Y距離は、再びZ距離を上書きします。

![Z距離がX/Y距離が非常に小さくなることを意味する場合、最小のX/Y距離が適用されます](../images/support_z_overrides_xy.svg)

### **影響**
この設定を増やすと、サポートがモデルの側面に当たって、不要な傷がつく可能性が減ります。また、サポートの取り外しも容易になります。ただし、この設定が実際に効果を発揮するのは、通常、サポートが必要な中程度から急なオーバーハングであることを覚えておいてください。この設定を増やすと、オーバーハングがさらに垂れ下がり、その表面品質が低下します。

---

Minimum Support X/Y Distance
====
### **Description**
If the Z distance of support is preferred over the X/Y distance, the horizontal distance between the support and the model is allowed to become smaller than the [Support X/Y Distance](support_xy_distance.md) setting to satisfy the required [Support Z Distance](support_z_distance.md).

This setting defines a minimum X/Y distance that must be held regardless of the Z distance. This minimum X/Y distance overrides the Z distance again.

![Minimum X/Y distance kicks in if the Z distance means that the X/Y distance would become very small](../images/support_z_overrides_xy.svg)

### **Influence**
Increasing this setting reduces the chance that the support hits the model on the side, leaving a scar where it's unnecessary. It also makes the support easier to remove. Keep in mind though that this only really kicks in at medium-steep overhangs where the overhang normally needs to be supported anyway. Increasing this setting also makes the overhang sag more, reducing its surface quality.