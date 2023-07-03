レイヤーの高さ
====
### **説明**
3Dプリンタは、プラスチックを層状に塗布します。層の高さは、最終的な印刷物の視覚品質および印刷時間の両方において最も重要な要素です。

![0.1mm層の高さ](../images/layer_height_0.1.png)
![0.3mm層の高さ](../images/layer_height_0.3.png)

### **影響**
この設定を変更すると次の効果があります：
* より薄い層を持つと印刷の視覚品質が向上します。層が薄いため、層の境界付近での階段状の効果が減少します。また、層が密接しているため、層間の折れ線が小さくなり、全体的に滑らかな仕上がりになります。
* より薄い層を持つことで、プリンターが印刷物の上下の側面により詳細を生み出すことが可能になります。
* より厚い層を持つと、印刷物が強くなります。層間の境界が少なくなりますが、これは弱点となる傾向があります。より厚い層はそれほど剥がれません。
* より厚い層を持つと、印刷時間が短縮されます。なぜなら、ノズルが多くの水平移動をする必要がなくなるからです。

### **使用法**
----
多くの設定は層の高さに依存します。層の高さがノズルを通る材料の流量に大きな影響を与えるため、印刷プロセスの多くのパラメータが変更されます。たとえば、層の高さを増やすときは、熱の損失を補うために印刷温度をわずかに上げるべきです。温度が材料の流動性に影響を及ぼし、それが角の鋭さと必要な冷却などにどのように影響するかなどがあります。したがって、このような理由から、あなたが望む層の高さに近いプリンターで利用可能な予め作成された品質プロファイルから始めることが賢明です。

カスタムモードで目的の層の高さを選択できますが、予め作成されたプロファイルはさまざまな層の高さでも利用可能です。推奨モードではスライダー


layer_height.md


------------------------------------------------

Layer Height
============
### **Description**
The 3D printer puts down plastic in layers. The Layer Height is the most important factor in both the visual quality of your final print and the printing time.

![0.1mm layer height](../images/layer_height_0.1.png)
![0.3mm layer height](../images/layer_height_0.3.png)

### **Influence**
Changing this setting will have the following effects:
* Having thinner layers will increase the visual quality of the print. Since the layers are thinner, the stair stepping effect at the layer's borders will be reduced. Also, the layers will be closer together and so the creases in between the layers will be smaller, leading to an overall smoother finish.
* Having thinner layers allows the printer to produce more detail on the top and bottom sides of your print.
* Having thicker layers tends to make the print stronger. There will be fewer borders between the layers, which tend to be a weak point. The thicker layers will not shear as much.
* Having thicker layers will reduce printing time, because the nozzle will not have to make as many horizontal movements.

### **Usage**
----
Many settings depend on the Layer Height. Because Layer Height significantly affects the flow rate of material through the nozzle, many parameters of the printing process will change. For instance, when increasing the Layer Height, you should probably increase the printing temperature slightly to offset the extra rate of heat loss. The temperature then affects the liquidity of the material which will affect how sharp your corners will be and what cooling is needed, and so on. It is always wise to start from a pre-made quality profile available to your printer that has a Layer Height close to what you want.

You can choose a desired layer height in Custom Mode, but pre-made profiles are available with various layer heights as well. You can choose from profiles for various layer heights in the Recommended Mode using a slider or using the drop-down widget in Custom Mode. Since these profiles also change some parameters that depend on the Layer Height, you'll probably achieve a better quality that way.

Additional notes
----
At very low layer heights, you could run into the resolution limit of your Z axis. Look up the step size of your printer's Z axis and make sure that the layer height is a multiple of the step size. If the step size and layer height don't match up properly, some layers will be thicker than others which will result in banding.

**Note that the layer height setting is not applicable to the initial layer of the print or for the raft layers, which have their own settings to adjust the layer height separately. When using adaptive layers, this layer height setting will be used as a baseline but the actual layer height will have some variation.**