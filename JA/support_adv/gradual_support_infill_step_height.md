漸進的なサポートインフィル段階高さ
====
### **説明**
漸進的なサポートを使用すると、支持体の密度が上から下にかけて数ステップで周期的に減少します。各ステップで、サポートの密度が半減します。この設定は、これらのステップの高さ、つまりサポート密度が半分になる二つの場所の間隔を指します。

![1mm step height](../images/gradual_support_infill_step_height_1mm.png)
![3mm step height](../images/gradual_support_infill_step_height_3mm.png)

その性質上、漸進的なサポートでは一部のサポートが宙ぶらりんになります。しかし、これは通常自動的に修復されます。最初のサポート層は空中に吊り下がり、サポートの側面にだけ適切に接続します。その上の層は前の層の端部に少し休むことができますが、中央ではたれ下がります。これは、層ごとに徐々に改善されます。漸進的なサポートのステップ高さが十分に大きい場合、次の密度ステップが発生するまでにサポートが適切に頑丈になります。

### **使用法**
漸進的なサポートインフィルステップ高さを減らすと、サポートが素早く低密度に下がります。これにより、印刷時間と材料の使用が節約されます。サポートが次の密度ステップが発生するまでに自己修復する十分なスペースを得られない場合、漸進的なサポートインフィルステップ高さを増やします。この設定の値を増やすと、印刷の信頼性が向上します。

---

Gradual Support Infill Step Height
====
### **Description**
When using gradual support, the density of the support gets periodically reduced from top to bottom in several steps. At each step, the support density is halved. This setting indicates the height of these steps, the distance between two places where the support density is halved.

![1mm step height](../images/gradual_support_infill_step_height_1mm.png)
![3mm step height](../images/gradual_support_infill_step_height_3mm.png)

Gradual support by its nature will suspend some of the support in mid-air. However this normally repairs itself automatically. The first layer of support will hang in mid-air and only attach to the sides of the support properly. The layers on top of it can rests on the previous layer a bit on the ends, but will sag in the middle. This gradually gets better, layer by layer. If the gradual support step height is large enough, the support is properly sturdy by the time the next density step occurs.

### **Usage**
Reduce the Gradual Support Infill Step Height can make the support quickly descend to a low support density. This saves on printing time and material use. Increase the Gradual Support Infill Step Height if the support will not get enough room to repair itself by the time the next step in support density occurs. Increasing the value of this setting makes the print more reliable.