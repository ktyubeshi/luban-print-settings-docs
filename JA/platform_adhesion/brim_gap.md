ブリムの距離
====
### **説明**
この設定は、モデルとブリムとの間にギャップを作ります。ブリムのラインはモデルに隣接していない状態になります。

![The brim keeps a certain distance away from the model](../images/brim_gap.png)

このギャップの目的は、ブリムをモデルから容易に取り除くことができるようにするためです。

### **影響**
ブリムのラインを実際のモデルから少し離すこと（ラインの幅の半分の距離）により、ブリムとモデルとの連結が弱くなり、ブリムを手で破ることが容易になります。また、ブリムの除去後に残るスカーまたはエレファントフットを減らすこともできます。これは特に[初期レイヤーの高さ](../resolution/layer_height_0.md)が大きいときに効果的です。なぜなら、厚いブリムは取り除くのが難しくなる傾向があるからです。

一方で、これはモデルをビルドプレートに固定するブリムの効果を減少させます。より薄い接触領域を通じて、ブリムはモデルに対して大きな力を発揮してそれを下に保つことができなくなります。これは[warping](../troubleshooting/warping.md)の効果に対抗するためです。

---

Brim Distance
====
### **Description**
This setting causes a gap between the model and the brim. The brim lines are no longer securely adjacent to the model.

![The brim keeps a certain distance away from the model](../images/brim_gap.png)

The objective of this gap is to make it easier to remove the brim from the model. 

### **Influence**
By placing the brim lines slightly apart from the actual model (in the distance of half a line width), the connection between the brim and the model becomes weaker, which makes it easier to tear off the brim by hand. It will also reduce the scar or elephant's foot left by the brim after removal. This is especially effective at greater [initial layer height](../resolution/layer_height_0.md), since the thick brim tends to be harder to remove then.

On the flip side, this also reduces the effectiveness of the brim to keep the model stuck to the build plate. Through a thinner contact area, the brim will not be able to exert a lot of force on the model to keep it down against the effect of [warping](../troubleshooting/warping.md).

