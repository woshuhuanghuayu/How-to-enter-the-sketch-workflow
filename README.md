# How-to-enter-the-sketch-workflow
如何从ps工作模式过渡到sketch工作流下，实现团队合作，提升整体效率
# sketch工作流遇到的问题以及如何解决
## 一、软件安装
由于sketch官方对软件的更新非常频繁，不建议去找破解版。还是建议去官网购买正版，对比PS，反正也不贵！
## 二、工作前期准备
### 1）插件选择
由于sketch本身的功能不多，开始工作前安装一些必备的插件是可以大幅度提高工作效率的。插件安装神器：Sketch Toolbox 下载地址  http://sketchtoolbox.com
我工作过程中常用的一些插件：

<img src="img/12.png" width="300"/>

资料：Sketch 有哪些插件值得推荐？
https://www.zhihu.com/question/27495264 根据自己的需要下载

- 优秀插件收集：https://github.com/zifeixu85/Better-Sketch 
- 生成随机中文名插件：https://github.com/JJYing/Fake-Chinese-Name-for-Sketch

### 2）快捷键学习
由于sketch一些工具不是太直接，或者靠点击不是太效率，记住一些常用的快捷键是很有必要的。当然，不嫌麻烦的话也可以自定义快捷，改回跟PS一样的快捷键。

* 常用快捷键：http://www.ui.cn/detail/17479.html
* 自定义快捷键：http://www.zcool.com.cn/article/ZNDA5ODI0.html

### 3）一些基本的软件知识学习
* 教程1：https://zhuanlan.zhihu.com/p/21359496 （一些技巧，插件介绍）
* 教程2： https://maimai.cn/article/detail?fid=77633319&from=single_feed&share_user=http%253A%252F%252Fi9.taou.com%252Fmaimai%252Fp%252F2074%252F2965_90_b2usF19sYi8xzi-a160 （一些技巧学习）
* 教程3：http://www.ui.cn/detail/157249.html  （sketch工作前可以提高效率的准备工作）
* 教程4：http://www.ui.cn/detail/31273.html （学习资料汇总贴）

## 三、新建文件
### 1、sketch新建画布默认尺寸比平时PS新建的尺寸小？

sketch现在鼓励一倍图的设计，所以更改了初始模板的尺寸，现在很多设计师都是一倍图设计啊，优点就是占资源小，文件小，方便生成多倍图！

## 四、设计过程中
### 1、字体行高问题
这个Line是指文本的实际高度，测试发现会比size小，比如这里是14size，实际文本占的高度是10.
实际设计标注中，不要去掉文字的外框，因为在系统默认字体苹方或者思源体的情况下，这个外框正好是开发那边文本控件的高度。
### 2、使用Sketch设计时，中英文混排时如何设置字体？
通过插件先设置好默认使用的字体，然后通过插件修改段落中英文的字体。
我更常用的方式是选择需要修改的字体直接修改就好了。
https://www.zhihu.com/question/26534333 （问题资料）
### 3、如何在sketch中使用UI模板里面的图标？
可以引申到如何使用团队模板文件，cmd+shift+v 复制到需要该元素的位置，再进行修改，最好不要在模板文件中直接修改，待确定需要修改后再调整模板。

https://www.zhihu.com/question/49339932  （问题资料）
### 4、Sketch 使用时，如何在选中对象或者对象组时，在画板内用鼠标拖动对象，而不会误点到上层的对象？
* 1）左侧选中一个或多个编组，右侧检查器中取消勾选“Click-through when selecting”
* 2）当元素很小，不好选择时，可以按住command键，鼠标拖动框选来选择元素。

### 5、使用UI设计工具Sketch如何解决色彩管理、矢量图形绘制等具体问题？
* 1）色彩管理：
   Sketch导入图片和导出图片，色彩会发生变化。问题来源是修改了电脑本身的颜色模式。改回默认的颜色模式即可解决！
