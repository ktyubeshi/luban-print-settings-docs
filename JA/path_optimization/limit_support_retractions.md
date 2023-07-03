サポートの引き戻しを制限
====
### **説明**
サポートを印刷するために一箇所から別の箇所に移動する際に引き戻すのではなく、この設定はそれが直接移動するだけで引き戻さないようにします。

この機能が有効になっていると、素材は直線でサポートからサポートに移動する際には引き戻されなくなります。実際の印刷物に移動する際や実際の印刷物と衝突を避けるために迂回する際には、素材は引き続き引き戻されます。

### **使用法**
この設定による実際の効果：
* 特に引き戻しが困難なソフト素材を使用した場合、印刷時間がわずかに節約されます。
* ソフトな素材を印刷する際の摩耗を防ぎます。給給機は、同じフィラメントの片を多く引き戻すとフィラメントを摩耗させ、ついにはフィラメントが握れなくなり、ノズルが印刷の残りの部分で空気を出力するまでになることがあります。
* 引き戻しによって素材の流れが途絶えるのを防ぎます。一部の素材、例えばPVAは、流れを維持するのが困難なので、引き戻しはそれらの信頼性にマイナスです。ノズルが詰まる可能性があります。
* トラベル移動内部にもっと滴下するでしょう。これ自体はサポート上で醜く見えるだけで無害です。しかし、滴下するすべての素材は、その後印刷されるサポートの押し出し不足をもたらし、サポートの強度を損なう可能性があります。
* 滴下により、サポート上での塊の形成のチャンスが増えます。これらの塊を何度も当てると、サポートが倒れる可能性があります。

---

Limit Support Retractions
====
### **Description**
Instead of retracting when moving from one place to another to print support, this setting causes it to just travel directly without any retraction.

If enabled, the material will no longer be retracted when making a travel move from support to support in a straight line. When travelling to or from the actual print or when making a detour to avoid colliding with the actual print, the material will still be retracted.

### **Usage**
Some effects of this setting in practice:
* It saves slightly on printing time, especially with soft materials that are difficult to retract.
* It prevents wearing down the material as much when printing soft materials. The feeder tends to wear down the filament if retracting too much on the same strip of filament, up to the point where it loses grip on the filament and your nozzle will print air for the rest of the print.
* It prevent interrupting the material flow with the retraction. Some materials, such as PVA, have trouble keeping the flow going so retracting is detrimental to their reliability. The nozzle may get clogged.
* There will be more oozing inside travel moves. This by itself just looks ugly on support but is harmless. However, all of the material that's being oozed will also result in underextrusion of the support being printed afterwards, which compromises the strength of the support.
* Through oozing, it will increase the chance for the formation of blobs on support. When hitting these blobs repeatedly, the support has a chance of falling over.