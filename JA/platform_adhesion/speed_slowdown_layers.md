遅いレイヤーの数
====
### **説明**
初期レイヤーが遅く印刷されるのは、初期レイヤーだけではありません。この設定では、何層が遅く印刷されるかを設定します。これらの層を通じて、印刷速度は徐々に通常の印刷速度まで上がります。

![印刷速度は徐々に50mm/sに上がります](../images/speed_slowdown_layers.svg)

### **影響**
初期レイヤーから始めて、速度は直線的に増加（または減少）して通常の印刷速度になります。これは壁やスキン、インフィル（充填部分）など、異なる速度で印刷される場合にそれぞれで起こります。

### **使用法**
以下の2つの理由から、数層かけて通常の印刷速度に移行したいと思うかもしれません：
(1)	2層目と3層目はビルドプレートにかなり近く、それらを素早く動かすと印刷物が簡単に剥がれてしまうことがあります。
(2)	初期レイヤーの印刷速度と通常の印刷速度との間の流量の違いがあまりにも大きい場合、大きな流量変化が効果を及ぼすのに時間がかかるかもしれません。

速度変更時の未押出を防ぐためには、ゆっくりと移行することをお勧めします。
ただし、ゆっくり移行すると総印刷時間も長くなります。

---

Number of Slower Layers
====
### **Description**
The initial layer is not the only layer that gets printed slower. This setting configures how many layers get printed slower. Over the course of these layers, the printing speed will gradually increase to the normal printing speed.

![The printing speed gradually increases to 50mm/s](../images/speed_slowdown_layers.svg)

### **Influence**
Starting from the initial layer, the speed linearly increases (or decreases) to the ordinary printing speed. This happens separately for the walls, skin, infill and so on, if they are printed at different speeds.

### **Usage**
There are two reasons why you could want to transition to the normal printing speed over several layers: 
(1)	The second and third layers are still quite close to the build plate, and moving fast over them can rip the print loose pretty easily.
(2)	The difference in flow rate between the initial layer printing speed and the ordinary printing speed may be so great that the large flow rate change may take some time to come into effect. 

Transitioning slowly prevents underextruding at a great speed change.
However, transitioning slowly will also increase the total printing time.

