最小押出距離ウィンドウ
====
### **説明**
フィーダーホイールは、材料を適切に動かすためにフィラメントにグリップする必要があります。素材を引き込むと、フィーダーホイールがフィラメントを摩耗させて、適切にフィラメントをグリップできなくなることがよくあります。この設定は、このような摩耗を防ぐために、特定のフィラメントの長さ内でのリトラクションの回数を制限します。

リトラクションは、[最大リトラクション数](retraction_count_max.md) とこの設定の組み合わせによって制限されます。材料は、この最小押出距離ウィンドウの設定によって示されるフィラメントの長さ内で、最大リトラクション数の値を超えて引き込むことは許されません。

![リトラクションの数が制限されるフィラメントの特定の長さ](../images/retraction_count_max.svg)

リトラクションの数が制限されるフィラメントの長さは、スライディングウィンドウとなります。例えば、ウィンドウ長が3mmで最大リトラクション数が10の場合、これはフィラメントの3mm以内で10回以上のリトラクションを行うことはできません。

### **使用方法**
押出しウィンドウの長さを増やすと、フィラメントの摩耗が減少します。これにより印刷の信頼性が向上しますが、表面のストリングやブロブの量が増えます。これは特に、摩耗に対して敏感なより柔らかい材料にとって非常に有用です。

---

Minimum Extrusion Distance Window
====
### **Description**
The feeder wheel needs to grip into the filament in order to move it properly. Retracting the material often tends to cause the feeder wheel to wear down the filament to the point where it can no longer grip the filament properly. This setting limits the number of retractions within a certain length of filament in order to prevent this grinding.

The retractions are limited by the combination of [Maximum Retraction Count](retraction_count_max.md) and this setting. The material is not allowed to be retracted more than the value of the Maximum Retraction Count within a length of filament indicated by this Minimum Extrusion Distance Window setting.

![A certain length of filament along which the number of retractions is limited](../images/retraction_count_max.svg)

The length of filament during which the number of retractions is limited is a sliding window. For instance, with a window length of 3 mm and a maximum retraction count of 10, this means that no more than 10 retractions can be made within the 3 mm of filament.

### **Usage**
Increasing the length of the extrusion window will reduce grinding on the filament. This makes the print more reliable, but increases the amount of stringing and blobs on the surface. This is especially useful for softer materials that are more sensitive to grinding.