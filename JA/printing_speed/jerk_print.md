# Print Jerk
## 説明
Jerkは、ノズルがコーナーを通過する速度を決定します。

**3Dプリントのジャークと物理学のジャークは異なります。**用語「ジャーク」はMarlinによって導入されました。そこでは、パスを完璧に追従することに固有の問題を回避するためのワークアラウンドとして設計されました。ノズルはパスから外れることが許可されていない（理論的に）ため、ノズルはすべてのコーナーで0mm / sに減速する必要があります。これはあなたのプリントを破壊するため、0mm / sに減速するとブロブがすべてのコーナーに発生します。コーナーを省略するための曲線を作成することは許可されていませんし、オーバーシュートもできません。代わりに、Marlinはモーションのすべてのコーナーで速度ベクトルの瞬時の変化を許可します。この速度ベクトルの変化の量は「ジャーク」と呼ばれます。したがって、ジャークは速度の瞬時的な最大変化です。

## 影響

ジャーク値が高い場合、コーナーに近づくとノズルがより少なく減速し、より一定の速度で動きますが、より大きな振動も引き起こします。

ジャークを増加させると、プリントに2つのポジティブな効果があります。
* コーナーでノズルがより少なく減速するため、印刷時間が短縮されます。
* ノズルがゼロに減速しないため、コーナーでブロブが少なくなります。ノズルはより一定のペースで動き、コーナーに留まる間もなく開口部から材料が流れ出します。

ジャークを増加させると、2つのネガティブな効果もあります。
* 特定の加速度で方向を瞬時に変更するようにツールヘッドが指示されるため、プリンタは一般的にコーナーごとにより多くの振動を発生します。これらの振動は、リンギングを引き起こし、寸法精度が低下する原因となります。
* 極端な値では、コーナーでモーターがいくつかのステップを失う可能性があり、レイヤーシフトが発生する可能性があります。

jerk_print.md

-----

Print Jerk
====
### **Description**
Jerk determines the speed at which the nozzle can go through corners. 

**Jerk in 3D printing is not the same as jerk in physics.** The term "jerk" was introduced by Marlin. It was designed there as a workaround for the inherent problem in trying to perfectly follow a path. Since the nozzle is not allowed to deviate from the path (in theory), the nozzle would need to decelerate to 0mm/s in every corner. This would ruin your print, because decelerating to 0mm/s would cause a blob in every corner. It is not allowed to make curves to shortcut the corner, nor can it overshoot. Instead, Marlin allows for an instantaneous change in the velocity vector in every corner. The magnitude of this change in the velocity vector is coined "jerk". So jerk is the maximum instantaneous change in velocity, applied at every corner of the motion.

### **Influence**
With high jerk values, the nozzle won't slow down as much when approaching a corner, resulting in a more constant velocity but also in greater vibrations.

Increasing the jerk will have two positive effects on your print:
* The printing time will be shortened, because the nozzle slows down less in the corners.
* Because the nozzle doesn't slow down to a crawl, you'll get less of a blob in the corners. The nozzle moves at a more constant pace, so it doesn't linger in the corner while material keeps flowing out the opening.

Increasing the jerk also has two negative effects:
* The printer will generally vibrate more for every corner, because the toolhead is instructed to make instantaneous changes in directions at certain acceleration. Those vibrations tend to create ripples in your print, resulting in ringing and reduced dimensional accuracy.
* At extreme values, your motors are likely to lose some steps in the corners, which can cause a layer shift.