# 内壁（複数可）の線幅

## **説明**
この設定は、個々の内壁の線幅を示します。内壁の線幅は外壁とは別に調整できます。

![内壁の線は他のものよりも広い](../images/wall_line_width_x.png)

## **影響**
内壁をノズルサイズよりも少し低くすると強度が向上します。ノズルはわずかに材料を押出しますが、その開口部が隣接する壁線と重なるため、材料が先に配置された壁によって適切な位置に押しやられます。しかし、それは隣接する壁にプラスチックをより良く接合させることも可能になり、壁同士がより良く接合して力を結合できるようになり、壁の強度が大幅に向上します。

内壁の線幅を増やすことで印刷時間を短縮できます。

線をフィットさせる
----
薄い部品を印刷する場合、壁線幅の設定を調整することは正確で強固な部品を得るための重要なツールです。Lubanは常に完全なコンターを描画しますので、コンターがギャップにフィットしない場合、それは壁に落ちてしまい、部品の強度と精度を大きく損ないます。

[壁間のギャップを埋める](../shell/fill_perimeter_gaps.md)が有効になっている場合、Lubanはこのようなギャップを埋めようとしますが、任意の形状に対しては不十分であり、しばしば多くの印刷時間を要します。2つの壁が重なる場合、[壁の重なりを補償](../shell/travel_compensate_overlapping_walls_enabled.md)機能は部品の正確性を確保するために壁線幅を縮小しますが、これは流れの変化を引き起こし、品質と強度を低下させます。

理想的なフィットを得るには、部品を壁線幅の正確な倍数に設定して、壁が部品内に正確にフィットするようにする必要があります。部品の幅を知っている場合、これは壁の幅を調整するだけで簡単に行うことができます。まず、線が十分な幅を持つように何個のコンターをフィットさせるかを見てください。次に、壁線幅を調整して、線が適切にフィットするようにするために必要な量を見てください。壁線幅を変更する効果を予測するために、各タイプの壁が何回描画されるかを注意深く数えてください。

壁の線をフィットさせることは、3Dプリントの専門家と他の人を区別する重要なスキルです。いくつかの練習が必要です。


wall_line_width_x.md

----


Inner Wall(s) Line Width
====
### **Description**
This setting indicates how wide the individual inner wall lines will be. The line width for the inner walls can be adjusted separately from the outer wall. 

![The lines for the inner walls are much wider than the rest](../images/wall_line_width_x.png)

### **Influence**
Reducing the inner walls to a line width slightly below the nozzle size is beneficial for the strength. The nozzle will extrude slightly less material but its opening will overlap with the adjacent wall lines, which causes the material to be pushed aside by the previously-placed wall into its proper location. But that will also cause the plastic to fuse better to the adjacent walls, which allows the walls to fuse better together so that they can combine their strength, greatly improving the strength of the walls.

Increasing the Inner Wall Line Width can reduce printing time.

Making lines fit
----
When printing thin parts, adjusting the wall line width settings is an important tool to get accurate and strong parts. Luban will only ever draw complete contours, so if a contour doesn't fit a gap, it will fall into the walls, which greatly compromises the strength and accuracy of the part.

Luban will attempt to fill such gaps between walls if [Fill Gaps Between Walls](../shell/fill_perimeter_gaps.md) is enabled, but that technique is less than ideal for arbitrary shapes and often takes a lot of printing time. When two walls overlap, the [Compensate Wall Overlaps](../shell/travel_compensate_overlapping_walls_enabled.md) feature will reduce the wall line width to make sure that the part is dimensionally accurate, but this incurs flow changes which reduce the quality and strength of the print as well.

For an ideal fit, you can set the part to be an exact multiple of the wall line width so that the walls fit precisely within the part. If you know how wide your part is, this can easily be done by adjusting the width of the walls. First you see how many contours you want to fit such that the lines still have a reasonable width. Then you can see how much you need to adjust the wall line width to make the lines fit properly. Keep in mind that you can adjust the [Outer Wall Line Width](wall_line_width_0.md) and [Inner Wall Line Width](wall_line_width_x.md) separately. Count carefully how many times each type of wall will be drawn to predict the effect of changing the wall line width.

Fitting wall lines is an important skill for 3D printing that distinguishes expert 3D printer operators from the rest. Some practice is required.