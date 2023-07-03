旅行時に印刷部品を避ける
====
### **説明**
この設定を有効にすると、ツールヘッドはビルドボリュームを移動する際に他のオブジェクトにぶつからないようにしようとします。小さな迂回ルートを取ることになります。他のオブジェクトにぶつからない迂回ルートが可能な場合は、パスの長さが[最大コーム距離（リトラクトなし）](retraction_combing_max_distance.md)設定を超えない限り、リトラクションは触発されません。

![無効化した場合、移動は他の部品を通過する可能性があります](../images/travel_avoid_other_parts_disabled.png)
![有効化した場合、移動は他の部品を避けます](../images/travel_avoid_other_parts_enabled.png)

他の部品を避けることに加えて、移動は可能な限り壁に近い位置を保つようにするでしょう。これは、部品を壁に入力する場合や出力する場合、壁に対して直角に出入りすることを意味します。

### **使用法**
この設定は、ノズルが壁を頻繁に通過しないため、印刷品質を向上させる傾向があります。壁を通過すると壁に傷跡が残るため、これを避けるべきです。

しかし、この設定はオージング（材料の漏出）を増加させます。なぜなら、リトラクト（材料の引き戻し）せずに移動する回数が増え、移動距離も長くなるからです。材料が非常に多く漏出する場合は、他の部品を避けることを無効にすることをお勧めするかもしれません。

プリント時間は移動距離が長くなるため微増する可能性がありますが、通常これはこの設定が引き起こすリトラクト回数の減少によって完全に相殺されます。

---

Avoid Printed Parts When Traveling
====
### **Description**
By enabling this setting, the toolhead will try to avoid hitting other objects when travelling around the build volume. It will take a small detour instead. If a detour is possible that doesn't hit any other objects, no retraction is triggered unless the length of the path exceeds the [Max Comb Distance With No Retract](retraction_combing_max_distance.md) setting.

![When disabled, travel moves can cross through other parts](../images/travel_avoid_other_parts_disabled.png)
![When enabled, travel moves will avoid other parts](../images/travel_avoid_other_parts_enabled.png)

Aside from avoiding other parts, the travel moves will also try to stay near the walls as shortly as possible. This means that when exiting or entering a part through a wall, it will exit or enter it perpendicular to the wall.

### **Usage**
This setting tends to improve the surface quality of the print, because the nozzle will not cross through the walls as often. Crossing through the walls leaves a scar in the wall, which should be avoided.

However, this setting does increase the amount of oozing, since more travel moves will be made without retracting and the travel moves will be longer. With materials that ooze a lot, it may be advisable to disable avoiding other parts.

Printing time could be slightly increased because the travel moves are longer, but usually this is completely offset by the reduction in the number of retractions that this causes.