最小薄壁線幅
====
この設定は、実際にはそれらにとって大きすぎる線幅で非常に小さな詳細を印刷することを可能にします。非常に細い線を印刷する代わりに、それはより合理的な線幅で印刷します。

[最小機能サイズ](min_feature_size.md)が非常に低い場合、非常に薄い部分が印刷されることがあります。これはうまく機能しません。ノズルサイズより小さい線を印刷することは可能ですが、それほど大きくはありません。あまりにも細い線を印刷すると、押し出しが不規則になります。

代わりに、非常に細い線はより幅広く作られ、もっと一貫した押出しができるようになります。モデルの一部が最小薄壁線幅よりも細い場合、その部分は最小薄壁線幅の単一の線を使って印刷されます。その後、線はモデルの元の幅よりも広くなります。これにより寸法精度が低下しますが、少なくとも信頼性の高い印刷が可能になります。

この設定値は、プリンターが表面が粗くなったり、押出しが不一致になったりする前に、確実に達成できる最小の線幅を指定する必要があります。これは通常、ノズルサイズとノズルサイズの半分の間のどこかです。これを増やすと、薄い部品が太過ぎて印刷される可能性がありますが、あまりにも細い線を印刷しようとして押し出しが不足するリスクを減らします。

---

Minimum Thin Wall Line Width
====
This setting allows printing very tiny details with a line width that is actually too big for them. Instead of printing very thin lines, it prints with a more reasonable line width.

If the [Minimum Feature Size](min_feature_size.md) is very low, some very thin parts could be printed. This doesn't work well. It's possible to print lines smaller than the nozzle size, but not by much. Printing too thin lines lead to inconsistent extrusion.

Instead, those very thin lines are made wider so that they extrude more consistently. Any part of the model that is thinner than the Minimum Thin Wall Line Width will get printed using a single line of the Minimum Thin Wall Line Width. The lines then become wider than the original width of the model. This reduces dimensional accuracy, but at least it will print reliably.

The value of this setting should be the thinnest line width that the printer can reliably achieve before it starts creating rough surfaces and inconsistent extrusion. This is normally somewhere between the nozzle size and half the nozzle size. Increasing it leads to thin parts being printed too fatly, but reduces the chance of underextrusion due to trying to print lines that are too thin.