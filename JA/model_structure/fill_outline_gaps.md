壁を薄く印刷する
====
### **説明**
通常、Lubanは[外壁ライン幅](../resolution/wall_line_width_0.md)よりも薄い壁を省略し、印刷するには小さすぎると捨ててしまいます。

この設定が有効になっている場合、Lubanはこれらのピースを印刷しようと試みます。結果として得られる印刷物は不正確で乱雑ですが、ある程度信頼性のある形状を生み出すはずです。

![一部の部品は印刷するには薄すぎます](../images/fill_outline_gaps_disabled.png)
![この設定が有効になると、薄い部品でも印刷されます](../images/fill_outline_gaps_enabled.png)

### **影響**
極めて細いラインで小さなピースを埋めています。これらのラインは、短くて隣接している場合に結合されます。これは多くの場合に有効ですが、場合によっては非常に小さなジグザグを生じさせ、印刷時間を大幅に増加させます。

この設定に頼る前に、外壁ラインの幅を少しだけ調整してみることをお勧めします。部品がライン幅よりもわずかに薄い場合、全体の印刷の外壁ラインの幅を減らすことで、薄い部分が正常に印刷される場合があります。しかし、ライン幅をあまりにも小さくすると、材料の流れが不安定になり、過少押出しを引き起こします。

これは、水平面で薄い部品だけを印刷しようと試みます。Z方向で薄い部品の場合は、[スライシング許容値](../experimental/slicing_tolerance.md)の設定を参照するか、レイヤーの高さを高めてください。

---

Print Thin Walls
====
### **Description**
Normally, Luban will omit walls that are thinner than the [Outer Wall Line Width](../resolution/wall_line_width_0.md), discarding them as being too small to print.

If this setting is enabled, Luban will make an attempt at printing these pieces anyway. The resulting print will be inaccurate and messy, but it should produce the desired shape somewhat reliably.

![Some parts are too thin to print](../images/fill_outline_gaps_disabled.png)
![With this setting enabled, even thin parts will get printed](../images/fill_outline_gaps_enabled.png)

### **Influence**
The tiny pieces are filled with extremely thin lines. These lines are then combined if they are short and adjacent to one another. This works for many cases, but in some cases it produces a tiny zig zag, significantly increasing printing time.

It is advisable, before resorting to this setting, to try adjusting the outer wall line width slightly. If your part is slightly thinner than one line width, it might give a better result if you reduce the outer wall line width of your entire print such that the thin parts print normally. However reducing the line width too far will cause the material to flow unreliably, leading to underextrusion.

This will only attempt to print pieces that are thin in the horizontal plane. For thin pieces in the Z direction, see the [Slicing Tolerance](../experimental/slicing_tolerance.md) setting or increase the layer height.