* 2）矢量图绘制
   个人觉得，复杂一些的矢量绘制，建议在AI里绘制好复制到Sketch。
   一些简单的图形，可以直接在sketch里进行绘制。

后期熟练掌握sketch布尔运算后一样可以直接进行复杂图标的设计。

https://www.zhihu.com/question/24072939

### 6、Sketch钢笔工具画完的路径如何闭合？
用sketch的钢笔工具画形状的时候，画了一次按esc退出后，又想把路径闭合成一个完整的形状，怎么才能闭合路径呢？

 <img src="img/%E9%92%A2%E7%AC%94%E5%B7%A5%E5%85%B7%E8%B7%AF%E5%BE%841.png" width="300" />

选择这个形状按Enter，然后点击close Path

<img src="img/%E9%92%A2%E7%AC%94%E5%B7%A5%E5%85%B7%E8%B7%AF%E5%BE%842.png" width="300" />

### 7、带阴影图标，怎么确定导出切图后的大小？
把带有阴影的部分成组，然后选中组，按S，点一下这个组就会自动导出带有阴影部分的切图。如果手动切图，就需要把XY轴的偏移量补偿回去。



### 8、sketch如何解决0.1像素误差这种事情？
路径模式下，选择右上角的round to fluu pixels edges
<img src="img/0.1%E5%83%8F%E7%B4%A0%E8%AF%AF%E5%B7%AE%E9%97%AE%E9%A2%98.png" width="300">

https://www.zhihu.com/question/35256192 
### 9、sketch设计UI中字体尺寸包含空白如何准确对齐？ 
默认字体苹方或者思源黑体的情况下，保留空白区域标注，因为程序那边开发写出来的代码，文本控件也是有空白区域的。
其他字体需要单独调整
https://www.zhihu.com/question/26758579
### 10、sketch如何复制样式？
Command + Option + C ( V )

### 11、在AI中画好图标后，导出会出现样式丢失或者其他异常情况？

在AI中画好图标，应该使用存储为svg格式，不用最新AI版本里的导出svg命令即可解决问题。

## 五、切图，标注
### 1、Mac上用Sketch做的设计产出如何与还使用PC做前端开发的工程师（前端来切图）进行无缝对接？
用好切图标注软件，文件的设计，图层的划分，文本层等，交给开发那边一份zeplin或者Marketch生成的html标注页面
https://www.zhihu.com/question/36318532
### 2、界面设计中的文字还原问题 

https://zhuanlan.zhihu.com/p/21813824
### 3、用sketch切图时，导出的png会自动去掉透明区域，怎样保留透明区域的空间？ 
* 1） 建立切片区域Slice，并且和需要导出的内容放到一个组里面
    <img src="img/%E5%88%87%E5%9B%BE%E4%BF%9D%E7%95%99%E9%80%8F%E6%98%8E%E5%8C%BA%E5%9F%9F.png" width="300" />
* 2）勾选仅导出组内容
    <img src="img/%E5%88%87%E5%9B%BE%E4%BF%9D%E7%95%99%E9%80%8F%E6%98%8E%E5%8C%BA%E5%9F%9F2.png" width="300" />

* 3）确认和去掉画布背景颜色选项中的Include Export，很多时候带底色，就是因为你默认选上了导出的时候带上了背景色( Include Export )
    <img src="img/%E5%88%87%E5%9B%BE%E4%BF%9D%E7%95%99%E9%80%8F%E6%98%8E%E5%8C%BA%E5%9F%9F3.png" width="300" />
* 4）设置好尺寸然后导出就好啦。

### 4、sketch 导出图片模糊不清，不知道如何解决？ 
主要是苹果的高清屏导致的问题。实际图片被放大了2倍造成看起来模糊，实际上是没问题的。
### 5、使用 Sketch 生成 Webfont
教程见：https://zhuanlan.zhihu.com/p/19748558 
### 6、sketch文字外围的边框能不能调整成贴合文字，如果不能，是不是用sketch measure标注出来的间距都是不准的？ 
这涉及到设计和开发沟通中常见的一个问题——行高影响。

