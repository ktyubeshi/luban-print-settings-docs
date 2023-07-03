サポートインターフェースの解像度
====
Lubanは、モデルとZ方向で接触する場所を確認することにより、サポートインターフェースが出力される場所を決定する必要があります。この設定は、チェックする解像度を決定します。

この設定を増やすと、Lubanはより低い解像度でサンプリングし、スライシングをスピードアップします。ただし、増やしすぎると、サポート上部または下部のモデルが非常に薄い場合、Lubanはサポートインターフェースの配置をスキップする可能性があります。もしモデルが非常に薄い場合、Lubanのサンプリングはモデルを見落とし、そこにサポートインターフェースを配置すべきだということに気付かない可能性があります。

---

Support Interface Resolution
====
Luban needs to determine where the support interface is printed by checking where it comes into contact with the model in the Z-direction. This setting determines the resolution at which it checks.

Increasing this setting causes Luban to sample at a lower resolution, which speeds up slicing. However increasing it too much can cause Luban to skip placing support interface if the model above or below the support is very thin. If the model is very thin, Luban's sampling could skip over the model, not noticing that it should place support interface there.