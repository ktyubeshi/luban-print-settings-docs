サポートZ距離
====
### **説明**
この設定は、サポートとモデルの間の垂直方向のクリアランス、すなわちサポートの上部と下部の間隔を指示します。この設定は、サポートがモデルにどれだけよく接着するかを最も大きく影響します。

![Z距離はサポートの上部と下部の両方を決定します](../images/support_top_bottom_distance.svg)
![モデルとサポートの間の垂直距離（誇張表現）](../images/support_z_distance.png)

### **影響**
この設定を減らすと、サポートはモデルによりよく接着します。これにより、オーバーハングがあまり下がらないので、見栄えが良くなります。また、サポートはモデルの上部にしっかりと位置しているため、安定性も向上します。

この設定を増やすと、サポートの除去が容易になります。サポートがモデルを支えていた表面にあまり傷跡を残さなくなります。一方、モデルはそれほどよく支えられません。これにより、オーバーハングの表面品質が低下します。

### **使用法**
一般的なルールとしては、サポート材料がビルド材料によく接着するほど、この設定を大きくする必要があります。異なる材料を使用してサポートを印刷する場合、Z距離は大幅に短縮できます。なぜなら、異なる2つの材料は固体化した後により容易に分離する傾向があるからです。良好な層接合性の材料を使用している場合、設定を少し増やす必要があります。より高温で、またはより厚いラインで印刷すると、接合度が上がるため、この設定を増やす必要があります。

---

Support Z Distance
====
### **Description**
This setting indicates the vertical clearance that must be kept between the support and the model, both at the top of the support and the bottom. This setting is the most influential factor in how well the support adheres to the model.

![Z distance determines both the top and the bottom sides of support](../images/support_top_bottom_distance.svg)
![A vertical distance between model and support (exaggerated)](../images/support_z_distance.png)

### **Influence**
If this setting is reduced, the support will stick better to the model. This makes overhangs look better since they are not allowed to sag as much. It will also improve the stability of the support, because it is firmly positioned on top of the model at the bottom side of the support.

If this setting is increased, the support will be easier to remove. It won't leave as much of a scar on the surface where the support was supporting the model. On the other hand, the model won't be supported as well. This reduces the surface quality of the overhangs.

### **Usage**
As a general rule, the better the support material sticks to the build material, the greater this setting must be. If you're using a different material to print the support, the Z distance can be lowered considerably since two different materials tend to separate more easily after solidifying. If you're using a material with good layer bonding, the setting must be increased a bit. Printing hotter or with thicker lines also increases bonding, and thus also require increasing this setting.