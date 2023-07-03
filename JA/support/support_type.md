サポートの配置
====
### **説明**
この設定は、サポートをどこに置くことができるかを選択できます。

![サポートはすべての突出した面で生成されます](../images/support_type_everywhere.png)
![サポートは、ビルドプレートに置くことができる場所でのみ生成されます](../images/support_type_touching_buildplate.png)

### **影響**
サポートを随所に配置することは、サポートにとってより確実です。輪郭が垂れ下がるとサポートされて倒れることはありません。しかし、サポートはモデルの上にも置かれる可能性があり、それに接している箇所に傷跡を残します。これは、サポートを取り除いた後の視覚的な品質とモデルの表面の滑らかさを低下させます。

それに対して、ビルドプレート上にのみサポートを配置することで、モデル上にサポートが置かれるのを防ぎます。ただし、これによりモデルの一部にサポートがない状態になることもあります。

### **使用法**
ビルドプレート上にサポートを持つときのコツは、[円錐サポートを有効にする](../experimental/support_conical_enabled.md)ことと、[円錐サポート角度](../experimental/support_conical_angle.md)に負の値を与えることです。これにより、サポートがモデルの周りを成長し、モデルに接せずにメッシュの大部分を支えることができます。もしくは、ツリーサポートをお試しください。

---

Support Placement
====
### **Description**
This setting allows you to choose where support can be placed on top of.

![Support is generated for all overhanging surfaces](../images/support_type_everywhere.png)
![Support is only generated where it can rest on the build plate](../images/support_type_touching_buildplate.png)

### **Influence**
Placing support everywhere is more reliable for the support. All overhangs that would sag are supported properly. However, the support may rest on top of the model as well, leaving a scar where it touches. This reduces the visual quality and the smoothness of the model's surface after the support is removed.

Instead, placing support only on the build plate prevents support from resting on the model. This may leave some parts of your model unsupported, though.

### **Usage**
As a trick when using support on the build plate only, try [enabling conical support](../experimental/support_conical_enabled.md) and giving the [Conical Support Angle](../experimental/support_conical_angle.md) a negative value. This allows the support to grow around the model and still support most of the mesh without resting on the model. Alternatively, try tree support.