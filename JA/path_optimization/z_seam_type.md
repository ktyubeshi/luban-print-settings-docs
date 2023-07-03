Zシームアライメント
====
この設定では、各輪郭のシームがどこに配置されるかを選択できます。シームの影響を最小限に抑えるか、または後処理でシームを簡単に取り除くことができるように、シームの配置を大いにコントロールできる複数のオプションが利用可能です。

シームとは、輪郭がレイヤー内で印刷を開始し終了する場所です。この設定を使用すると、シームをどこかに隠したり、周囲に広げたりすることで、見えにくくすることができます。

ユーザー指定
----
![User specified](../images/z_seam_type_user.png)

このオプションでは、位置を手動で選択することができます。シームは選択した位置に最も近い角に配置されます。これにより、シームが非常に近くに揃えられ、簡単にカットすることができます。また、シームがどこにあるべきかを細かく制御することも可能です。

デフォルトでは、プリンタの背面に位置が選択されます。

最短
----
![Shortest](../images/z_seam_type_shortest.png)

このオプションは、ノズルが前の層を終了する位置に最も近い位置に始点を配置することで、移動距離を最小限に抑えます。移動経路が短いため、移動時間を少し節約することができます。また、シームは若干小さくなります。なぜなら、ノズルが輪郭に着地する位置にオーズが少なく配置されるからです。

ノズルがいる場所に近い角を選択することで、希望の角の優先順位が維持されます。最も近い角が選ばれるわけではなく、重み付けされた優先順位が使われて、移動をある程度最小限に抑えつつ、適切な角を[シーム角の優先設定](z_seam_corner.md)に使用する。

ランダム
----
![Random](../images/z_seam_type_random.png)

シームの位置には、周囲のランダムな位置が選ばれます。このランダムな位置は、各レイヤーで変更されるため、シームはモデルの周囲にほぼ均等に広がります。異なるレイヤーのシームが揃わないため、シームはほとんど見えません。ただし、表面は全体的に若干乱雑に見えます。

最鋭角
----
![Sharpest corner](../images/z_seam_type_sharpest.png)

シームは、全体の輪郭の中で最も鋭い角に配置されます。これは[シーム角の優先設定](z_seam_corner.md)で選択した角の優先順位に従います。これにより、移動距離が長くなる可能性がありますが、角の優先設定に従って、シームを最大限に隠すか、露出させることが確実になります。

---

Z Seam Alignment
====
This setting allows you to choose where the seam of each contour is placed. Several options are available that give great control over where the seam gets placed to minimise its impact or to allow you to remove the seam more easily in post-processing.

The seam is where the contour starts and ends printing in a layer. With this setting the visibility of the seam can be minimised by hiding it somewhere or spreading it around.

User specified
----
![User specified](../images/z_seam_type_user.png)

This option allows you to choose a location manually. The seam will be placed in the corner that is closest to the chosen location. This will usually line up the seams very closely together, which allows you to cut them away easily. It also allows fine-grained control over where the seam should be.

By default, a location in the back of the printer is chosen.

Shortest
----
![Shortest](../images/z_seam_type_shortest.png)

This option minimizes the length of travel moves by placing the starting point closest to the position where the nozzle finishes the previous layer. Because the travel path is shorter, you'll save a small measure of time on travel moves. The seam will also be slightly smaller, because less ooze will be placed in the location where the nozzle lands on the contour.

The desired corner preference is still held by picking a corner close to where the nozzle is. Not the very closest corner is chosen, but a weighted preference is used to minimise travel moves somewhat but also use an appropriate corner for the [Seam Corner Preference](z_seam_corner.md) setting.

Random
----
![Random](../images/z_seam_type_random.png)

A random location around the perimeter is chosen for the seam. This random location is changed in every layer, so the seam will get spread out pretty much evenly around the model. Because the seams of different layers don't line up, the seam will hardly be visible. However, the surface will look altogether slightly messier.

Sharpest corner
----
![Sharpest corner](../images/z_seam_type_sharpest.png)

The seam will be placed in the very sharpest corner of the whole contour, according to the corner preference chosen in the [Seam Corner Preference](z_seam_corner.md) setting. This may incur longer travel moves, but ensures that the seam is hidden or exposed maximally according to the preference set for the corners.