Z シームの相対位置
====
Z シームの配置がユーザー指定に設定されている場合、シームが配置されるべき座標を入力することができます。通常、これらの座標はビルドプレート上の Z シームの絶対位置を指定します。この設定が有効になっている場合、これらの座標はモデルの位置に対して相対的に取られます。

![無効: 座標はビルドプレートの中心にある絶対位置を指すため、すべての青い線が中央に向かっています](../images/z_seam_relative_disabled.png)
![有効: 座標はモデルに相対的であるため、すべてのモデルが同じ角に青い線を持つことになります](../images/z_seam_relative_enabled.png)

モデルがビルドプレート上で複製された場合、この設定は、Z シームが複製された各部品で完全に同じ位置に配置されるようになり、それらがビルドプレート上の同じ点を指すのではなくなります。これにより、ビルドプレート上での位置に関係なく、すべてのコピーを完全に同じ方法で印刷することができます。

---

Z Seam Relative
====
If Z Seam Alignment is set to User Specified, you can enter coordinates for where the seam must be located. Normally those coordinates specify the absolute position of Z seam on the build plate. If this setting is enabled, those coordinates will be taken relative to the position of the model.

![Disabled: The coordinates point to an absolute position in the centre of the build plate, so all the blue striped point towards the middle](../images/z_seam_relative_disabled.png)
![Enabled: The coordinates are relative to the model so every model will have the blue stripes in the same corner](../images/z_seam_relative_enabled.png)

When a model is duplicated on the build plate, this setting causes the Z seam to be positioned in exactly the same location for each of the duplicates, rather than having them point toward the same point on the build plate. This allows you to print every copy in exactly the same way regardless of their positions on the build plate.