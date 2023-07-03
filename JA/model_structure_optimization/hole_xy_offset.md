# 穴の水平拡大
これは、穴が予定よりも小さく印刷される印刷効果の補償措置です。この設定を使用すると、プリントの穴のサイズを拡大できます。

![穴が大きくなりましたが、他の形状は変わりません](../images/hole_xy_offset.png)

材料の粘性のため、曲線を印刷すると、プラスチックはノズルに沿って曲線に引かれます。これにより、弦が内側の曲線に引き込まれるため、予定よりも少し小さくなります。通常、これは本当に目立つことはありませんが、非常に正確なアイテムを印刷したり、非常に小さな垂直穴を印刷したりする場合、これはあなたの印刷の精度を台無しにします。ネジが入らなくなり、部品がうまくスライドしなくなります。

この設定は、すべての穴を少し大きくすることでそれを補償します。[水平拡大](xy_offset.md)とは異なり、これは閉じた穴にのみ影響します。一方の端（水平方向、同じレイヤー上）に少しの開口がある場合、その部分は穴として考慮されず、この設定には影響しません。

正の値を設定すると、穴が大きくなります。負の値を設定すると、穴が小さくなります。水平拡大と組み合わせると、普通の水平拡大を適用する前に、穴が最初に拡大されます。これにより、普通の水平拡大で拡大される前に、薄い部品が完全に消えてしまう可能性があります。

hole_xy_offset.md

----

Hole Horizontal Expansion
====
This is a compensation measure for a printing effect where holes tend to end up being printed smaller than intended. With this setting you can expand the size of holes in your print.

![The holes have been made larger, but the rest of the shape hasn't changed](../images/hole_xy_offset.png)

Due to the viscosity of the material, when printing a curve, the plastic tends to get dragged by the nozzle along the curve. This makes the curve slightly smaller than intended as the string gets pulled into the inside of the curve. Normally this isn't really visible, but when printing items that need to be very precise or when printing items with very small vertical holes, this becomes ruinous to the accuracy of your print. Screws won't fit any more, pieces don't slide into each other neatly any more, and so on.

This setting compensates for that by making all holes slightly bigger. Unlike [Horizontal Expansion](xy_offset.md), this only affects closed holes. If there is even a tiny opening on one side (horizontally, on the same layer) then that part won't be considered a hole and won't be affected by this setting.

A positive value will make the holes bigger. A negative value will make the holes smaller. When combined with Horizontal Expansion, the holes are expanded first before applying the ordinary horizontal expansion. This could cause thin pieces to disappear entirely before they are expanded by the ordinary horizontal expansion.