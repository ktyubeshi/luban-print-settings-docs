ツリーサポート衝突解決
====
### **説明**
ツリーサポートの主な欠点は、スライスに時間がかかることです。ツリーサポートに必要な計算のほとんどは、ツリーの枝がメッシュと衝突しないようにするためのものです。この設定は、これらの衝突防止計算の精度を決定します。この解像度を上げる（精度を下げる）と、計算時間が大幅に節約できますが、サポートがメッシュ近くにあるときにギザギザに見えるようにもなります。

![低解像度（0.2mm）では、枝がギザギザになる](../images/support_tree_collision_resolution_lo.png)
![高解像度（0.02mm）では、枝が滑らかになる](../images/support_tree_collision_resolution_hi.png)

### **影響**
この設定を上げると、スライス時間を大幅に節約できます。しかし、サポートがギザギザになり、それが強度を損ない、印刷中にサポートが折れて印刷が失敗する可能性が高くなります。

---

Tree Support Collision Resolution
====
### **Description**
A major disadvantage of tree support is that it takes a long time to slice. Most of the calculations necessary for tree support are for the branches of the tree to avoid colliding with the mesh. This setting determines the accuracy of these collision avoidance calculations. Increasing this resolution (lower accuracy) will save a lot of time calculating, but will also make the support appear jagged when it's near the mesh.

![A low resolution (0.2mm) causes the branches to become jagged](../images/support_tree_collision_resolution_lo.png)
![A high resolution (0.02mm) creates smooth branches](../images/support_tree_collision_resolution_hi.png)

### **Influence**
Increasing this setting will save a lot of slicing time. It will also make the support more jagged, which compromises its strength, increasing the chance that the support breaks off during printing and making the print to fail.