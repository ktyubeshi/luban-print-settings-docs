フチがサポート部分を置き換えます
====
### **説明**
この設定を有効にすると、フチはサポートの周りを回る代わりに、サポートの下のモデルに沿って進みます。その結果、サポートはフチの上に印刷されます。サポートの周りにもフチが存在します。

![無効の場合、フチはサポートの周りを行きます](../images/brim_replaces_support_disabled.png)
![有効の場合、フチはサポートの下に行きます](../images/brim_replaces_support_enabled.png)

### **影響**
この設定を有効にすると、フチがモデルにより忠実に従います。その結果、モデルはビルドプレートにさらによく固定され、反りを防ぎます。

一部の場合では、この設定は一部のサポートのフチの合計幅を縮小します。しかし、それらの場合でも、サポートがモデルの十分近くに存在するため、サポートのフチがモデルのフチとマージしますので、そこでの接着に問題があるわけではほとんどありません。

---

Brim Replaces Support
====
### **Description**
If this setting is enabled, the brim will continue to follow the model underneath support, instead of going around the support. The support will then be printed on top of the brim. There will also still be a brim around the support.

![Disabled, the brim goes around the support](../images/brim_replaces_support_disabled.png)
![Enabled, the brim goes underneath the support](../images/brim_replaces_support_enabled.png)

### **Influence**
Enabling this setting will make the brim follow the model better. As a result, the model is kept down to the build plate better, which prevents warping.

In some cases, this will reduce the total width of the brim for some pieces of support. However, in those cases, the support will be close enough to the model that the support brim merges with the model brim, so it will hardly be a problem of adhesion there.