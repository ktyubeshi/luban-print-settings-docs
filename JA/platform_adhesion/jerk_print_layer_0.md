初期レイヤー印刷ジャーク
====
### **説明**
この設定は、初期レイヤーが押出される際にノズルがコーナーを通過する速度を決定します。初期レイヤー中の旅行移動とは別に設定することができます。

### **影響**
ジャークを減らすと、ノズルが遅くなると材料の流れが減少したときに遅延があるため、プリンターは鋭い角にさらに多くの材料を預けます。これらの鋭い角は、たわみによりビルドプレートを最初に放す場所でよくあります。そのため、そのような角にいくらかの追加の材料を預けることは有利となります。それは角がより良くスティックすることになります。

この効果は、初期レイヤーの移動中には存在しません。この理由から、最初のレイヤーの押出し中のジャークは通常、最初のレイヤーの移動移動中のジャークよりも少し低くなります。

### **使用法**
プリントの個々の構造はすべて異なるジャーク値を持つことができます。インフィル、底面、外壁及び内壁、サポート、プライムタワーのための別々の設定があります。この設定はそれらすべてを上書きします。[スカート/ブリムジャーク](jerk_skirt_brim.md)設定のみがこのジャークを上書きします、なぜならスカートおよびブリムは最初のレイヤーでのみ発生することができるからです。

---

Initial Layer Print Jerk
====
### **Description**
This setting determines the speed at which the nozzle can go through corners while the initial layer is being extruded. It can be configured separately from the travel moves during the initial layer.

### **Influence**
Reducing the jerk will make the printer deposit more material in sharp corners because the nozzle slows down while the material flow has some delay when the flow is reduced. These sharp corners are often where the print lets go of the build plate first due to warping. Depositing some extra material in those corners is advantageous then, since it'll make the corners stick better. 

This effect is not present during the travel moves of the initial layer. For this reason, the jerk during the extrusion of the first layer is normally a bit lower than the jerk during travel moves of the first layer.

### **Usage**
The individual structures of the print could all have different jerk values. There are separate settings for the infill, bottom side, outer and inner walls, support and prime tower. This setting will override all of those. Only the [Skirt/Brim Jerk](jerk_skirt_brim.md) setting will override this jerk, since the skirt and brim can only occur in the first layer.

