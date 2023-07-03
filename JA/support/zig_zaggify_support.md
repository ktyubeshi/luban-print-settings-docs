サポートラインを繋げる
====
### **説明**
[Support Pattern](support_pattern.md)でラインパターンが選択されている場合、この設定は、サポートラインの端点を接続させ、サポートを強化します。また、サポートの出力がより連続的な流れとなるようにします。トラベルムーブ（移動）が必要なタイミングを減らします。

![切断されたサポートライン](../images/zig_zaggify_support_disabled.png)
![接続されたサポートライン](../images/zig_zaggify_support_enabled.png)

### **影響**
サポートラインの接続にはいくつかの利点がありますが、一方でデメリットもあります：
* サポートはより安定し、印刷中に倒れる可能性が減少します。
* 流量はより一定に保たれ、フロープロブレムなしにサポートをより速く印刷できます。これは、適切に押し出すのが難しいサポート材料にとって特に重要です。
* サポートの途中でリトラクション（材料の引き戻し）が行われる場合、サポートの印刷中に必要となるリトラクションは大幅に減少します。これにより、材料の摩耗が防止されます。
* サポートを印刷するためにはより多くの材料が必要です。
* 通常、サポートの印刷にはより多くの時間が必要となります。これは、移動は通常、サポートラインの印刷よりも速いからです。

---

Connect Support Lines
====
### **Description**
If the lines pattern is chosen for the [Support Pattern](support_pattern.md), this setting makes the endpoints of the support lines to be connected together, making the support stronger. It also makes the support print with more continuous flow. Fewer travel moves will be necessary.

![Disconnected support lines](../images/zig_zaggify_support_disabled.png)
![Connected support lines](../images/zig_zaggify_support_enabled.png)

### **Influence**
Connecting the support lines has a couple of benefits, but also some downsides:
* The support will be more stable, less likely to topple over during printing.
* The flow rate will be held more constant, allowing you to print the support at greater speed without flow problems. This is especially important for support materials that are hard to extrude properly.
* If retractions are made during support, significantly fewer retractions will be necessary during the printing of support, which prevents the material from grinding.
* It takes more material to print the support.
* Usually it will take more time to print the support, since travel moves are normally faster than printing support lines.