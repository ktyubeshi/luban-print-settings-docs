オーズシールドを有効にする
====
オーズシールドは、デュアルエクストルーダ印刷中にオーズをキャッチするためのオブジェクト周りの１層幅の壁です。

デュアルエクストルーダ印刷中、アイドル状態のエクストルーダは、ノズルの温度がまだ高い場合に材料を続けて吹き出す可能性があります。次に、このエクストルーダが再び印刷を開始すると、ノズル下の蓄積したオーズがオブジェクトに付着し、視覚的に不快な印刷物となる可能性があります。これがオーズシールドが防ごうとする問題です。

オーズシールドは、レイヤーを開始するエクストルーダで印刷されます。そして、エクストルーダが切り替えられると、切り替えられたエクストルーダはノズルをオーズシールドに拭きつけます。これにより、吹き出した材料がモデルの表面に落ちることはありません。

![レイヤーの最初のエクストルーダでオーズシールドが印刷され、2つのエクストルーダで印刷している場合には交互のパターンが生じます](../images/ooze_shield.png)
![オーズシールドの一部のパラメータは調整可能です](../images/ooze_shield.svg)

オーズシールドは最高エクストルーダ切替高さまで印刷します。その高さ以上では、スタンバイモードにあった後にプリントインされるノズルはなく、オーズシールドの印刷は不要です。

オーズシールドは十分に薄くて簡単に折ったり切ったりでき、モデルから適度な距離を保つことで、表面に傷をつけずに取り外すことができます。

---

Enable Ooze Shield
====
Ooze shield is a one-layer wide wall around the object that catches ooze during dual extruder printing.

During dual extruder printing, the extruder being inactive may continue to ooze out material when its nozzle temperature is still high. Then, when this extruder starts printing again, the accumulated ooze beneath the nozzle may stick to the object, leading to an unsightly print. That's the problem that the ooze shield is meant to prevent. 

The ooze shield will get printed with the extruder that starts on a layer. Then, when extruder switch happens, the switched back extruder will wipe its nozzle on the ooze shield. This way, the oozed material won't fall on the model surface.

![The ooze shield gets printed with the first extruder of a layer, causing an alternating pattern if printing with two extruders](../images/ooze_shield.png)
![Some parameters can be adjusted for the ooze shield](../images/ooze_shield.svg)

The ooze shield will print up to the height of the highest extruder switch. Above that height, no nozzle will be moved into the print after being on stand-by mode, so printing an ooze shield is unnecessary. 

The ooze shield is thin enough to break or cut easily, and keeps its distance from your model so that it can be removed without scarring the surface.