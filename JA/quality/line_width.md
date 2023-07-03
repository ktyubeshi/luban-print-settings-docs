線の幅
====
### **説明**
これはプリンターが配置する線の水平幅のことです。通常、ノズル開口部の直径が線の幅を決定しますが、材料を多く押し出したり、少なく押し出したりすることにより、線の幅は少し変化します。

![非常に細い線](../images/line_width_small.png)
![非常に広い線](../images/line_width_large.png)

### **影響**
線の幅を小さくすると、プリンターはより詳細な部分を印刷できます。特に、この設定ではプリンターが細い部分も印刷できます。線の幅はプリントの最も影響力のある設定の一つです。この設定を調整すると、次の効果が得られます：
* より細い線を印刷すると、最も細い部分にさえ線を配置できるため、より細い部分が印刷できます。
* プリントの厚さの偶数倍に線の幅を調整すると、オブジェクトがより固くなり、材料の流れが改善します。
* 比較的短い線幅は、上面をスムーズに見せる効果があります。
* ノズルサイズよりも若干小さい線を印刷すると、強度が向上します。ノズルが前回の線のすぐ上を通過するときに、隣接する線をいちどに融合させることができます。
* あり得ないほど広い線を印刷すると、過少押出しが発生します。プリンターは、線の幅を満たすためにより多くの材料を押出そうと試みます。その材料はできる方向に流れようとします。しかし、一定の圧力がかかると、物質は非常に広い線の側面まで流れなくなり、線と線の間に隙間が生じます。
* あまりにも小さな線を印刷すると、過少押出しになることもあります。材料がノズルから十分に速く流れない場合、材料の表面張力が小滴に凝固させ、押出しが均一でなく、滴と滴の間に隙間ができます。
* より細い線を印刷すると、印刷時間が大幅に増加します。

### **利用法**
*ノズルサイズの60％以下または150％以上にライン幅を減らすことは推奨されません。どちらも十分な材料を押し出すことができない可能性があります。*

ライン幅を調整して壁を十分に収める
----
薄いが強い必要がある機械的な物体を印刷する場合、ピースがライン幅のきれいな倍数でないという問題に常に直面します。もし倍数でなければ、Lubanは通常、[壁の重複を補償する](../shell/travel_compensate_overlapping_walls_enabled.md)設定のためにいくつかのラインの流れを減らします。これはノズルを通る流れ率を変更し、視覚品質を損ないます。もしライン幅のきれいな倍数であるけど偶数でなければ、壁の一つが0に減らされます。

きれいな輪郭と均一なラインを生成すると、印刷物は強くなり、見た目も良くなります。 

![デフォルトのライン幅、輪郭が合わず、一部のラインが他のラインより太い](../images/line_width_fit_bad.png)
![ライン幅を減らすと均一に収まります](../images/line_width_fit_good_small.png)
![ライン幅を増やしても機能します](../images/line_width_fit_good_large.png)

流れを一定に保つ
----
FDMプリンターでは、流れの大きな変動が時々問題になります。ノズルチャンバーは一部の材料を圧力下に保ち、これがノズルからの実際の流れ率を遅れさせます。流れ率が増減するまでには時間がかかります。フィラメントを供給するボーデンシステムを持つプリンターも、ボーデンチューブのバネ性がこの効果を著しく悪化させます。その結果、高い流れ率に切り替えるときに未押出が発生し、低い流れ率に切り替えると過押出が発生します。したがって、流れ率を可能な限り一定に保つことは良いアイデアです。

行の幅は流量に大きく影響します。行の幅をノズルのサイズに近づけ、密着させることをお勧めします。線幅を大幅に調整した場合は、印刷速度も調整して流量を一定に保つことを検討してください。そうすることで、印刷の寸法精度が向上します。


line_width.md

---------------

Line Width
====
### **Description**
This is the horizontal width of the lines that the printer will place down. Normally the diameter of the nozzle opening determines how wide your lines will be, but by extruding more or less material, the printer can vary a little bit in how wide the lines will become.

![Very thin lines](../images/line_width_small.png)
![Very wide lines](../images/line_width_large.png)

### **Influence**
Reducing the Line Width allows the printer to print more details. In particular, this setting also allows the printer to print thin parts. Line Width is one of the most influential settings in your print. Adjusting this setting will have the following effects:
* Printing thinner lines will allow thinner pieces to be printed, since it can even fit a line in the thinnest parts.
* Adjusting the Line Width to an even multiple of the thickness of your print can make the object stronger and make the material flow better.
* A smaller line width will make your top surface look smoother.
* Printing lines slightly smaller than your nozzle size tends to improve strength. It allows the nozzle to fuse adjacent lines together when it makes a second pass slightly over the previous line.
* Printing lines that are too wide will lead to underextrusion. The printer will attempt to extrude more material, enough to fill the desired width of the line. That material will attempt to flow in whichever direction it can. However at some point the back pressure will become too great such that the material will no longer flow all the way to the side of the very wide lines, leaving gaps between the lines.
* Printing lines that are too small will also lead to underextrusion. If the material doesn't flow fast enough through the nozzle, the surface tension of the material will cause it to coagulate into small droplets, making the extrusion uneven and leaving gaps in between the droplets.
* Printing thinner lines will considerably increase the printing time.

### **Usage**
*It's not advisable to reduce the line width below 60% of the nozzle size or above 150%. Both may fail to extrude enough material.*

Adjusting line widths to fit enough walls
----
When printing mechanical objects that need to be thin but strong, you'll regularly run into the problem that your piece does not have a clean even multiple of the line width. If it's not an even multiple, Luban will normally reduce the flow of some of the lines due to the [Compensate Wall Overlaps](../shell/travel_compensate_overlapping_walls_enabled.md) setting. This changes the flow rate through the nozzle which is detrimental to visual quality. If it is a clean multiple of the line width but not an even number, one of the walls will get reduced to 0.

Producing clean contours with even lines can make the print stronger and look better. 

![Default line width, where the contours don't fit and some lines are thicker than others](../images/line_width_fit_bad.png)
![Reducing the line width makes it fit evenly](../images/line_width_fit_good_small.png)
![Increasing the line width also works](../images/line_width_fit_good_large.png)

Keeping the flow constant
----
Great fluctuations in flow are sometimes problematic for FDM printers. The nozzle chamber keeps some material under pressure, which causes the actual flow rate out the nozzle to be delayed. It'll take a while for the flow rate to increase or decrease. Printers with a Bowden system to feed the filament also have springiness in the Bowden tube, which makes the effect much worse. As a result, you'll get underextrusion when switching to a higher flow rate and overextrusion when switching to a lower flow rate. Therefore it is a good idea to keep the flow rate as constant as possible.

Line Width influences the flow rate greatly. It is advisable to keep the widths of the lines close together and close to the size of the nozzle. If you have adjusted the Line Width significantly, you could consider adjusting the printing speed as well to keep the flow rate more constant. This will improve your print's dimensional accuracy.