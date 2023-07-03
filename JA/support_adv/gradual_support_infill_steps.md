漸進的なサポートインフィルステップ
====
### **説明**
漸進的なサポートは、下層のサポート密度を減らすことで、使用するサポート材料の量を減らします。これにより、印字時間と材料が節約され、かつオーバーハングの品質があまり低下しません。サポートの主な目的は、オーバーハング部分をサポートすることです。この機能は、その目的だけにサポートを集中させます。

この設定は、サポート密度が何段階で減少するかを示しています。各ステップでは、サポートの密度が半分になります。例えば、密度が20%から始まり、2つの段階的なサポートステップがある場合、下部のサポート密度はそれぞれ10%と5%になります。

![サポートが3段階で低密度になる](../images/gradual_support_infill_step_height_1mm.png)

### **使用法**
ステップの数を増やすと、密度がどんどん半分になり、結果的にサポートの密度が下がります。これにより、多くの材料と印刷時間が節約されますが、サポートが弱くなります。

サポートの一部は空中に浮いていることになります。しかし、実際には、ほとんどのサポートパターンでは、層が弱くなった下層でも適切に構築できるため、すぐに自己修復します。[Gradual Support Infill Step Height](gradual_support_infill_step_height.md)の目的は、次の段階的なサポートステップが上に積み重ねられる前に、層が自己修復するのに十分な時間を与えることです。

この設定は、少なくとも1つの[Support Wall Line](../support/support_wall_count.md)と組み合わせて使用するのが最適です。これにより、サポートラインが何かに掛かることができ、ただ空中に浮かんでいるだけでなくなります。

---

Gradual Support Infill Steps
====
### **Description**
Gradual support reduces the amount of support material used, by reducing the support density in the lower layers. This saves on printing time and material, while not reducing the overhang quality much. The primary purpose of support is to support overhanging areas. This feature focuses the support to that purpose only.

This setting indicates in how many steps the support density gets reduced. At every step, the support's density is halved. For example, starting at a density of 20% and two gradual support steps, the support density of the lower parts will be 10% and 5% respectively.

![The support is reduced to lower density in 3 steps](../images/gradual_support_infill_step_height_1mm.png)

### **Usage**
Increasing the number of steps cause the density to be halved more and more, resulting in lower density support. This saves a lot of material and printing time, but will make the support weaker.

Some of the support will be floating in mid-air. However in practice with most support patterns this will repair itself quickly as the layers can build up properly even on weakened lower layers. The intent of the [Gradual Support Infill Step Height](gradual_support_infill_step_height.md) is to allow sufficient time for the layers to repair themselves before the next gradual support step is piled on top.

This setting is best combined with at least one [Support Wall Line](../support/support_wall_count.md). This gives the support lines something to hang on to, rather than being suspended in mid-air.
