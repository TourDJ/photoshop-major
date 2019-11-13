# photoshop 主修及设计相关知识的充电。

## 色彩

### 色光三原色和 RGB 色彩模型
RGB模式是以色光三原色为基础建立的色彩模式。

### 色料三原色和 CMYK 色彩模型
CMYK是一种依靠反光的色彩模式。

### HSB 色彩模型
在`HSB`模式中，H(hues)表示色相，S(saturation)表示饱和度，B（brightness）表示亮度。

* 色相（H,hue）：在0~360°的标准色轮上，色相是按位置度量的。在通常的使用中，色相是由颜色名称标识的，比如红、绿或橙色。黑色和白色无色相。
* 饱和度（S,saturation）：表示色彩的纯度，为0时为灰色。白、黑和其他灰色色彩都没有饱和度的。在最大饱和度时，每一色相具有最纯的色光。取值范围0～100%。
* 亮度（B,brightness或V,value）：是色彩的明亮度。为0时即为黑色。最大亮度是色彩最鲜明的状态。取值范围0～100%。

HSB模式中S和B呈现的数值越高，饱和度明度越高，页面色彩强烈艳丽，对视觉刺激是迅速的，醒目的效果，但不益于长时间的观看。

### Lab 色彩模型
 Lab 被视为与设备无关的颜色模型。Lab 色彩模型是由亮度（L）和有关色彩的a, b三个要素组成。

* L表示亮度（Luminosity），a表示从洋红色至绿色的范围，b表示从黄色至蓝色的范围。
* L的值域由0到100，L=50时，就相当于50%的黑；
* a和b的值域都是由+127至-128，其中+127 a就是红色，渐渐过渡到-128 a的时候就变成绿色；同样原理，+127 b是黄色，-128 b是蓝色。

所有的颜色就以这三个值交互变化所组成。例如，一块色彩的Lab值是L = 100，a = 30, b = 0, 这块色彩就是粉红色。（注：此模式中的a轴,b轴颜色与RGB不同，洋红色更偏红，绿色更偏青，黄色略带红，蓝色有点偏青色）

### 参考资料
[色彩原理解析：其实我们生活在一个“无色”的世界里](https://zhuanlan.zhihu.com/p/53547719)      


## Photoshop 主要知识点

### 图层
Photoshop 图层就如同堆叠在一起的透明纸。您可以透过图层的透明区域看到下面的图层。可以移动图层来定位图层上的内容，就像在堆栈中滑动透明纸一样。也可以更改图层的不透明度以使内容部分透明。

#### 基本概念
智能对象是包含栅格或矢量图像（如 Photoshop 或 Illustrator 文件）中的图像数据的图层。智能对象将保留图像的源内容及其所有原始特性，从而让您能够对图层执行非破坏性编辑。

背景图层是图层调板中最底部的图层。在从扫描仪或数码相机导入图像时，整个图像将被置于背景图层上。

复合图像是由多个图像合并而成的一个图像。

拼合的作用是将所有可视图层合并到背景图层，以此来减小文件的大小。

## 通道

栅格化是将向量图形格式表示的图像转换成位图以用于显示器或者打印机输出的过程。

- [快捷键](shortcut.md)     
