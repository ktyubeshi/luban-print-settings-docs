Support Floor Speed
===
**概要**

この設定は、[サポートフロアが有効になっている](../support_adv/support_bottom_enable.md)場合、サポートの底面を印刷する速度を設定します。

![Various structures printed at different speeds](../images/speed_difference.png)

高いサポートフロアスピードは、一部の印刷時間を節約できます。

**使用法**

この設定の効果は大きく異なります。一部の材料、特に冷却が早く、[サポート底部距離](../support_adv/support_bottom_distance.md)が大きい材料では、より高いスピードでサポートとモデルとの接着性が高まります。この効果は橋渡しに似ています：より高いスピードでは、材料が慎重に懸濁されず、ツールヘッド上のファンによって冷却される時間がなくなります。これは通常あなたが望まないものです、なぜならサポートが表面に大きな印を残すからです。

他の材料では、より高いスピードで材料を置く力が減少し、流出する余地がなくなります。この効果はベッド接着に似ています。サポートフロアの開始と終了時に起こる流量の変化の限界に達するまで、より高いスピードは有利です。

サポートフロアがモデルに非常に近い場合（PVAなどの溶解性サポート材料の場合など）、サポートフロアスピードを上げると、ノズルがモデルに飛び込んで表面を微妙に傷つける可能性があります。

speed_support_bottom.md

-----

Support Floor Speed
====
### **Description**
This setting configures the speed at which the bottom side of the support is printed, if [Support Floor is enabled](../support_adv/support_bottom_enable.md).

![Various structures printed at different speeds](../images/speed_difference.png)

A higher Support Floor Speed can save some printing time.

### **Usage**
The effect of this setting greatly depends on circumstances. With some materials, especially materials that cool quickly and with a large [Support Bottom Distance](../support_adv/support_bottom_distance.md), greater speed will increase the adhesion between the support and the model. The effect is similar to bridging: At greater speeds, the material is less carefully suspended and doesn't get time to get cooled by the fans on the toolhead. This is something you don't normally want, because it will cause the support to leave a greater mark on your surface.

With other materials, greater speed reduces the force with which the material is put down and doesn't allow it to flow out much. This effect is similar to bed adhesion. The greater speed is then only advantageous until you start reaching the limits of the change in flow rate that occurs at the start and end of the support floors.

If the support floor is very close to the model, such as for PVA or other soluble support materials, increasing the support floor speed can also cause the nozzle to overshoot into the model, marring the surface slightly.
