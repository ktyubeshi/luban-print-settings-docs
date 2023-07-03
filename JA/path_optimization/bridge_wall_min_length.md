最小ブリッジ壁長
====
この設定では、ブリッジ壁の最小長さを指定できます。最小長さより短い壁はブリッジとは見なされず、ただの突出した壁となり、それらの壁を印刷するための通常の設定を使用します。最小ブリッジ壁長よりも長く支えられていない壁はブリッジとしてマークされます。

短いラインピースのブリッジはしばしば効果がありません。これらのラインは、短い距離だけブリッジする必要があるため、大きくたわむことはありません。しかし、ブリッジ技術が使用された場合、[フローレート](bridge_wall_material_flow.md)と[速度](bridge_wall_speed.md)も調整されます。これにより、ノズルからのノズルの流出速度が変化し、一部の部分では過剰押出しが発生し、他の部分では押出し不足が発生します。非常に短い壁の部分をフィルタリングすることで、フローレートはそれらの部分では中断されないが、フローレートを調整することが重要な場所では、オーバーハングの品質が依然として向上します。

---

Minimum Bridge Wall Length
====
This setting allows you to specify a minimum length for bridged walls. Any walls shorter than this minimum length are not seen as bridging but just overhanging walls, and are printed using the normal settings for printing those walls. Any walls that go unsupported for longer than the Minimum Bridge Wall Length will be marked as bridging.

Bridging short line pieces is often ineffective. These lines won't sag a lot anyway because they need to bridge only a short distance. However if the bridging technique is used, then the [flow rate](bridge_wall_material_flow.md) and [speed](bridge_wall_speed.md) will be adjusted as well. This will change the rate at which nozzle flows out of the nozzle, produces overextrusion in some parts and underextrusion in others. By filtering out very short pieces of walls, the flow rate won't be interrupted for those but the quality of overhangs will still be better for places where it is important to adjust the flow rate.