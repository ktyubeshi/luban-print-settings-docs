フロー等化比率
====

この機能により、プリンタがライン幅を調整するために使用する方法を変更することができます：ノズルを通じての材料の流れの速度を変更する代わりに、プリンタはノズルが移動する速度を変更します。

FFFプリンタは、ノズルから材料が流れ出る速度を変更する点で非常に悪名高いです。プリンタが給材速度を変更すると、これがフロー率の変更に実際に変換されるまでに一瞬の時間がかかります。その時点で、印刷速度によっては、ノズルがフロー率を調整すべき点をすでに数ミリメートル超えている可能性があります。これは、プリンタがBowdenチューブを介してプリントヘッドからフィーダーを取り外している場合、さらに悪化します。

給材速度を変更する代わりに、プリンタは印刷ヘッドの移動速度も変更できます。プリントヘッドはもっと早く加速できるため、ラインの幅をより良く制御できます。プリントヘッドが速くなりながらフローレートが同じままの場合、同じ量の材料が大きな長さに伸ばされ、ラインの幅が縮小します。プリントヘッドが遅くなると、同じ量の素材が小さなスペースにまとまり、ラインの幅が広がります。

この設定は比率です。それはフローレート（0％）または印刷速度（100％）またはその二つの組み合わせを調整することができます。比率はさらに100％を超えることができ、これはフローレートが厚いラインを生成するために減少するが、スピードがさらに減少して補償することを意味します。

この比率を100％に向けて増やすと、ライン幅を変更するためにフローレートではなくスピードを使用することになるため、印刷に以下の影響を及ぼします：

* ライン幅がより正確になり、印刷の寸法精度が向上します。
* フローレートは均等に保たれ、特にエキゾチックな素材を使用したときに印刷がより信頼性のあるものになります。
* いくつかの場所では印刷ヘッドが速く移動し、リングが出来上がります。

この設定は、ラインを薄い部分と鋭い角の幅に収めることによるライン幅のバリエーションにのみ適用されます。インフィルと壁の為の異なるライン幅の設定によるフローレートの変更や、ブリッジングやアイロニングのような機能には補償されません。リニアアドバンスや類似の補償機能を実装するプリンタは、この設定が100％に設定されていても、それらの設定によってフローの変化がまだ発生する可能性があるので、それらを使用すべきです。

---

Flow Equalization Ratio
====

This feature allows you to change the way that your printer will use to adjust the line width: Instead of changing the flow rate of material through the nozzle, the printer will change the speed at which the nozzle moves.

FFF printers are notoriously bad at changing the rate at which material flows out of the nozzle. If the printer changes the speed of the feeder, it takes a fraction of a second before this actually translates into a change of flow rate. By that time, depending on the print speed, the nozzle may already be several millimetres beyond the point where the flow rate should've been adjusted. This is even worse if your printer has the feeder removed from the print head with a Bowden tube in between.

Instead of changing the feed rate, the printer can also change the movement speed of the print head. The print head can accelerate much faster and so could get better control over the width of the line. If the print head speeds up while the flow rate is kept the same, the same amount of material gets stretched over a greater length, which reduces the line width. If the print head slows down, the same amount of material is bunched up in a smaller space, increasing the line width.

This setting is a ratio. It could adjust the flow rate (0%) or the print speed (100%) or a combination of the two. The ratio can even exceed 100%, which means that the flow rate is reduced in order to produce thicker lines, but the speed is reduced even more to compensate.

Increasing this ratio towards 100% means that it uses the speed instead of the flow rate to change the line width, which has the following effects on the print:

* The line width is likely more accurate, improving the dimensional accuracy of the print.
* The flow rate will be kept equal, which makes the print more reliable, especially with exotic materials.
* In some places the print head moves faster, which results in ringing.

This setting only applies to the variations in line width caused by fitting the lines into the width of thin parts and sharp corners. Changes in flow rate due to settings such as different line widths for infill vs. wall will not be compensated for, nor features like bridging or ironing. Printers that implement Linear Advance or similar compensation features should still use those, even if this setting is set to 100%, because flow changes can still occur due to those settings.
