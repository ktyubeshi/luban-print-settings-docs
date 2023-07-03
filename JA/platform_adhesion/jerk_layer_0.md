初期レイヤーのジャーク
====
### **説明**
この設定は、初期レイヤーが印刷されている間、ノズルが角を通過する速度を決定します。他のすべてのレイヤーから別々に設定できます。

### **影響**
速い速度で鋭角を通過すると、ツールヘッドが水平方向に振動するだけでなく、ビルドプレートが垂直方向に振動することもあります。これはベッドの接着性に悪影響を及ぼします。初めての層で角をもう少し注意深く通過することで、ベッドの接着性が一貫していますが、印刷には時間がかかります。

さらに、ジャークを減らすと、通常はノズルが遅くなるので、資料の流れがいくつか遅延すると、プリンターは鋭角でより多くの材料を堆積します。この流れが減少する際の遅延です。これらの鋭角は、しばしばプリントが反りのためにビルドプレートから最初に離れてしまいます。そのため、これらの角に少し余分な材料を預けることは、角がよりよく固定されるため有利です。

### **使い方**
印刷の各構造はすべて異なるジャーク値を持つことがあります。インフィル、底面、外壁と内壁、サポート、プライムタワーのための別々の設定があります。この設定はそれらすべてを上書きします。[Skirt/Brim Jerk（スカート/ブリムのジャーク）](jerk_skirt_brim.md)設定だけがこのジャークを上書きします。これは、スカートとブリムは初期レイヤーでしか発生しないからです。

---

Initial Layer Jerk
====
### **Description**
This setting determines the speed at which the nozzle can go through corners while the initial layer is being printed. It can be configured separately from the rest of the layers.

### **Influence**
Going through sharp corners at great speeds not only causes the toolhead to vibrate horizontally. It can also cause the build plate to vibrate vertically. This affects bed adhesion negatively. Going through corners a bit more carefully during the first layer allows for more consistent bed adhesion, but will take longer to print.

Additionally, reducing the jerk will normally make the printer deposit more material in sharp corners because the nozzle slows down while the material flow has some delay in when the flow is reduced. These sharp corners are often where the print lets go of the build plate first due to warping. Depositing some extra material in those corners is advantageous then, since it'll make the corners stick better.

### **Usage**
The individual structures of the print could all have different jerk values. There are separate settings for the infill, bottom side, outer and inner walls, support and prime tower. This setting will override all of those. Only the [Skirt/Brim Jerk](jerk_skirt_brim.md) setting will override this jerk, since the skirt and brim can only occur in the first layer.

