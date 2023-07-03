壁の遷移長さ
====
薄い部分では、すべての壁が形状の中に収まりません。もし部品があるところで他のところよりも薄い場合、Curaはあるところで異なる数の壁を使用する必要があります。この設定は、1つの壁を追加または削除する遷移領域の幅を制御します。

![A very short transition](../images/wall_transition_length_0_2.png)
![A longer transition](../images/wall_transition_length_1_5.png)

異なる数の壁間の遷移領域には常にいくつかの微妙な問題があります。これは、中央の線が終わって2つの周囲の壁がギャップを埋める必要があるときに最も目立ちます。彼らはすぐにスペースを埋めることはできず、ギャップが残されます。これは、印刷物の上部と下部に小さな穴を作成します。逆の効果が2つの壁が1つに結合するときに起こります。これは、一時的に重複してしまうまで、2つの壁が一緒になるまでオーバーエクストルージョンを引き起こします。これは、特に外壁でこれが起こる場合に特に寸法不正確さを引き起こします。これはすべて、可能な限り短い遷移を行うことで防ぐことができます。

しかし、短い遷移は、ギャップをすばやく埋めるためにノズルが非常に急なターンを取ることを意味します。これは、特に外壁の印刷のときにより多くのリングを引き起こします。遷移を長くすると、特に[ジャーク](../speed/jerk_print.md)制限を下回るように加速を減らすことができます。

この長さをライン幅の1または2倍に設定するのが理想的な場所です。フレームの弱いプリンタや重いプリントヘッドを持つプリンタは、それを増やす必要がある場合があります。リングなしで迅速に加速できるプリンタは、視覚的な品質を改善するために遷移を短くできます。

**この設定は通常の壁だけでなく、追加のスキン壁、サポート壁、インフィル壁、同心パターンにも適用されます。**

wall_transition_length.md

----

Wall Transition Length
====
In thin parts, not all of the walls fit inside of the shape. If the part is thinner in some places than in others, Cura needs to use different numbers of walls in some places. This setting controls how wide the transitional area will be where it adds or removes one of the walls.

![A very short transition](../images/wall_transition_length_0_2.png)
![A longer transition](../images/wall_transition_length_1_5.png)

The transition area between different numbers of walls always has some slight problems. This is most visible when a single line in the centre ends and the two surrounding walls need to fill the gap. They don't immediately fill the space, and a gap is left. This results in tiny holes on the top and bottom of the prints. The opposite happens when two walls combine into one, causing them to overlap for a moment until they have come together. The overextrusion can lead to dimensional inaccuracy, especially where this occurs in the outer wall. This can all be prevented by making the transition as short as possible.

However, a short transition also causes the nozzle to take some very sharp turns to quickly fill that gap. This results in more ringing, in particular if this occurs for the printing of the outer wall. Making the transition longer reduces accelerations in the nozzle, in particular if this reduces them below the [jerk](../speed/jerk_print.md) limit.

Setting this length to one or two times the line width is a reasonable place to start. Printers with weaker frames or heavier print heads may need to increase it, while printers that can accelerate quickly without ringing can affort to shorten the transition to improve visual quality.

**This setting doesn't just apply to normal walls, but also to extra skin walls, support walls, infill walls and concentric patterns.**