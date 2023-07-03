シームコーナー設定
====
### **説明**
この設定では、モデルの角に対するシームの位置を制御できます。

一般的には、シームを配置する場所は2つあります: 内側の角に隠すか、外側の角に露出させるかです。シームを内側の角に隠すことは、シームがそこではほとんど目立たないため、一般的に好ましいです。しかし、ナイフでシームを切り取ったり、サンドペーパーで滑らかにするために、外側の角に配置することも可能です。

### **使い方**
この設定には以下のオプションがあります:
* **None:** 角はまったく配慮されません。シームは、[Z Seam Alignment](z_seam_type.md)の条件に最も合うものが選ばれます。
* **Hide Seam:** 内側の角にシームを隠すことを優先します。Z Seam Alignmentが "Sharpest Corner"に設定されている場合、最も内側の角が常に選ばれます。"Shortest"に設定されている場合、ノズルが前の層を終了する位置近くの内側の角を選択します。
* **Expose Seam:** 外側の角にシームを露出することを優先します。Z Seam Alignmentが "Sharpest Corner"に設定されている場合、最も鋭角の外角が必ず選ばれます。 "Shortest"に設定されている場合、ノズルが前の層を終了する位置近くの外側の角を選択します。
* **Hide or Expose Seam:** 内側の角でも外側の角でも、フラットな壁以外の鋭角の角にシームを配置します。
* **Smart Hiding:** "Hide or Expose Seam"と同じく鋭角の角にシームを配置しますが、輪郭内に内側の角が存在する場合、内側の角が外側の角よりも優先されます。内側の角がない場合は、外側の角を選択します。

---

Seam Corner Preference
====
### **Description**
With this setting you can control how the seams will be positioned relative to corners in your model.

Generally there are two options for where the seam can be placed: hidden in an inside corner, or exposed in an outside corner. Hiding the seam in an inside corner is generally preferable since the seam will hardly be visible there. But it is also possible to put it on an outside corner so that you can cut off the seam with a knife or sand it smooth with some sand paper, if some post-processing can be done on the part.

### **Usage**
The following options are available for this setting:
* **None:** There is no preference for corners at all. The seam will be chosen to match the requirements for [Z Seam Alignment](z_seam_type.md) best.
* **Hide Seam:** This will prefer to hide the seam in an inside corner. If Z Seam Alignment is set to "Sharpest Corner", the very innermost corner is always chosen. If Z Seam Alignment is set to "Shortest", it will choose an inside corner near the position at which the nozzle finishes the previous layer.
* **Expose Seam:** This will prefer to expose the seam on an outside corner. If Z Seam Alignment is set to "Sharpest Corner", the very sharpest outer corner is always chosen. If it's set to "Shortest", it will choose an outside corner near the position at which the nozzle finishes the previous layer.
* **Hide or Expose Seam:** This will place a seam on a sharp corner, be it an inside corner or outside, as long as it's not on a flat wall.
* **Smart Hiding:** This will place the seam on a sharp corner just like "Hide or Expose Seam", but inside corners will be more preferable than outside corners if any inside corners are available in the contour. If there are no inside corners, it will choose an outside corner.