# How-to-enter-the-sketch-workflow
如何从ps工作模式过渡到sketch工作流下，实现团队合作，提升整体效率
# sketch工作流遇到的问题以及如何解决
## 一、软件安装
由于sketch官方对软件的更新非常频繁，不建议去找破解版。还是建议去官网购买正版，对比PS，反正也不贵！
## 二、工作前期准备
### 1）插件选择
由于sketch本身的功能不多，开始工作前安装一些必备的插件是可以大幅度提高工作效率的。插件安装神器：Sketch Toolbox 下载地址  http://sketchtoolbox.com
我工作过程中常用的一些插件：![image](https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/12.png) 
<img src="https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/12.png" width="10"/>
资料：Sketch 有哪些插件值得推荐？
https://www.zhihu.com/question/27495264 根据自己的需要下载
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
 ![image](https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/%E9%92%A2%E7%AC%94%E5%B7%A5%E5%85%B7%E8%B7%AF%E5%BE%841.png) 
选择这个形状按Enter，然后点击close Path
 ![image](https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/%E9%92%A2%E7%AC%94%E5%B7%A5%E5%85%B7%E8%B7%AF%E5%BE%842.png)
### 7、带阴影图标，怎么确定导出切图后的大小？
把带有阴影的部分成组，然后选中组，按S，点一下这个组就会自动导出带有阴影部分的切图。如果手动切图，就需要把XY轴的偏移量补偿回去。



### 8、sketch如何解决0.1像素误差这种事情？
路径模式下，选择右上角的round to fluu pixels edges
![image](https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/0.1%E5%83%8F%E7%B4%A0%E8%AF%AF%E5%B7%AE%E9%97%AE%E9%A2%98.png) 
https://www.zhihu.com/question/35256192 
### 9、sketch设计UI中字体尺寸包含空白如何准确对齐？ 
默认字体苹方或者思源黑体的情况下，保留空白区域标注，因为程序那边开发写出来的代码，文本控件也是有空白区域的。
其他字体需要单独调整
https://www.zhihu.com/question/26758579
### 10、sketch如何复制样式？
Command + Option + C ( V )

## 五、切图，标注
### 1、Mac上用Sketch做的设计产出如何与还使用PC做前端开发的工程师（前端来切图）进行无缝对接？
用好切图标注软件，文件的设计，图层的划分，文本层等，交给开发那边一份zeplin或者Marketch生成的html标注页面
https://www.zhihu.com/question/36318532
### 2、界面设计中的文字还原问题 

https://zhuanlan.zhihu.com/p/21813824
### 3、用sketch切图时，导出的png会自动去掉透明区域，怎样保留透明区域的空间？ 
* 1） 建立切片区域Slice，并且和需要导出的内容放到一个组里面
 ![image](https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/%E5%88%87%E5%9B%BE%E4%BF%9D%E7%95%99%E9%80%8F%E6%98%8E%E5%8C%BA%E5%9F%9F.png)
* 2）勾选仅导出组内容
![image](https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/%E5%88%87%E5%9B%BE%E4%BF%9D%E7%95%99%E9%80%8F%E6%98%8E%E5%8C%BA%E5%9F%9F2.png)  
* 3）确认和去掉画布背景颜色选项中的Include Export，很多时候带底色，就是因为你默认选上了导出的时候带上了背景色( Include Export )
![image](https://github.com/ColourCloudSky/How-to-enter-the-sketch-workflow/blob/master/img/%E5%88%87%E5%9B%BE%E4%BF%9D%E7%95%99%E9%80%8F%E6%98%8E%E5%8C%BA%E5%9F%9F3.png)
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

## 六、团队协作
### 1、各位ui设计师使用sketch时，请问是如何完成设计师之间的协作的？
分功能类别来做，建立模板页面，但是不能太过于依赖symbol。
我的经验是一些小图标和公共的元素可以建立symbol 

## 七、其他资料
### 1、专制处女座 之 Sketch
主要介绍一些文字标注方面的小知识。
https://zhuanlan.zhihu.com/p/20594884
### 2、sketch有那些提升工作效率的实用技巧？
这些小技巧很实用，推荐一看。
https://www.zhihu.com/question/41362114

还不完善，欢迎补充，多谢！














