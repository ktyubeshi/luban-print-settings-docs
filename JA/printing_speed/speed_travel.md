旅行速度
====
### **説明**
この設定は、材料を押出していないときにツールヘッドが移動する速度を設定します。

![Various structures printed at different speeds](../images/speed_difference.png)

### **影響**
旅行速度は一般的に他の速度設定よりもはるかに高いです。 旅行速度を上げるといくつかの効果があります：
* 高い旅行速度は、印刷時間をわずかに短縮できます。
* 旅行速度を上げると、フィラメントが材料から漏れ出す時間が短くなり、オージングによる小さなブロブでクリーナーなパーツ全体が作成されます。
* しかし、旅行速度を上げると、プリンタがより多くの振動を発生するため、リンギングが増加します。
* 旅行速度を上げると、[コンビング](../travel/retraction_combing.md)が無効になっている場合、特に印刷物が転倒する可能性が高くなります。
* 極端な速度になると、プリンタのモーターがいくつかのステップを失う可能性があり、レイヤーシフトが発生する可能性があります。

### **使用法**
**旅行速度は、ほとんどの人が想定しているよりも総印刷時間に影響を与えることが少ないです。 これは、旅行時間が通常、総印刷時間のわずかな割合であるため、そして加速度ではなく最大速度で制限されるため、高速になるまで長い時間がかかるためです。**

speed_travel.md

-----

Travel Speed
====
### **Description**
This setting configures the speed at which the toolhead moves when it's not extruding any material.

![Various structures printed at different speeds](../images/speed_difference.png)

### **Influence**
The Travel Speed is generally much higher than any other speed setting. Some effects of increasing the Travel Speed include:
* A higher Travel Speed can slightly reduce the printing time.
* Increasing the Travel Speed will reduce the time that the filament has to ooze out of the material, making a cleaner part overall with smaller blobs due to oozing.
* However, increasing the Travel Speed also tends to make the printer vibrate more, which increases ringing. 
* Increasing the Travel Speed increases the chance of your print being knocked over, especially if [combing](../travel/retraction_combing.md) is disabled.
* When taken to extreme speeds, the motors of the printer might also lose some steps, causing a layer shift.

### **Usage**
**The Travel Speed has less of an effect on the total printing time than most people assume. This is because the travel time is usually only a small fraction of the total printing time, and because it takes a long time for the high speeds are reached, being limited mostly by acceleration rather than maximum speed.**