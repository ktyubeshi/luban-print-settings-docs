サポート階段ステップ最大幅
====
### **説明**
[Support Placement](../support/support_type.md)が「Everywhere（どこでも）」に設定されている場合、サポートはモデルに接することができます。ただし、モデルの輪郭に完全に従うわけではありません。代わりに、サポートの底面には階段状のパターンが付与されます。これにより、サポートはモデルのいくつかの場所だけに接続されます。

この設定は、これらのステップの最大幅を決定します。ステップは通常、[Support Stair Step Height](support_bottom_stair_step_height.md)の指定された値でモデルの表面に従って幅を得ます。しかし、それが広すぎる場合、幅はサポート階段ステップ最大幅に制限されます。それから残りのステップでもモデルの表面に従います。

![階段ステップの幅が制限され、サポートがモデルに従う](../images/support_bottom_stair_step_width.png)

### **使用法**
一般的に、この設定は、サポートラインの上の安定性を損なうことなく素材が橋渡しできる最大距離に設定するべきです。設定を下げると、サポートがモデルにより頻繁に従うため、サポートがより安定します。設定を上げると、サポートはより頻繁にSupport Stair Step Heightの設定値に沿うことになり、サポートがモデルから取り外しやすくなります。

---

Support Stair Step Maximum Width
====
### **Description**
If [Support Placement](../support/support_type.md) is set to "Everywhere", the support is allowed to rest on the model. It won't follow the contours of the model exactly though. Instead, the bottom side of the support is given a stair stepping pattern. This way, the support only makes a connection to the model in a few locations.

This setting determines the maximum width of these steps. The step normally gets a width that follows the model's surface with a given value of [Support Stair Step Height](support_bottom_stair_step_height.md). However if that is too wide, the width gets limited to the Support Stair Step Maximum Width. It then follows the model's surface for the rest of the step.

![Stair steps limited in width, causing support to follow the model](../images/support_bottom_stair_step_width.png)

### **Usage**
This setting should normally be set to the maximum distance that can be bridged by the material without compromising the stability of the support lines above it. Lowering the setting causes the support to follow the model more often, making support more stable. Increasing the setting causes the support to adhere to the set value for Support Stair Step Height more often, making support easier to remove from the model.
