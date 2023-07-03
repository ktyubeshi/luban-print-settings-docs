インフィル密度
====
### **説明**
この設定は、印刷物の内部の密度を設定します。これは、最終印刷物の強度やトップ表面の品質に大きな要素となります。インフィル密度が高いほど、インフィル線は密に配置されます。100％を超える密度にすることも可能ですが、それは過剰押し出しを引き起こします。

![20% 密度](../images/infill_sparse_density_high.png)
![10% 密度](../images/infill_sparse_density_low.png)

### **使用方法**
異なるインフィルパターンには、異なる密度を設定する必要があるかもしれません。コーナーやクロッシングがたくさんあるインフィルパターンは、大きなインフィル密度ではうまく機能しません。コーナーは問題で、フィラメントがコーナーと一緒に引っ張られ、材料が堆積すべき場所のコーナーの外側に空気ポケットができます。クロッシングはさらに大きな問題で、一つのラインが別のラインを交差すると、ラインフローが中断され、交差した直後に欠陥が起こります。

インフィル密度を増やす（ライン距離を縮小する）と、印刷に大きな影響を与えます：
* 印刷物はより強固になります。
* 上面はよりサポートされ、滑らかで防水性が向上します。
* ピローイング効果が軽減され、熱のポケットが小さくなります。
* 印刷物にはより多くの材料が必要となり、結果として重くなります。
* 印刷にはより長い時間がかかります。

---

Infill Density
====
### **Description**
This setting configures the density of the volume inside the print, which is a major factor in the strength of the final print as well as the top surface quality. The greater the infill density, the closer the infill lines will be placed together. You can even go above 100% density, but that will result in overextrusion.

![20% density](../images/infill_sparse_density_high.png)
![10% density](../images/infill_sparse_density_low.png)

### **Usage**
For different infill patterns, you may need to set different densities. Infill patterns with lots of corners and crossings will not work well at great infill densities. Corners are a problem because the filament tends to drag along with the corner, creating air pockets in the outside of the corner where the material should've been deposited. Crossings are an even greater problem, because when one line crosses another, the line flow will get interrupted, causing underextrusion right after the crossing.

Increasing the infill density (by reducing the line distance) has a big effect on your print, namely:
* Your print will be stronger.
* The top surface will be supported better, becoming smoother and more watertight.
* The pillowing effect will be reduced because the pockets of heat will be smaller.
* Your print will require more material and as a result will be heavier.
* It takes longer time to print.