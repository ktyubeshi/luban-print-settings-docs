リトラクション時のZ軸ホップ
====
### **説明**
リトラクションが行われるたびに、ノズルが上昇（またはビルドプレートが下降）して、ノズルとプリントの間にクリアランスが生まれます。ノズルが一か所から別の場所に移動する必要があるとき、ノズルはプリントの上に少し持ち上げられます。これにより、ノズルはプリントにぶつかるのではなく、プリントの上を通過します。

![Zホップが有効なときに上昇する](../images/retraction_hop_enabled.svg)

### **使用法**
* トラベル移動中にノズルがプリントに当たることを防ぎます。ノズルがプリントに当たると目に見える傷が残るため、プリントの壁の視覚的な品質を改善するはずです。
* マテリアルがトラベル移動中にノズルから滴下する場合、その滴下物はトラベル移動後にノズルが着地する場所に堆積します。これはよくインフィル（内部充填）で見えない部分であり、これにより表面上のブロブ（塊）が減少します。
* 表面上のブロブにはプリントを倒す可能性がありますので、この設定を有効にすると信頼性が向上します。

ただし、ノズルを常時上下させると時間が少しかかり、プリントの完成に時間がかかることになります。また、プリンターの設計によっては、Z軸が早く摩耗することもあります。

---

Z Hop When Retracted
====
### **Description**
Whenever a retraction is done, the nozzle is raised (or the build plate lowered) to create clearance between the nozzle and the print. When the nozzle needs to travel from one place to another, the nozzle will be lifted above the print slightly. This way, the nozzle goes over the print instead of hitting the previously printed parts. 

![Moving up when Z hops are enabled](../images/retraction_hop_enabled.svg)

### **Usage**
* It prevents the nozzle from hitting the print during travel moves. When the nozzle hits the print it leaves a visible scar, so it should improve the visual quality of the walls of the print.
* If the material oozes out of the nozzle during travel moves, the ooze gets deposited where the nozzle lands after the travel move, which is often in the infill where it's not visible. This reduces blobs on the surface.
* Blobs on the surface have a chance to knock over your print, so enabling this setting can improve reliability.

However, moving the nozzle up and down all the time takes a bit more time, so your print will take longer to complete. It can also wear down the Z axis of the printer faster, depending on the printer's design.