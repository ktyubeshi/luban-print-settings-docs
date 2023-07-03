ノズルスイッチエクストラプライム量
====
### **説明**
この設定により、エクストルーダが切り替えられたときに少しの余分な材料を排出するようにプリンタを設定できます。他のエクストルーダが出力中またはエクストルーダの切り替え時にノズルが滲んだ後、ノズルの圧力を回復することを目的としています。

### **影響**
他のエクストルーダが出力中、このエクストルーダはスタンバイ状態で待機していたでしょう。この間にも、材料が滲み出ます。この材料の損失は、追加の材料を押し出すことで補えます。これによりノズル室内に圧力が戻ります。ただし、滲み出した材料はまだノズルの先端にぶら下がっているので、[プライムタワー](prime_tower_enable.md)または[滲みシールド](ooze_shield_enabled.md)を使用しない限り、印刷物の横に付着します。

### **使い方**
この設定はエクストルーダごとに設定可能です。設定した量の材料が、材料で印刷する前に排出されます。

---

Nozzle Switch Extra Prime Amount
====
### **Description**
This setting allows you to configure the printer to purge a bit of extra material every time when the extruder is switched back. It is intended to restore the pressure on the nozzle after it has been oozing while other extruders have been printing or during an extruder switch.

### **Influence**
While other extruders are printing, this extruder will have been waiting on stand-by. During this time though, it will ooze material. That loss of material can be compensated for by pushing through some extra material. This puts the pressure back in the nozzle chamber. The material that was oozed out will still be hanging under nozzle tip though, so unless a [prime tower](prime_tower_enable.md) or [ooze shield](ooze_shield_enabled.md) is used, it will end up on the side of your print. 

### **Usage**
This setting is configurable per extruder. The configured amount of material is purged before printing with the material.

