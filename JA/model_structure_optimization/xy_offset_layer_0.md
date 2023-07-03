初期レイヤーの水平拡張
### **説明**
この設定は、ビルドプレート（またはラフト）に接着している初期レイヤーだけを拡張します。[水平拡張](xy_offset.md)と同様に、正の値を設定すると初期レイヤーが広がり、負の値を設定すると初期レイヤーが狭くなります。

![元のモデル](../images/xy_offset_layer_0_original.png)
![初期レイヤーが縮小されたもの](../images/xy_offset_layer_0_enabled.png)

### **使用法**
初期レイヤーは通常、加熱されたビルドプレート上に印刷され、ビルドプレートに対する接着性を向上させるためにわずかに液体状態に保たれます。初期レイヤーは通常、他のレイヤーよりも厚くなっています。これにより、レイヤーが横に引き伸ばされるのに十分な時間と材料が与えられ、印刷物の下側にわずかに広いリップがある「象の足」と呼ばれる現象が生じます。この設定を使用すると、事前に初期レイヤーを細くすることで、象の足を補正できます。負の値を設定すると、初期レイヤーが小さくなります。

また、この設定に大きな正の値を設定すると、ラフトなどの他の接着技術と組み合わせて、印刷物の周囲に擬似ブリムを作成できます。

この設定をブリムと組み合わせると効果がないため、ブリムは初期レイヤーの周囲に大きな境界線を作成します。

xy_offset_layer_0.md

----

Initial Layer Horizontal Expansion
====
### **Description**
This setting expands only the initial layer that rests on the build plate (or on the raft). Similarly to [Horizontal Expansion](xy_offset.md), a positive value will make the initial layer wider while a negative value will shrink the initial layer.

![The original model](../images/xy_offset_layer_0_original.png)
![The intial layer is shrunk](../images/xy_offset_layer_0_enabled.png)

### **Usage**
The initial layer is often printed on a heated build plate, which keeps it in a slightly liquid state in order to improve adhesion to the build plate. The initial layer is normally also much thicker than the rest of the layers. This allows for ample time and material to let the layer sag sideways, creating a phenomenon called "elephant's foot" where the bottom side of the print has a slightly wider lip. This setting can compensate for the elephant's foot by making the initial layer slimmer in advance. You can set it to a negative value to get a smaller initial layer.

You can also give this setting a large positive value to create a pseudo-brim around your print that can be combined with other adhesion techniques such as the raft.

Combining this setting with a brim is ineffective, since the brim will produce a large border around the initial layer anyway.