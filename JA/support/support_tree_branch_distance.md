ツリーサポート枝間距離
====
### **説明**
この設定は、枝がモデルに触れる2つの隣接する枝間の距離を決定します。

![1.4mm離れた場所で配置された枝](../images/support_tree_branch_distance_1_4.png)
![5mm離れた場所で配置された枝](../images/support_tree_branch_distance_5.png)

通常のサポートと異なり、ツリーサポートは大きな平らな屋根を持つモデルには対応していません。代わりに、ツリーサポートは疎な小枝でモデルを支え、多くの小さな接触点を作り出します。ツリーサポート枝間距離を設定することで、各接触点がどれほど離れて配置されるかを調整することができます。

### **使用法**
枝間距離を減少させることで、サポートの上に横たわるラインが橋を架ける必要がなくなり、より良いオーバーハング品質を達成することができます。また、サポートの頂部に向かってより多くの材料を使うようになるので、サポートがより硬くなり、プリントがより信頼性の高いものになります。

ただし、枝間距離を減少させると、サポートに必要な材料と印刷時間が増えます。

枝間距離を[枝の直径](support_tree_branch_diameter.md)以下に減少させると、枝が適切に形成される前に結合してしまう可能性があります。その結果、大きなオーバーハングエリアの中心部が適切にサポートされないことがあります。

---

Tree Support Branch Distance
====
### **Description**
This setting determines the distance between two adjacent branches where the branches touch the model.

![Branches placed 1.4mm apart](../images/support_tree_branch_distance_1_4.png)
![Branches placed 5mm apart](../images/support_tree_branch_distance_5.png)

Unlike Normal Support, the Tree Support does not support the model with a large flat roof. Instead, the tree support supports the model with sparse small branches, thus creating a lot of small contact points. By setting Tree Support Branch Distance, you can adjust how far apart each contact point are placed. 

### **Usage**
By reducing the branch distance, a better overhang quality can be achieved because the lines resting on top of the support won't need to bridge as far. The support will also be stiffer because more material will be used towards the top of the support, making the print more reliable.

However reducing the branch distance will also cause the support to take more material and printing time.

Reducing the branch distance below the [branch diameter](support_tree_branch_diameter.md) will cause the branches to merge before they could properly be formed. As a result the centre of large overhang areas may not get supported properly then.