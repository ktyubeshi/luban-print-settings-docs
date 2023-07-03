サポートラインの距離
====
### **説明**
この設定は、サポートパターン内の2つの隣接するライン間の距離を定義します。この方法でサポートの密度を調整する方が、サポート密度を直接調整するより直感的かもしれません。なぜなら、直接にサポートラインが橋渡ししなければならない距離を調整するからです。

![大きなライン間距離](../images/support_infill_rate_low.png)
![小さなライン間距離](../images/support_infill_rate_high.png)

### **影響**
サポートライン間の距離を短くすることは、良い面と悪い面があります。以下は、考慮すべき効果の一部です：
* 上に接している表面は、2つのサポートライン間の距離が短いため、下がりにくくなります。
* サポートはより強くなり、印刷の信頼性が向上します。
* 接着面が増えたため、サポートを取り外すのが難しくなります。
* サポートを印刷するためにより多くの材料が必要になります。
* 印刷が完了するまでの時間が長くなります。

---

Support Line Distance
====
### **Description**
This setting defines the distance between two adjacent lines in the support pattern. This way of adjusting the density of support may be more intuitive than adjusting Support Density, since it directly adjusts the distance that the supported lines must bridge.

![Great line distance](../images/support_infill_rate_low.png)
![Small line distance](../images/support_infill_rate_high.png)

### **Influence**
Reducing the distance between support lines has some positive and negative effects. Here are some of the effects that need to be weighed off:
* The surface resting on top of this support will sag less, because it has to bridge a smaller distance between two lines of support.
* The support will be stronger, improving reliability of the print.
* It's harder to remove the support due to the increased adhesion surface.
* It will take more material to print the support.
* The print will take longer to complete.