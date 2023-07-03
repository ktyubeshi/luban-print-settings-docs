サポートを生成する
====
### **説明**
フューズド・フィラメント・ファブリケーションを用いた3Dプリンタは、溶けたプラスチックの糸を指定した場所に置くことで作動します。このプラスチックが支えられていないと、下に垂れ下がってしまいます。そのため、モデルの突き出た部分は通常、追加のサポート構造によって支えられる必要があり、印刷が終了した後に取り除かれ、廃棄されます。

この設定は、モデルが印刷される間にサポート構造を作成することを可能にします。

![サポートが必要なところをモデルに赤でマーキング](../images/support_enable_prepare_mode.png)
![印刷中にモデルを支えるためのサポート構造（シアン色）](../images/support_enable.png)

### **影響**
サポートの印刷は時間と材料を大量に消費します。また、印刷が完了した時には、サポートをモデルから割ったり切ったりする必要があります。これはモデルの表面に傷を残すことがあります。

しかし、サポートはいくつかの状況では依然として必要です。例えば、モデルにビルドプレートに向かって下を指すピースがある場合、このピースはサポートがなければ空中にぶら下がるだけになります。

サポートを防ぐための設計
----
サポートは時々必要なものの、可能ならばサポートの印刷は避けるべきです。サポートの印刷を避けるための技術は数多くあります。
* モデルをビルドプレートに置いて、空中に浮かばせるのではなく。
* モデルを配置する角度を調整して、空中に突き出た平面のないようにする。
* 可能な限りオーバーハングの設計を避ける。

---

Generate Support
====
### **Description**
3D printers with fused-filament fabrication work by placing a string of molten plastic in the specified locations. If this plastic is not supported, it will sag down. Therefore, the overhanging parts of a model usually need to be supported by an additional support structure, which will be removed and discarded after the printing is finished.

This setting enables creating support structures to support the model while it's being printed.

![Marking the model red where support is needed](../images/support_enable_prepare_mode.png)
![Support structure (in cyan) to support the model during printing](../images/support_enable.png)

### **Influence**
Printing support takes a significant amount of time and material. Besides, the support will need to be broken or cut off from the model when the print is completed. This tends to leave a scar on the model surface.

However, support is still necessary for some situations. For instance, if the model has a piece that points down towards the build plate, this piece would otherwise just hang in mid air without support.

Design for preventing support
----
Although support is sometimes necessary, printing support should be prevented if possible. There are numerous techniques to prevent having to print support. 
* Place your model down to the build plate instead of making it float in mid air.
* Orient your model such that there are no flat surfaces overhanging in mid air.
* Avoid designing overhangs as much as possible.