プライムタワーを有効にする
====
### **説明**
プライムタワー、または*ワイプタワー*とも呼ばれる、はビルドプレート上で別々に作られる追加の印刷で、非アクティブなエクストルーダーが適切に切り替えられるように支援します。

デュアルエクストルーダー印刷中、不活動のエクストルーダーはノズル温度がまだ高いときに素材を続けて滲み出す可能性があります。滲み出した素材はノズルの下にぶら下がり、ノズルチャンバーが空になることがあります。この場合、このエクストルーダーが再度印刷を開始するとき、蓄積された滲みが美観を損ね、空のチャンバーが冒頭で不適切な流れを引き起こします。これらはプライムタワーが防ぐことを意図している問題です。

![プライムタワーの見た目とその寸法](../images/prime_tower.svg)

### **使用方法**
プライムタワーを印刷することで、待機中のエクストルーダーはノズルから滲み出たものをすべて拭き取り、適切な素材の流れのためにそのチャンバーをプライムすることができます。

プライムタワーは、一方のエクストルーダーによって印刷された連続した外殻と、他方のエクストルーダーによって印刷された不連続な内壁からなる中空の円筒です。連続した外殻はタワーの安定性を維持するために必要ですが、一部の印刷では余分なエクストルーダーの切り替えを引き起こすことがあります。内壁はエクストルーダーの切り替えがないときには印刷されません。

プライムタワーの欠点は、印刷に余分な時間がかかり、ビルドプレート上のスペースを一部取り上げることです。

---

Enable Prime Tower
====
### **Description**
Prime tower, also called *wipe tower*, is an additional print that's created separately on the build plate to help the inactive extruder switch back properly.

During dual extruder printing, the extruder being inactive may continue to ooze out material when its nozzle temperature is still high. The oozed material may hang beneath the nozzle, while the nozzle chamber becomes void. In this case, when this extruder starts printing again, the accumulated ooze will cause unsightly appearance, and the empty chamber will cause improper flow at the beginning. Those are the problems that the prime tower is meant to prevent.

![How a prime tower looks, and the dimensions of it](../images/prime_tower.svg)

### **Usage**
By printing the prime tower, the stand-by extruder can wipe off any ooze from its nozzle and prime its chamber for proper mateiral flow.

The prime tower is a hollow cylinder consists of a continuous outer shell printed by one extruder and some discontinous inner walls printed by the other extruder. The continuous outer shell is necessary for maintaining the stability of the tower, although it may cause extra extruder switches for some prints. The inner walls are not printed when there is no extruder switch.

The disadvantages of the prime tower are that it takes some extra time to print and takes away some space on the build plate.