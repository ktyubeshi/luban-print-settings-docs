Filter Out Tiny Gaps
====
壁の間に穴を埋めると、追加の移動が必要になります。もし穴が非常に小さい場合、材料は通常、ノズルから十分に流れ出す時間を得ることはできません。この設定を有効にすると、プリンターは一部の最も小さい穴をスキップできます。

2つの壁の外側の幅よりも小さい穴は「ティニーギャップ」としてカウントされます。例えば、[外壁ライン幅](../resolution/wall_line_width_0.md)が0.4 mmに設定されている場合、面積が0.4 mm × 0.4 mm × 2 = 0.32 mm²以下の穴は埋められません。

filter_out_tiny_gaps.md

-------
Filter Out Tiny Gaps
====
Filling gaps between walls introduces extra travel moves. If the gaps are extremely small, the material will typically not get enough time to flow out the nozzle very well. If this setting is enabled, the printer can skip some of the smallest gaps.

Gaps smaller than 2 square outer wall line widths count as "tiny gaps". For instance, if your [Outer Wall Line Width](../resolution/wall_line_width_0.md) is set to 0.4 mm, gaps with an area no larger than 0.4 mm × 0.4 mm × 2 = 0.32 mm² will not get filled.