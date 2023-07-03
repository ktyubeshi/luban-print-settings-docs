最大後退数
====
### **説明**
フィーダーホイールは、フィラメントを適切に動かすためにフィラメントにグリップする必要があります。材料をよく後退させると、フィーダーホイールがフィラメントを磨耗させる傾向があり、フィラメントを適切にグリップできなくなることがあります。この設定は、この研削を防ぐために、特定のフィラメントの長さ内での後退回数を制限します。

この設定は、フィラメントが[最小押出距離ウィンドウ](retraction_extrusion_window.md)設定に示されるフィラメントの長さ中、何度後退できるかを示します。このウィンドウ中にさらに後退が発生した場合、後退せずに移動のみが行われます。

![フィラメントの特定の長さ中の後退の視覚化](../images/retraction_count_max.svg)

後退回数が制限されるフィラメントの長さは、スライディングウィンドウです。例えば、ウィンドウの長さが3ミリメートルで、最大後退数が10回の場合、これはフィラメントの3ミリメートル内で10回以上の後退を行うことはできないという意味です。

### **使い方**
最大後退数を減らすと、フィラメントの研削が減少します。これは、PVAのような柔らかい材料に便利です。しかし、一部の必要な位置で後退しなくなる可能性があるため、ストリング化も増加します。

---

Maximum Retraction Count
====
### **Description**
The feeder wheel needs to grip into the filament in order to move it properly. Retracting the material often tends to cause the feeder wheel to wear down the filament to the point where it can no longer grip the filament properly. This setting limits the number of retractions within a certain length of filament in order to prevent this grinding.

The setting indicates how often the filament is allowed to be retracted during the length of filament indicated by the [Minimum Extrusion Distance Window](retraction_extrusion_window.md) setting. Any further retractions during this window will not retract, but just travel without retracting.

![Visualisation of retractions during a certain length of filament](../images/retraction_count_max.svg)

The length of filament during which the number of retractions is limited is a sliding window. For instance, with a window length of 3 mm and a maximum retraction count of 10, this means that no more than 10 retractions can be made within the 3 mm of filament.

### **Usage**
Reducing the maximum retraction count will reduce grinding on the filament. This is useful for softer materials, such as PVA. However it will also increase stringing, because it might no longer retract in some necessary positions.