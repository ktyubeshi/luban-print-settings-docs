初期レイヤーの底面パターン
====
この設定により、モデルの底側で、直接ビルドプレートまたはラフトに接触する部分のパターンを設定します。このレイヤーのパターンは、他の底レイヤーとは別に設定されます。

![初期レイヤーは同心円パターンで印刷されますが、残りは線のパターンです](../images/top_bottom_pattern_0.gif)

同心円パターンは、線が収縮するときのテンションがすべての方向に広がるため、他のパターンよりもビルドプレートによりしっかりと付着します。これにより、ワーピングを防ぎ、印刷の信頼性を向上させます。他のパターンは一方向に収縮します。

ラフトを使用して印刷するとき、線のパターンを使用すると部品が少し強くなる傾向があります。線は、ラフトの線間の隙間をうまく架けるように配置され、底面を滑らかにします。

---

Bottom Pattern Initial Layer
====
This setting configures which pattern will be used for the bottom side of the model where it rests directly on the build plate or the raft. The pattern for this layer is configured separately from the rest of the bottom layers.

![The initial layer is printed with a concentric pattern, but the rest is the lines pattern](../images/top_bottom_pattern_0.gif)

The concentric pattern tends to adhere much better to the build plate than other patterns, because the tension in the lines when they are shrinking is spread out in all directions. This prevents warping and improves the reliability of the print. Other patterns contract all in one direction.

When printing with a raft, using the lines pattern tends to give a slightly stronger part. The lines are then also oriented such that they bridge the gaps between the raft lines well, creating a smoother bottom side.