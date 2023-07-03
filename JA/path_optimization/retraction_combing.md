コーミングモード
====
### **説明**
コーミングとは、一か所から別の場所へ移動する際に、プリントの壁を越えて移動することを避ける実践です。壁を越えて移動すると、ヘッドが熱を持ってプリントの容積を出入りするため、表面に傷を残す傾向があります。それは一般的に望ましくないためです。

コーミングだけでは、ノズルはメッシュの内部を移動する際に壁を避けます。同時に、[移動中に印刷部品を避ける](travel_avoid_other_parts.md) 機能をオンにすることで、ノズルがボリュームの外部でもオブジェクトを避けるようになります。

![ Combing disabled, the travel move crosses the walls of the print](../images/retraction_combing_off.png)
![ Combing enabled, a detour is made to avoid crossing the walls](../images/retraction_combing_on.png)

スタートからエンドまでの経路がオブジェクト内部で壁にぶつからずに通過できる場合、その経路が引き戻しを行わずに使用されます。 スタート地点とエンド地点が完全に別のパスにある場合、ノズルはまず2つの部分が最も近くにある位置に移動し、オプションで引き戻しを行い（[リトラクションが有効](retraction_enable.md)になっている場合）、目標のパスに移動し、オプションで引き戻しを戻し、その後、新しい部分を最終的な目的地への移動します。それぞれの部分では、内部を通過する際に壁にぶつかることを避けます。パートからパートへの移動時には、[移動中に印刷部品を避ける](travel_avoid_other_parts.md)設定が有効になっている場合にのみ、パートを避けます。

コーミングの目的は、オブジェクトの壁を通過することを避け、表面の傷を減らすことです。さらに見える部分の紐を減らします。なぜなら、移動操作が行われている間にもフィラメントが流れ出る場合があるからですが、このフィラメントはモデルの内部に配置されます。ただし、コーミングは移動の距離を増加させます。大回りする必要があることがあります。

この設定にはドロップダウンメニューで4つのオプションがあります：
* **オフ**：コーミングは無効です。旅行移動は常にその目標地点に直行します。これが壁に当たらない場合、引き戻しは行われません。
* **全て**：ノズルは上記のように、プリントの内部を移動する際に壁に当たりません。
* **スキンにない**：可能な限りノズルはスキンに当たらないようにします。これにより、ノズルが壁に沿って動くことで、スキンを通り抜けるのではなく、プリントの上面の傷を減らすことができます。しかし、一部のケースでは、ノズルが逃げ出すことができず、リトラクションを行わざるを得ない場合があります。通常であればスキンを通過していたでしょう。
* **インフィル内**：最も厳格なモードであり、インフィル内だけでコーミングを許可します。これにより、内壁と外壁の両方、およびスキンの打撃を避けることができます。 ノズルが内壁に当たると、ノズルの外側の半径が壁よりも広くなる場合があるため、外側にもまだ見えることがあります。 これはその効果を防ぎます。ただし、経路がしばしば利用できないため、さらに多くのリトラクションを行う必要があります。

---

Combing Mode
====
### **Description**
Combing is the practice of avoiding crossing the walls of the print when travelling from one place to another. Crossing the walls tends to leave a scar on the surface where a hot nozzle exited or entered the volume of the print, so that is generally undesirable.

Combing alone just causes the nozzle to avoid the walls when travelling through the inside of the mesh. You can also turn on the [Avoid Printed Parts While Traveling](travel_avoid_other_parts.md) feature, which makes the nozzle avoid objects while outside of the volume as well.

![Combing disabled, the travel move crosses the walls of the print](../images/retraction_combing_off.png)
![Combing enabled, a detour is made to avoid crossing the walls](../images/retraction_combing_on.png)

If there is a path through the object from the start to the end location without hitting any walls, this path will be taken without making a retraction. If the start and end location are in completely separate paths, the nozzle will first move to the position where the two parts are closest together, then optionally retract (if [retractions are enabled](retraction_enable.md)), travel to the target path, optionally unretract, and then move through the new part to its final destination. In both parts it will avoid hitting the walls while travelling through the inside. When travelling from part to part it will only avoid parts when the [Avoid Printed Parts While Traveling](travel_avoid_other_parts.md) setting is enabled.

The objective of combing is to avoid going through the walls of the object, reducing the amount of scars in the surface. It will also reduce the stringing that is visible on the outside, because while the travel move is made it will still ooze, but this ooze is placed on the inside of the model. However combing will also increase the length of the travel move. Sometimes it needs to make a big detour.

There are four options in the drop-down for this setting:
* **Off**: Combing is disabled. Travel moves will always go directly to their target location. If this happens to not hit any walls, it will not retract.
* **All**: The nozzle will not hit any walls while travelling through the inside of the print, as described above.
* **Not in Skin**: The nozzle will avoid hitting the skin as well, if possible. This can reduce the scarring on the top side of the print by making the nozzle go along the walls rather than cutting through the skin. However in some cases the nozzle will not be able to escape and has to make a retraction, where otherwise it would have cut through the skin.
* **Within Infill**: The strictest mode of them all, this only allows combing through the infill. This makes it avoid hitting the inner walls as well as the outer walls, and also avoids hitting the skin. If the nozzle hits the inner walls, it may sometimes still be visible on the outside because the outside radius of the nozzle may be wider than the walls. This prevents that effect. However, it will need to make even more retractions because a path will often not be available.