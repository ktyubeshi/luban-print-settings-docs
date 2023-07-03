デュアル押出しヘルパータイプ
======
デュアル押出しプリンティング中、非アクティブ状態の押出し機が、ノズルの温度がまだ高い時に材料を続けてにじみ出すことがあります。その後、この押し出し機が再びプリントを開始すると、ノズルの下に溜まったにじみ出した材料が対象物に付着してしまい、見た目が悪くなることがあります。そのため、デュアル押出しヘルパーが必要です。Lubanは2つのタイプのデュアル押出しヘルパーを提供しています。それぞれに独自の特徴があります。

プライムタワー
----

プライムタワー、別名 *ワイプタワー*、は非アクティブな押し出し機が正しく切り替えるのを助けるために、ビルドプレート上に別途作成される追加のプリントです。

実は、材料のにじみ出しは見た目が悪いだけでなく、空のチャンバーを作り出し、プリントの開始時に適切な流れを引き起こすこともあります。プライムタワーをプリントすることで、スタンバイしている押し出し機はノズルからのにじみ出しをワイプオフし、適切な材料の流れのためにチャンバーをプライムすることができます。

![プライムタワーの見た目、およびその寸法](../images/prime_tower.svg)

プライムタワーは、一方の押し出し機により印刷された連続した外殻と、他方の押し出し機により印刷された不連続な内壁からなる中空の円筒です。連続した外殻はタワーの安定性を維持するために必要ですが、一部のプリントでは押し出し機の切り替えを余分に引き起こす可能性があります。内壁は押し出し機の切り替えがない場合にはプリントされません。

プライムタワーの欠点は、少し余分な時間を要することと、ビルドプレート上の一部のスペースを占めることです。

ウーズシールド
----
ウーズシールドは、デュアル押出しプリンティング時ににじみ出した物をキャッチするための、オブジェクトの周囲にある一つのレイヤー幅の壁です。ウーズシールドは薄くて容易に壊れたり切れたりし、モデルから距離を保つため、表面に傷をつけることなく取り外すことができます。

ウーズシールドは、レイヤーで最初にスタートする抜き出し機で印刷されます。その後、抜き出し機が切り替えられると、切り替えられた押し出し機はノズルをウーズシールドにワイプします。このようにして、にじみ出した材料がモデルの表面に落ちることはありません。

![ウーズシールドがレイヤーの最初の抜き出し機で印刷され、二つの抜き出し機で印刷すると交互にパターンが出来る](../images/ooze_shield.png)
![ウーズシールドの一部のパラメータは調整可能です](../images/ooze_shield.svg)

ウーズシールドは、最も高い抜き出し機の切り替え箇所まで印刷されます。その高さ以上では、ノズルはスタンバイモード後にプリントに移動されませんので、ウーズシールドをプリントする必要はありません。

---

Dual Extrusion Helper Types
====
During dual extruder printing, the extruder being inactive may continue to ooze out material when its nozzle temperature is still high. Then, when this extruder starts printing again, the accumulated ooze beneath the nozzle may stick to the object, leading to an unsightly print. That's why we need to use dual extrusion helpers. Luban provides you with two types of dual extrusion helpers, each with its own feature. 

Prime Tower
----

Prime tower, also called *wipe tower*, is an additional print that's created separately on the build plate to help the inactive extruder switch back properly.

Actually, material oozing will not only cause unsightly appearance, but also result in an empty chamber, followed by improper flow at the beginning of the print. By printing the prime tower, the stand-by extruder can wipe off any ooze from its nozzle and prime its chamber for proper mateiral flow.

![How a prime tower looks, and the dimensions of it](../images/prime_tower.svg)

The prime tower is a hollow cylinder consists of a continuous outer shell printed by one extruder and some discontinous inner walls printed by the other extruder. The continuous outer shell is necessary for maintaining the stability of the tower, although it may cause extra extruder switches for some prints. The inner walls are not printed when there is no extruder switch.

The disadvantages of the prime tower are that it takes some extra time to print and occupies some space on the build plate.

Ooze Shield
----
Ooze shield is a one-layer wide wall around the object that catches ooze during dual extruder printing. The ooze shield is thin enough to break or cut easily, and keeps its distance from your model so that it can be removed without scarring the surface.

The ooze shield will get printed with the extruder that starts on a layer. Then, when extruder switch happens, the switched back extruder will wipe its nozzle on the ooze shield. This way, the oozed material won't fall on the model surface.

![The ooze shield gets printed with the first extruder of a layer, causing an alternating pattern if printing with two extruders](../images/ooze_shield.png)
![Some parameters can be adjusted for the ooze shield](../images/ooze_shield.svg)

The ooze shield will print up to the height of the highest extruder switch. Above that height, no nozzle will be moved into the print after being on stand-by mode, so printing an ooze shield is unnecessary. 
