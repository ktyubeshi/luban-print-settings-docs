Z Seam X
====
Z Seam AlignmentがUser Specifiedに設定されている場合、シームはZ Seam Xと[Z Seam Y](z_seam_y.md)の設定により指定された位置に近く配置されます。

![シームは左側に位置しています](../images/z_seam_x_left.png)
![シームは右側に位置しています](../images/z_seam_x_right.png)

この設定は、[Z Seam Relative](z_seam_relative.md)が無効になっている場合はビルドプレート上の絶対位置を示し、またZ Seam Relativeが有効になっている場合はモデルの中心からの相対位置を示します。

シームが最終的な印刷で見えにくい場所を選ぶのが最良です。内側の角にある場所が良い選択となるでしょう。しかし、そのような角が利用できない場合でも、シームが後加工で容易に切り取ったり、サンドペーパーで削ったりできる位置を選ぶことも可能です。

---

Z Seam X
====
If Z Seam Alignment is set to User Specified, the seam will be placed close to the position specified by the Z Seam X and [Z Seam Y](z_seam_y.md) settings.

![The seam is located on the left side](../images/z_seam_x_left.png)
![The seam is located on the right side](../images/z_seam_x_right.png)

This setting indicates an absolute position on the build plate if [Z Seam Relative](z_seam_relative.md) is disabled, or a position relative to the centre of the model if Z Seam Relative is enabled.

It is best to choose a location where the seam will be hard to see in the final print. A location that is in an inside corner will be a good choice. But if such a corner is not available, you can also choose a position that allows the seam to be easily cut off or sanded down in post-processing.