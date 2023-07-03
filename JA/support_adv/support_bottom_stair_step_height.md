サポート階段ステップの高さ
====
### **説明**
[サポート配置](../support/support_type.md)が「すべての場所」に設定されている場合、サポートはモデル上に置くことができます。ただし、モデルの輪郭に完全に従うわけではありません。代わりに、サポートの底面は階段のステップパターンを持っています。これにより、サポートはモデルと数箇所でのみ接続します。

この設定は、これらのステップの高さを決定します。

![サポートの底部に形成される階段ステップ](../images/support_bottom_stair_step_height.png)

### **影響**
[サポート階段ステップ最大幅](support_bottom_stair_step_width.md)設定は、ステップの幅を制限します。もしモデルの表面が非常に浅く、小さなステップの高さが巨大なステップの幅を生じさせる場合、サポートはステップの高さの残りの部分についてモデルの表面に従います。

この設定を減らすと、サポートの底が滑らかになります。これはサポートとモデルとの間の密着性を高め、サポートをより安定させますが、サポートの除去を困難にします。

---

Support Stair Step Height
====
### **Description**
If [Support Placement](../support/support_type.md) is set to "Everywhere", the support is allowed to rest on the model. It won't follow the contours of the model exactly though. Instead, the bottom side of the support is given a stair stepping pattern. This way, the support only makes a connection to the model in a few locations.

This setting determines the height of these steps.

![Stair steps forming at the bottom of support](../images/support_bottom_stair_step_height.png)

### **Influence**
The [Support Stair Step Maximum Width](support_bottom_stair_step_width.md) setting limits the width of the steps. If the model's surface is so shallow that a small step height would incur a huge step width, the support will follow the surface of the model for the rest of the step's height.

Reducing this setting will cause the bottom of support to be smoother. This increases adhesion between the support and the model, making the support more stable but also making it harder to remove the support.
