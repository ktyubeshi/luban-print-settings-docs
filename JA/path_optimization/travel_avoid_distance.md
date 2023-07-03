移動回避距離
==== 
### **説明** 
[他のオブジェクトとの衝突を避ける](travel_avoid_other_parts.md)場合、この設定はノズルが避ける必要のある他のオブジェクトからどれだけクリアランスを保つかを定義します。

この設定は、他のオブジェクトと移動の中央線との間の距離を定義することに留意してください。移動は厚みがありません。ノズルの先端が他の部品に当たらないように、この設定には少なくとも十分な値を与えることをお勧めします。

### **影響**
この設定値を増やすと、ノズルが他のオブジェクトを移動しながら打つ確率が減少します。

しかし、この設定値を増やすと、ノズルが大きな迂回路を取らなければならないため、移動の長さもわずかに増加します。これにより、印刷時間と滲みの量がわずかに増加します。また、これにより、以前に印刷した部分に近づき過ぎない有効な経路が見つかる可能性が減少します。有効な経路が見つからない場合、ノズルは（おそらく）リトラクトし、他のパーツが当たってしまうと諦めて直線で移動します。したがって、この設定を過度に増やすことは、表面品質にも悪影響を及ぼす可能性があります。

---

Travel Avoid Distance
====
### **Description**
When [avoiding collisions with other objects](travel_avoid_other_parts.md), this setting defines how much clearance the nozzle keeps to the other objects that it needs to avoid.

Keep in mind that this defines the distance between the other objects and the centreline of the travel move. The travel move has no thickness. It's advisable to give a value to this setting that is at least big enough so that the nozzle tip doesn't hit the other parts.

### **Influence**
Increasing the value of this setting reduces the chance that the nozzle hits previously printed objects when travelling around them. 

However, increasing the value of this setting will also slightly increase the length of travel moves, since the nozzle must take a greater detour. This increases printing time and the amount of oozing slightly. More pressing perhaps is that this reduces the chance of a valid path being found that doesn't come too close to any previously printed parts. If no valid path is found, the nozzle will (perhaps) retract and travel in a straight line instead, resigning that the other parts will be hit anyway. So increasing this setting too much can also be detrimental to the surface quality.