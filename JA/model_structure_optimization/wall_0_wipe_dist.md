アウターウォール移動距離(Outer Wall Wipe Distance)
====
この設定では、外壁が終わるたびに、ノズルは押し出されることなくわずかに移動し、輪郭を拭き取るように閉じます。

With this setting, at the end of every outer wall, the nozzle will travel slightly further without extrusion, wiping the contour closed.

![A small travel move after completing the outer wall](../images/wall_0_wipe_dist.png)

この機能の目的は、継ぎ目を目立たなくすることです。壁が完成したとき、通常ビードはまだノズルの少し後ろにある。このわずかな移動で、ビードと輪郭の始点がつながり、継ぎ目が閉じます。

The goal of this feature is to reduce the visibility of the seam. When the wall is completed, normally the bead is still slightly behind the nozzle. This little travel move connects the bead with the start of the contour, so that the seam is closed.

継ぎ目はまだ目立ちますが、拭き取り距離を小さくすることで、仕上がりは少し良くなるはずです。この設定を大きくしすぎると、ノズルが継ぎ目を越えて移動するため、それ以上の効果はありません。また、ノズルの拭き取り中にノズルチャンバーが空になるため、後でアンダー押し出しが発生する可能性があります。

The seam will still be visible, but the result should be slightly better with a small wipe distance. Increasing this setting too much has no more effect since the nozzle travels beyond the seam, and may cause some underextrusion later as the nozzle chamber empties during nozzle wipe.


この効果は基本的に[Coasting](../experimental/coasting_enable.md)の逆で、輪郭が仕上がる前に押出しがわずかに止まります。

This effect is basically the opposite of [coasting](../experimental/coasting_enable.md), which will stop extruding slightly before the contour is finished.