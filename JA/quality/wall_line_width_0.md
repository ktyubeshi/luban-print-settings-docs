# 壁線の幅

### **説明**
この設定は、個々の壁線の幅を示します。壁の線幅は印刷物の残りから別々に調整できます。

![壁の線は他のものよりもはるかに広い](../images/wall_line_width.png)

### **影響**
ノズルサイズよりも少し下げた壁を縮小すると強度が向上します。ノズルはわずかに材料を押出しますが、その開口部が隣接する壁線と重なり、材料が先に配置された壁によって適切な位置に押しやられます。しかし、それは隣接する壁にプラスチックをより良く熔着させることも可能になり、壁同士がより良く熔着して強度を結合できるようになり、壁の強度が大幅に向上します。

Wall Line Widthを縮小することで、ノズルがより細かい細部を印刷できるようになります。特に[Outer Wall Line Width](wall_line_width_0.md)はこの機能に重要です。

Wall Line Widthを増加させることで、印刷時間を短縮できます。

壁をフィットさせる
----
薄い部品を印刷する場合、Wall Line Widthを調整することは正確で強固な部品を得るための重要なツールです。Lubanは常に完全なコンターを描画しますので、コンターがギャップにフィットしない場合、それは壁に落ちてしまい、部品の強度と正確性を大きく損ないます。

[Fill Gaps Between Walls](../shell/fill_perimeter_gaps.md)が有効になっている場合、Lubanはこのような壁間の隙間を埋めようとしますが、この技術は任意の形状に対しては不十分であり、しばしば多くの印刷時間を要します。2つの壁が重なっている場合、[Compensate Wall Overlaps](../shell/travel_compensate_overlapping_walls_enabled.md)機能は、部品が寸法的に正確であることを確認するためにWall Line Widthを縮小しますが、これは流量の変化を引き起こし、品質と強度を低下させます。

理想的なフィットを得るには、部品をWall Line Widthの正確な倍数に設定して、壁が部品内に正確にフィットするようにする必要があります。あなたが部品の幅を知っている場合、これは壁の幅を調整することで簡単に行うことができます。まず、線が適切な幅を持つように何個のコンターをフィットさせるかを見てください。次に、壁線を適切にフィットさせるためにWall Line Widthをどれだけ調整する必要があるかを見てください。壁ごとに異なる[Outer Wall Line Width](wall_line_width_0.md)と[Inner Wall Line Width](wall_line_width_x.md)を調整できることを忘れないでください。各タイプの壁が何回描画されるかを正確に数えて、Wall Line Widthを変更する効果を予測してください。

壁のフィットは、3Dプリントのための専門家3Dプリンタオペレーターを他の人と区別する重要なスキルです。いくつかの練習が必要です。


wall_line_width_0.md

---

Wall Line Width
====
### **Description**
This setting indicates how wide the individual wall lines will be. The line width for the walls can be adjusted separately from the rest of the print. 

![The lines for the walls are much wider than the rest](../images/wall_line_width.png)

### **Influence**
Reducing the walls to a line width slightly below the nozzle size is beneficial for the strength. The nozzle will extrude slightly less material but its opening will overlap with the adjacent wall lines, which causes the material to be pushed aside by the previously-placed wall into its proper location. But that will also cause the plastic to fuse better to the adjacent walls, which allows the walls to fuse better together so that they can combine their strength, greatly improving the strength of the walls.

Reducing the Wall Line Width also allows the nozzle to print finer details. Especially the [Outer Wall Line Width](wall_line_width_0.md) is important for this property.

Increasing the Wall Line Width can reduce printing time. 

Making lines fit
----
When printing thin parts, adjusting the Wall Line Width is an important tool to get accurate and strong parts. Luban will only ever draw complete contours, so if a contour doesn't fit a gap, it will fall into the walls, which greatly compromises the strength and accuracy of the part.

Luban will attempt to fill such gaps between walls if [Fill Gaps Between Walls](../shell/fill_perimeter_gaps.md) is enabled, but that technique is less than ideal for arbitrary shapes and often takes a lot of printing time. When two walls overlap, the [Compensate Wall Overlaps](../shell/travel_compensate_overlapping_walls_enabled.md) feature will reduce the Wall Line Width to make sure that the part is dimensionally accurate, but this incurs flow changes which reduce the quality and strength of the print as well.

For an ideal fit, you can set the part to be an exact multiple of the Wall Line Width so that the walls fit precisely within the part. If you know how wide your part is, this can easily be done by adjusting the width of the walls. First you see how many contours you want to fit such that the lines still have a reasonable width. Then you can see how much you need to adjust the wall line width to make the lines fit properly. Keep in mind that you can adjust the [Outer Wall Line Width](wall_line_width_0.md) and [Inner Wall Line Width](wall_line_width_x.md) separately. Count carefully how many times each type of wall will be drawn to predict the effect of changing the Wall Line Width.

Fitting wall lines is an important skill for 3D printing that distinguishes expert 3D printer operators from the rest. Some practice is required.