サポートインターフェースの水平拡張
====
この設定により、サポートインターフェースが残りのサポート部分に対して全方向に拡大されます。

![サポートインターフェースはサポート内部に拡大されます](../images/support_interface_offset.png)

このメカニズムには2つの使用ケースがあります。
* サポートインターフェースが直接必要なオーバーハングの端に終わっている場合、建造材料が端部を越えて垂れ落ちる可能性があります。インターフェースを少し拡大することでこれを防げます。
* サポート印刷に使われるいくつかの素材は、低流量できちんと押し出せないか、適切に動作するまでに時間がかかります。サポートインターフェースの面積が小さいと、これらの素材と上手く合いません。この設定を使用すると、これらの素材を押し出すためのスペースが増えるように、面積を実際に大きくすることができます。

ただし、技術的な制限により、サポートインターフェースをサポート自体を超えて拡大することはできません。

---

Support Interface Horizontal Expansion
====
This setting causes the support interface to be expanded in all directions horizontally into the rest of the support.

![The support interface is expanded into the support](../images/support_interface_offset.png)

There are two use cases for this mechanism.
* If the support interface ends directly at the edge of the overhang that needs to be supported, the build material can sag over the edge. Making the interface expand a bit further will prevent this.
* Some materials typically used to print support with extrude badly at low flow rates or need some time to get going. Small areas of support interface don't jive well with those materials. This setting can literally make the areas larger so that there is more space to extrude these materials.

Due to technical limitations, the support interface cannot be expanded beyond the support itself.