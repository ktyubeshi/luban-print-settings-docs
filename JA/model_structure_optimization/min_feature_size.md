最小機能サイズ
====
この設定は、印刷されるモデルの詳細の最小幅を制御します。これより細いものは印刷されません。

ノズルサイズよりも小さい詳細は、うまく印刷されない可能性があります。これはプリンターの制約です。しかし、Lubanはそれらを印刷することを試みることができますが、それはきれいな押し出し率を持たないか、または詳細がモデル化されたものよりも厚くなることを受け入れています。

「最小機能サイズ」を減らすと、プリンターは印刷物のより小さい詳細を印刷します。[最小薄壁ライン幅](min_bead_width.md)によりますが、これらの小さな詳細は、非常に少ない押し出し（[押し出し不足](../troubleshooting/underextrusion.md)を引き起こす可能性があります）または、より合理的なライン幅を押し出しでも、それらを大きく印刷することによって印刷されることがあります。この値を0に設定すると、プリンターはすべての鋭い角の先端まで完全に進みます。

最小機能サイズを大きくすると、プリンターはやっぱりうまくいかない小さな詳細には手を出さないようになります。これは少しの時間を節約し、印刷物がきれいに仕上がる可能性があります。

---

Minimum Feature Size
====
This setting controls the minimum width of details of the model that will be printed. Anything thinner than this will not get printed.

Details that are smaller than the nozzle size are not likely to print well. This is a limitation of the printer. However Luban can still attempt to print them, accepting that it will not have a nice extrusion rate, or that the details will end up thicker than modelled.

Reducing the Minimum Feature Size makes the printer print smaller details of the print. Depending on the [Minimum Thin Wall Line Width](min_bead_width.md), these tiny details may be printed by extruding very little (causing [underextrusion](../troubleshooting/underextrusion.md)), or by extruding more reasonable line widths but printing them over-sized. Setting this value to 0 makes the printer go all the way into the very tips of every sharp corner.

Increasing the Minimum Feature Size makes the printer not bother with small details that wouldn't come out nicely anyway. This saves a bit of time and could make the print come out cleaner.