在一些非标准控件中，会涉及到自定义的间距之类的。这个时候，我们给出的是「视觉间距」，因为我们不能预估开发时这个文字对应的行高（也不可能要求开发全部设定为 1em，要被打死）。

开发看的时候，会把视觉间距换算为开发用的间距。看下面的例子：

定义 L = 标注的视觉距离；
定义 a = 某文字元素的字号；
定义 b = 此文字的行高； 

那么在开发的时候，可以这么计算：

实际距离 = L - (b-a)/2

比如标注了距离是 20pt，行高 1.5，字号 16pt，那么开发需要设定实际间距就是 15pt。

https://www.zhihu.com/question/25528295

### 7.批量导出问题

问题重现：每次导出资源时，如果是要导出多种尺寸，都需要重复设置导出参数，这样很不方便，能不能保存导出设置？

解决办法：

- 方法1：下载一个插件https://github.com/abynim/sketch-exportable 可以保存预设

- 方法2：先做好全部要切的资源，然后全选所有切片，设置一次导出设置，将资源导出。

- 方法3：下载插件https://github.com/Ashung/Android_Res_Export/blob/master/README_zh.md ，配合这个插件来实现导出

### 8、导出png图片有背景

单独导出png图片，需要建组，然后对组进行切片。

## 六、团队协作
1、保持自己的symbols库和团队共享的symbols不重复。

2、文字经常会出问题，把同类型的文字也建成symbol，这样如果文字出现不居中，换字体的情况都只需要修改这个文字symbol就可以。

3、在更新sketch文档时，直接把自己做的源文件拖到公共sketch组件中时，会发生设置好的属性文字丢失，图标丢失等等情况。解决办法是复制page里的页面到新的公共组件中，就可以保留设置好的属性值。

4、在导出资源的时候，还是要针对每一个需要导出的元素设置切片范围，这样才可以导出需要的资源。

5、设置切片时，需要将切片和被切片的元素放在一个组里面，再关闭Export Group Contents Only,要不然就会出现带背景的情况。

6、导出小技巧。在用sketch measure导出插件时，将自己需要导出的page放在最上面，这样可以方便自己找到需要导出的页面。

Tip:导出后，如果发现有问题，不要使用导出覆盖而是把之前有问题的文件夹全部删掉，重新导出一次。

7、每次迭代组件后，都需要检查下，是不是链接到迭代的共享组件，如果没有，需要单独调整。如果有在自己的组件库中发现与新更新的组件重复，则说明重复组件有更新过，需要重新选择新组件（老组件填的样式会保留,没有嵌套的情况），替换后删掉自己组件库中的重复组件。

8、命名规范：模块名――页面名字――控件名――状态。建议自己新建的模块symbols命名不要跟基础底层symbols命名规范一致，这样做是为了方便自己区分自己的symbol和共享的symbol。

9、文件更新时，会出现symbol属性丢失的情况，如何解决文件合并的问题？

1）symbols有重复且有嵌套symbol，则直接删除被创建的symbols页面中的重复symbol

2）symbols有重复且没有嵌套symbol，则先选择更新的symbols，之后再删除被创建的symbols页面中的重复symbol

3）最终的目标是更新的symbols和复制页面后被创建的symbols页面中的symbol都是唯一的。

Tip:用automate-sketch.sketchplugin插件找到哪些页面在使用这个symbols。

## 七、其他资料
### 1、专制处女座 之 Sketch
主要介绍一些文字标注方面的小知识。
https://zhuanlan.zhihu.com/p/20594884
### 2、sketch有那些提升工作效率的实用技巧？
这些小技巧很实用，推荐一看。
https://www.zhihu.com/question/41362114

还不完善，欢迎补充，多谢！














