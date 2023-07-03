壁の順序設定
====
この設定は、最初に印刷する壁を決定します。外側から内側、または内側から外側へ印刷します。

![内壁が最初に印刷されます](../images/outer_inset_first_disabled.gif)
![外壁が最初に印刷されます](../images/outer_inset_first_enabled.gif)

この設定は、品質と寸法精度に少ない影響を与えます:
* 外側から内側への印刷は寸法精度を向上させます。隣接する壁は通常、互いに少し押し出され、特に壁の線幅がノズルサイズより小さい場合です。最初に印刷される壁は固化し、それほど押し出されません。したがって、外壁を最初に印刷すると、外壁がより正確な位置になります。
* 充填が壁の前に印刷される場合、外側から内側への印刷は表面上での充填の透け見えを減らします。それ以外の場合、充填が最初に印刷され、次に内壁が充填により外側に押し出され、次に内壁により外側に押し出される外壁が印刷されます。その結果、パターンが外側に見えるかもしれません。外壁が最初に印刷される場合、外壁は内壁が押す前に固化できます。
* 内側から外側への印刷は、オーバーハングの場合が良いです。外壁は前の層から内壁よりも離れています。外壁を最初に印刷する場合、外壁はまだ何も掴むものがありません。内壁を最初に印刷すると、外壁は外壁に横から接着できます。

壁の数が奇数の場合、中央の壁は常に最後に印刷されます。

---

Wall Ordering
====
This setting determines which walls are printed first, printing them from the outside in, or from the inside out.

![The inner wall is printed first](../images/outer_inset_first_disabled.gif)
![The outer wall is printed first](../images/outer_inset_first_enabled.gif)

This setting has a small effect on quality as well as dimensional accuracy:
* Printing from outside inwards will improve dimensional accuracy. Adjacent walls generally push each other a bit, especially if the wall line width is smaller than the nozzle size. The wall that gets printed first will have been solidified and then doesn't get pushed as much. Therefore printing the outer wall first will make your outer wall be in a more accurate location.
* If the infill is printed before the walls, printing from the outside in will reduce how much the infill shows through on the surface. Otherwise the infill is printed first, then the inner walls which get pushed outwards by the infill, and then the outer wall which gets pushed outwards by the inner walls. As a result, a pattern could be visible on the outside. If the outer wall is printed first, the outer wall can solidify before the inner wall is able to push on it.
* Printing from the inside out is better for overhang. The outer wall is further removed from the previous layer than the inner wall. When printing the outer wall first, the outer wall has nothing yet to grab on to. When the inner wall is printed first, the outer wall can attach sideways to the outer wall.

When there is an odd number of walls, the wall in the centre will always be printed last.