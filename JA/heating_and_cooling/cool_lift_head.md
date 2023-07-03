リフトヘッド
====
リフトヘッドが有効になっていると、ツールヘッドはレイヤーの最後まで到達したときに少し上昇し、最小レイヤータイムが経過するのを待ちます。

レイヤーが非常に小さく、通常の印刷速度で印刷すると最小レイヤータイムよりも短い時間で印刷できる場合、その実際の印刷速度はレイヤーが最小レイヤータイムで印刷するように減速します。しかし、印刷速度は最小速度を下回ることはありません。最小速度でレイヤーを印刷すると、最小レイヤータイムよりも短い時間で印刷できる場合、プリンターはレイヤーの最後まで待つことになります。リフトヘッドを有効にすると、ツールヘッドが非常に小さなレイヤーの印刷を終えたときに少し上昇します。

この設定が無効になっている場合、印刷ヘッドはノズルが印刷物に触れたままレイヤーの最後で待機します。

![最小レイヤータイムに達すると、ヘッドは上がるかもしれません](../images/cool_fan_speed.svg)

プリントヘッドは常に3mm上昇します。現在、これを設定する方法はありません。

---

Lift Head
====
With Lift Head enabled, the toolhead will rise up a bit when it reaches the end of a layer waiting for the Minimum Layer Time to pass.

If a layer is so small that it would take less than the Minimum Layer Time to print at regular printing speed, then its actual printing speed will be reduced so that the layer still takes the Minimum Layer Time to print. But the printing speed will not be reduced below the Minimum Speed. If printing the layer at Minimum Speed would take less than the Minimum Layer Time, the printer will wait at the end of the layer until the Minimum Layer Time has passed. Enabling Lift Head is to make the toolhead lift up a bit when it finish printing the very small layer.

If this setting is disabled, then the print head will wait at the end of the layer with the nozzle touching the print.

![When the minimum layer time is reached, the head may lift up](../images/cool_fan_speed.svg)

The print head will always move up by 3 mm. There is no setting to configure this at the moment.