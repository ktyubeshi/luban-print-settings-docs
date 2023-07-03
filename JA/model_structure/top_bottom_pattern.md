トップ/ボトムパターン
====
この設定では、トップとボトムのレイヤーがどのように素材で埋められるかを選択することができます。複数の異なる印刷パターンが利用可能ですが、ここでのパターンはインフィルのものよりも制限されています。固体のレイヤーを作成するパターンのみが利用可能です。

ラインズ
---
![Lines](../images/top_bottom_pattern_lines.png)

基本的なラインパターンは、表面上に直線を描きます。これらのラインはデフォルトでは、インフィルとサポートが十分に支えられるように向かって配置されています。ラインの方向はレイヤー間で交互に変わります。
* 良好な表面品質を提供します。
* 壁に強く付着し、比較的強度のある部品を作ることができます。

コンセントリック
----
![Concentric](../images/top_bottom_pattern_concentric.png)

コンセントリックパターンでは、壁からモデルの内部へ向かって輪郭を描きます。
* 全ての方向で同じ強度を持ちます。
* 空気のポケットや隙間の作成を防ぎます。このパターンを使用すると、防水オブジェクトを作りやすくなります。
* ラインが非常によくブリッジしているため、オーバーハングの品質が良いです。
* パートが円形の場合、輪郭が集まる中央で、いたずらにスポットを作ります。
* 表面品質は理想的ではありません。

ジグザグ
---
![Zigzag](../images/top_bottom_pattern_zigzag.png)

ジグザグパターンはラインパターンと非常に似ていますが、壁でラインを終わらせるのではなく、壁に接触すると向きを変えて次のラインに向かって押し出しを続けます。
* 素晴らしい表面品質を提供します。
* 押し出しレートをより一定に保つことで、表面の一貫性が向上します。
* ラインズパターンほど壁にしっかりと付かない。[Skin Overlap](skin_overlap.md)の効果が減少します。これにより部品は弱くなり、オーバーハングの品質も低下します。

---

Top/Bottom Pattern
====
This setting allows you to choose how the top and bottom layers get filled up with material. Several different printing patterns are available, but the patterns here are more limited than those for infill. Only patterns that create solid layers are available.

Lines
---
![Lines](../images/top_bottom_pattern_lines.png)

The basic lines pattern draws straight lines across the surface. These lines are oriented by default such that they are well supported by the infill and support. The direction of the lines alternates between layers.
* Provides a nice surface quality.
* Adheres strongly to the walls, creating relatively strong parts.

Concentric
----
![Concentric](../images/top_bottom_pattern_concentric.png)

The concentric pattern draws contours from the walls towards the inside of the model.
* Equally strong in all directions.
* Prevents creating air pockets and gaps. It's easier to create watertight objects with this pattern.
* Great overhang quality, because the lines tend to bridge very well.
* If the part is circular, this will create a nasty spot in the centre where the contours converge.
* Surface quality is less than ideal.

Zigzag
---
![Zigzag](../images/top_bottom_pattern_zigzag.png)

The zigzag pattern is very similar to the lines pattern, but instead of ending the lines in the walls, it will turn around when it touches the walls and continue extruding towards the next line.
* Provides a great surface quality.
* Keeps the extrusion rate more constant, which improves the consistency of the surface.
* Doesn't stick as well to the walls as the lines pattern. The effect of the [Skin Overlap](skin_overlap.md) is reduced. This makes the part weaker and reduces the quality of overhangs.