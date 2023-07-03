後退最小移動距離
====
この設定は、非常に短い移動距離のための材料の後退を防ぎます。これらの移動中にはノズルから材料が滲み出る時間はほとんどありませんので、後退させるとむしろ害がある場合があります。

![一番短い移動は後退していない](../images/retraction_min_travel.png)

材料を後退させる目的は、糸引きを防ぐことです。非常に短い移動は、材料がまだノズルから出る時間を持っていないため、糸引きを引き起こしません。文字幅程度の極端に短い移動距離では、糸引きが生じる余地さえありません。それに対して、後退するとノズルは一時停止し、材料が流れ出ます。これにより、後退が発生する位置にブロブが生成されます。そのため、短距離移動時に後退しない方が、モデルの見える部分に対するトラックであっても、良い傾向があります。

この設定を過度に増やすと、モデルの詳細部分や部品が密接している部分で糸引きが発生します。

---

Retraction Minimum Travel
====
This setting prevents the material from retracting for very short travel moves. During those travel moves there is very little time for the material to ooze out of the nozzle anyway, so retracting would do more harm than good.

![The shortest travel move in the middle is not retracted](../images/retraction_min_travel.png)

Retracting the material is intended to prevent stringing. Very short travel moves don't produce stringing, because the material has not yet had the time to flow out of the nozzle. For extremely short travel moves of one line width or so, there will even be no room for any stringing. On the other hand, retracting causes the nozzle to stand still for a short while, while the material is flowing. This will produce a blob on the position where retraction occurs. For those reasons it tends to be better to not retract when travelling short distances, even if those tracks are on visible parts of the model.

Increasing this setting too much will cause stringing in detailed parts of the model or where parts are close together.