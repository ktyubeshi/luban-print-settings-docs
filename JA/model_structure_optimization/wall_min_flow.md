最小壁流量
====
### **説明**
壁の重複を補償すると、一部の壁ラインの流量が減少します。これは問題となることがあります。なぜなら、壁がほぼ完全に重なると流量が1%まで任意に低下するからです。極端に低い流量での印刷はうまくいきません。連続的に押し出すラインの代わりに滴状のパターンを形成する傾向があります。

この設定は、非常に低い流量のラインを移動ラインに変換し、効果的にその流量を0％にスナップします。通常の移動ラインと同様に、材料はまだ滲み出ますが、ビーズを形成することはありません。ノズルは正しい場所に滲み出すために壁のパスに沿って移動します。

![壁間の重複は通常通り補償されます](../images/wall_min_flow_0.png)
![50％未満の押し出しで壁が移動するように変わります](../images/wall_min_flow_50.png)

### **使用方法**
この設定を増やすと、壁が望むよりも薄くなります。プリンターは非常に細いラインを省略します。技術的にはこれは押し出し不足で、製品が望むよりも薄くなる原因です。壁全体にビーズやブリップの長い線を引く代わりに、何も印刷されません、壁は少し滑らかになります。

滲み出すことなくノズルが達成できる最小壁流量にこの設定を調整します。通常、これは約60％です。ライン幅が60％以下に減少すると、それらの滴が形成されます。より大きなレイヤー高さで印刷していたり、より厚い壁ラインを使用していたりする場合は、次元精度を高めるためにこの設定を少し下げることができるかもしれません。

---

Minimum Wall Flow
====
### **Description**
Compensating for wall overlaps will reduce the flow rate of some of the wall lines. This can be problematic, because it can reduce the flow rate arbitrarily low, down to 1% if the walls almost completely overlap. Printing at extremely low flow rates doesn't work well. It tends to form a droplet pattern instead of continuously extruding lines.

This setting will turn those lines with extremely low flow rate into travel moves, effectively snapping their flow rate to 0%. Material will still ooze out as with normal travel moves, but will not form beads. The nozzle will still follow the path of the wall in order to ooze in the correct location.

![Overlaps between walls are compensated normally](../images/wall_min_flow_0.png)
![Walls with less than 50% extrusion are turned into travel moves](../images/wall_min_flow_50.png)

### **Usage**
Increasing this setting will cause your walls to be thinner than desired. The printer will omit the very thin lines. Technically this is underextrusion, causing your part to be thinner than desired. Instead of drawing a long line of blips or beads across the wall, nothing will be printed, making the wall a bit smoother.

Adjust this setting to the minimum wall flow rate that your nozzle can achieve without forming droplets. Typically this is about 60%. If the line width is reduced below 60%, those droplets would form. If you are printing at greater layer heights or using thicker wall lines, you may be able to reduce this setting a bit to get greater dimensional accuracy.