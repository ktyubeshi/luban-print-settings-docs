ジャーク制御を有効にする
====
ジャークは、ノズルがコーナーを抜ける速度を決定します。ジャーク制御が有効になっている場合、Lubanは印刷中のさまざまな部分で適用するジャークの量を制御します。無効になっている場合、プリンタファームウェアがジャーク値を選択します。

![速度、加速度、ジャークの関係](../images/velocity_acceleration_jerk.svg)

**3Dプリントのジャークと物理学のジャークは異なります。** 「ジャーク」という用語はMarlinによって導入されました。そこでは、パスを完璧に追従するという固有の問題を回避するためのワークアラウンドとして設計されました。ノズルはパスから外れることが許可されていない（理論上）ので、ノズルはすべてのコーナーで0mm / sに減速する必要があります。これはあなたの印刷を台無しにするだろう、なぜならコーナーごとに0mm / sに減速するとブロブが発生するからです。コーナーを省略するための曲線を作成することは許可されていませんし、オーバーシュートもできません。代わりに、Marlinはモーションのすべてのコーナーで速度ベクトルの瞬時の変化を許可します。この速度ベクトルの変化の量は「ジャーク」と呼ばれます。

したがって、ジャークはモーションのすべてのコーナーで適用される最大の瞬時変化の速度です。

jerk_enabled.md

-----

Enable Jerk Control
====
Jerk determines the speed at which the nozzle can go through corners. If jerk control is enabled, Luban will control how much jerk to apply during various parts of the print. If it's disabled, the printer firmware will choose a jerk value. 

![The relation between velocity, acceleration and jerk](../images/velocity_acceleration_jerk.svg)

**Jerk in 3D printing is not the same as jerk in physics.** The term "jerk" was introduced by Marlin. It was designed there as a workaround for the inherent problem in trying to perfectly follow a path. Since the nozzle is not allowed to deviate from the path (in theory), the nozzle would need to decelerate to 0mm/s in every corner. This would ruin your print, because decelerating to 0mm/s would cause a blob in every corner. It is not allowed to make curves to shortcut the corner, nor can it overshoot. Instead, Marlin allows for an instantaneous change in the velocity vector in every corner. The magnitude of this change in the velocity vector is coined "jerk".

So jerk is the maximum instantaneous change in velocity, applied at every corner of the motion.