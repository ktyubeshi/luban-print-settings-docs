初期レイヤーサポートライン距離
====
### **説明**
サポートの最初のレイヤーの密度は、サポートの残りの部分の密度とは別に調整することができます。この設定は、サポートがビルドプレート上に置かれる二つの隣接するライン間の距離を設定します。

![最初のレイヤーのパターンは、サポートの残りの部分の2倍の密度です](../images/support_initial_layer_line_distance.png)

### **使用方法**
この設定は、サポートとビルドプレートとの間の付着を改善するのに役立ちます。最初のレイヤーでサポートパターンを密集させると、サポートとビルドプレートとの接触面積が増え、よりよく固定されます。

この設定は最初のレイヤーにのみ影響を与えるため、サポートの強度や時間と材料費には大きな影響を与えません。また、オーバーハングの品質にも影響を与えません。オーバーハング近くのサポートの密度を調整するには、[Support Roof Line Distance](../support_adv/support_roof_line_distance.md)設定を参照してください。

この設定は、サポートの本体のライン距離の倍数とするのが良いと思われます。このようにすると、サポートのラインが最初のレイヤーのラインと一致し、空中ではなく最初のレイヤー上に置くことができます。

---

Initial Layer Support Line Distance
====
### **Description**
The density of the support's first layer can be adjusted separately from the density of the rest of the support. This setting configures the distance between two adjacent lines where the support rests on the build plate.

![The pattern of the first layer is twice as dense as the rest of the support](../images/support_initial_layer_line_distance.png)

### **Usage**
This setting is useful to improve the adhesion between support and the build plate. Making the support pattern denser in the first layer will increase the contact area between the support and the build plate, making it stick better.

Since this setting only affects the first layer, so it doesn't significantly affect the strength of the support nor the time and material cost. It also doesn't affect the quality of overhangs. To adjust the density of support near the overhangs, look to the [Support Roof Line Distance](../support_adv/support_roof_line_distance.md) setting.

It is a good idea to make this setting a multiple of the line distance of the main body of support. This way, the lines of support will match up with the lines on the first layer, allowing them to rest on the first layer instead of floating in air.
