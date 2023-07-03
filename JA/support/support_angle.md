サポート・オーバーハング角度
====
### **説明**
オーバーハング角度は、プリントを支えるためにどれだけの材料が使われるかを影響します。角度は、最小限にサポートされる角度を示します。この設定の値を下げると、サポートがより多く生成されます。

![低いオーバーハング角度はより多くのサポートを生成します](../images/support_angle_low.png)
![高いオーバーハング角度はより少ないサポートを生成します](../images/support_angle_high.png)
![サポートされるエリアは赤で示されます](../images/support_angle_prepare_mode.png)


### **影響**
この設定を下げると、印刷部品の大部分が支持されます。また、印刷中にあまりたわまない急峻な表面までもサポートします。必要以上のサポートが生成されると、印刷時間と材料の使用量が不必要に増え、サポートが印刷物に接触した箇所に傷が残る可能性があります。

しかし、サポート角度を下げることは、材料が過度に落ち込むのを防ぐために時々必要です。一般的に、これは最終部品の寸法精度を向上させ、オーバーハングをより良く見せる効果があります。

### **使用方法**
サポートを使用する際は、事前にサポートがどのように見えるかをプレビューステージで確認するのが良いでしょう。そこでは実際にどこにサポートが生成されるかを確認することができます。この設定を調整することで、不必要なサポートを取り除くことが可能です。

---

Support Overhang Angle
====
### **Description**
The overhang angle influences how much material is used to support the print. The angle indicates the minimum angle that gets supported. Reducing the value of this setting generates more support.

![A low overhang angle generates more support](../images/support_angle_low.png)
![A high overhang angle generates less support](../images/support_angle_high.png)
![The supported areas are indicated in red](../images/support_angle_prepare_mode.png)

### **Influence**
Reducing this setting makes more of the printed parts get supported, even surfaces that are steeper and won't sag much during printing. If unnecessary support is generated, it'll increase the printing time and material usage unnecessarily and also create scars where the support touched the print.

However reducing the support angle is sometimes necessary to prevent the material from sagging too much. It generally improves the dimensional accuracy of the final part and makes the overhangs look better.

### **Usage**
Whenever working with support, it's a good idea to preview what the support looks like in the Preview stage. There you can see where it will actually generate support. Adjusting this setting can filter out unnecessary support.