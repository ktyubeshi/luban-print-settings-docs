ZシームY
====
Z シームの位置合わせがユーザー指定に設定されている場合、シームは[Z シームX](z_seam_x.md)およびZシームYの設定によって指定された位置に近いところに配置されます。

![継ぎ目は前面に位置しています](../images/z_seam_y_front.png)
![継ぎ目は背面に位置しています](../images/z_seam_y_back.png)

この設定は、[Zシーム相対](z_seam_relative.md)が無効になっている場合はビルドプレート上の絶対位置を示し、Zシーム相対が有効になっている場合はモデルの中心からの相対位置を示します。

最終的なプリントでシームが見えにくい位置を選択するのが最善です。内側の角にある位置が良い選択になります。しかし、そのような角が利用できない場合は、ポストプロセスでシームを簡単に切り取ったり研磨したりできる位置を選択することもできます。

---

Z Seam Y
====
If Z Seam Alignment is set to User Specified, the seam will be placed close to the position specified by the [Z Seam X](z_seam_x.md) and Z Seam Y settings.

![The seam is located on the front side](../images/z_seam_y_front.png)
![The seam is located on the back side](../images/z_seam_y_back.png)

This setting indicates an absolute position on the build plate if [Z Seam Relative](z_seam_relative.md) is disabled, or a position relative to the centre of the model if Z Seam Relative is enabled.

It is best to choose a location where the seam will be hard to see in the final print. A location that is in an inside corner will be a good choice. But if such a corner is not available, you can also choose a position that allows the seam to be easily cut off or sanded down in post-processing.