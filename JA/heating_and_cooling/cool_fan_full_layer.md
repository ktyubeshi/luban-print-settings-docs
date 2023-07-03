レイヤーでの通常のファン速度
====
### **説明**
レイヤーでの通常のファン速度は、初期ファン速度から通常ファン速度に移行するレイヤーを設定します。

印刷の開始時に、ツールヘッドは初期レイヤーの初期ファン速度を低く設定します。その後、ファン速度は徐々に上がり、設定したレイヤーで通常のファン速度に到達します。例えば、初期ファン速度を0％、通常ファン速度を100％、レイヤーでの通常ファン速度を6に設定した場合、ファン速度は0％から始まり、最初の5層の印刷中に徐々に上がり、6層目で100％に到達します。

![どのファン速度がどこで使われるか](../images/cool_fan_speed.svg)

### **影響**
通常、初期ファン速度は、反りを防ぎ、ビルドプレートの粘着力を高めるために、かなり低く設定されています。しかし、初期レイヤーを印刷した後でも、ファン速度を急に上げるとリスクがあります。最初の数層が素早く冷却されると、それらは縮小し、シア輸送により最初のレイヤーを引き上げてしまい、印刷が反り上がってしまう可能性があります。この設定の目的は、低いファン速度で複数のレイヤーを印刷することを可能にすることです。このようにすると、印刷物が反りを抵抗する十分な剛性を持つまで、反りを防ぐことができます。

### **使用法**
* この設定を増やすことで、ベッドの粘着力を向上させることができます。
* ビルドプレートが高温に加熱されている場合、[象の足](../troubleshooting/elephants_foot.md)や滲みを防ぐために、この設定を減らす必要があるかもしれません。

---

Regular Fan Speed at Layer
====
### **Description**
Regular Fan Speed at Layer configures the layer at which the fan speed is transitioned from Initial Fan Speed to Regular Fan Speed.

At the beginning of the print, the toolhead will use the lower Initial Fan Speed for the initial layer. Then, the fan speed will gradually increase and finally reach the Regular Fan Speed at the layer you set. For example, if you set the Initial Fan Speed to 0%, the Regular Fan Speed to 100%, and Regular Fan Speed At Layer to 6, then the fan speed will begin at 0%, continuously increase during the printing of the first five layers, and reach 100% at the sixth layer.

![Which fan speed is used where](../images/cool_fan_speed.svg)

### **Influence**
Normally, the Initial Fan Speed is set considerably lower to prevent warping and increase build plate adhesion. However, after the initial layer is printed, it may still be risky to increase the fan speed too suddenly. If the first few layers cool down too quickly, they may still shrink and through shear friction pull the first layer up, warping the print as well. The purpose of this setting is to allow printing multiple layers with a lower fan speed. This way, the warping can be prevented until the print has sufficient stiffness to resist the warping.

### **Usage**
* Increasing this setting can improve bed adhesion.
* If your build plate is heated to a high temperature, you might need to reduce this setting in order to prevent [elephant's foot](../troubleshooting/elephants_foot.md) or oozing.