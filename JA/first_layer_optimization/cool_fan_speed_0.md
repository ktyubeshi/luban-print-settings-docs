初期ファン速度
====
### **説明**
初期ファン速度は、印刷開始時のツールヘッド上のファンの回転速度です。

ファン速度は[レギュラーファン速度が層で](cool_fan_full_layer.md)設定したものに基づいて、初期ファン速度からレギュラーファン速度へ段階的に変化します。例えば、初期ファン速度を0%、レギュラーファン速度を100%、レギュラーファン速度を層で6に設定した場合、ファン速度は0%から始まり、最初の5層の印刷中に連続して増加し、6層で100%に達します。

### **使用方法**
初期ファン速度は通常、レギュラーファン速度よりも低く設定されます。これにより、素材がより遅く冷却し、さらにビルドプレートに下がり、ビルドプレートの接着性が向上します。

---------------------------
Initial Fan Speed
====
### **Description**
Initial Fan Speed is the rotation speed of the fans on the toolhead at the beginning of the printing. 

The fan speed will gradually transition from the Initial Fan Speed to the Regular Fan Speed based on the [Regular Fan Speed At Layer](cool_fan_full_layer.md) you set. For example, if you set the Initial Fan Speed to 0%, the Regular Fan Speed to 100%, and Regular Fan Speed At Layer to 6, then the fan speed will begin at 0%, continuously increase during the printing of the first five layers, and reach 100% at the sixth layer.

### **Usage**
The Initial Fan Speed is normally set lower than the Regular Fan Speed. This allows the material to cool down slower and sag further onto the build plate, and thus improves build plate adhesion.
