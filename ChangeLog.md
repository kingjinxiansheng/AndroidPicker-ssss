### v1.5.5 - 2017.09.01
代码优化，新增一些设置方法；
### v1.5.4 - 2017.08.19
修复时间选择器bug；
联动选择器支持设置宽度填充;
### v1.5.3 - 2017.07.01
修复默认无法选中第一项的问题；
新增日期时间选择器联动时是否重置下一级的索引的控制方法;
修复日期选择器setSelectedItem传值错误可能导致的奔溃问题;
新增多项选择器；
### v1.5.2 - 2017.05.14
有童鞋反应动画太慢，移除选择器默认的动画；
DoublePicker支持设置前缀及后缀标签;
修复联动选择器不滑动（使用默认项）就确定时的奔溃问题；
修复setXXRangeStart()及setXXRangeEnd()二者调用顺序颠倒出现的问题；
### v1.5.1 - 2017.05.03
日期时间选择器支持设置各项平分布局;
顶部按钮文字颜色默认调整为青蓝风格;
修复日期时间选择联动适时取值不对问题；
支持设置选中项的背景色及透明度；
增加港澳台的县级城市数据；
添加双项选择器，选择两项，数据不联动;
### v1.5.0 - 2017.05.01
基于View重构WheelView；
联动选择器支持直接传入对象；
动画默认为500毫秒，应该不会太慢了；
### ~~v1.4.6 - 2017.04.10~~
弹窗内部部分代码重构；
使用透明渐变位移动画，缓解初始化时默认选中项显示跳动问题；
日期时间选择联动时重置联动项的索引为0；
### ~~v1.4.5 - 2017.03.19~~
解决选择器部分选项概率性不显示问题，感谢亮亮同学；
### ~~v1.4.4 - 2017.03.8~~
解决滑动选项闪烁问题；修复已知的数组越界异常问题；
### ~~v1.4.3 - 2017.01.16~~
解决默认选项选中失效问题；
### ~~v1.4.2 - 2017.01.09~~
滑轮选择器默认禁用循环滚动；
日期时间选择器宽度兼容480x800；
demo的地址选择器重构，方便回调；
### ~~v1.4.1 - 2017.01.08~~
修复选择器在Android4.X版本上奔溃问题；
改进文件目录选择器的路径指示效果；
### ~~v1.4.0 - 2017.01.07~~
重构WheelView，大批量数据时滑动性能显著提升；
改进颜色选择器的颜色选择预览效果；
滑轮选择器可设置阴影效果；
### ~~v1.3.5 - 2017.01.04~~
选择器引用的图片改成字节数组形式;
解决默认主题设置为Material时顶部按钮内边距过宽问题;
demo添加沉浸式状态栏功能
### ~~v1.3.4 - 2017.01.01~~
重构日期时间选择器，默认选中当前日期时间;
支持设置顶部的左右边距;
优化多级选择器的数据联动；
支持将库打包为纯jar包，通过jar依赖;
### ~~v1.3.3 - 2016.12.21~~
修复日期选择器月份范围设置可能无效的bug;
支持设置顶部按钮按下状态的文字颜色;
选择器条目默认显示由3条改为5条，并修改条目文字的内边距；
### ~~v1.3.2 - 2016.12.19~~
支持设置选中项分割线的宽比例、透明度、粗度；
修复小数选择器设置默认选择项可能无效的bug；
添加中国大陆车牌号码选择器；
### ~~v1.3.1 - 2016.12.17~~
对1.2.*版本作兼容处理。
### ~~v1.3.0 - 2016.12.15~~
支持设置选择器主体背景颜色；
所有选择器支持滑动实时监听;
所有选择器支持内嵌到其他视图容器;
重构单项选择器，数字选择器支持小数；
### ~~v1.2.4 - 2016.11.23~~
修复默认选中第一项时颜色不高亮问题；
修复联动选择器数组越界问题；
多级联动选择器支持设置各列比例；
时期及时间选择器内部逻辑修改；
### ~~v1.2.3 - 2016.10.13~~
修复日期选择器中当开始年份和结束年份相同时的Bug；
修复年月日时分选择器的设置默认值时分没有补零的Bug；   
支持所有选择器顶部高度及字号的设置；   
修复日期选择器选中项显示有误问题，感谢@msdx；   
### ~~v1.2.2 - 2016.09.01~~
日期选择器支持年份正序和逆序；   
时间选择器可以限定时分范围；   
选择器可指定弹框显示位置，如居中；   
日期选择器可以限定年月日范围；   
修复几个已知的bug；   
### ~~v1.2.1 - 2016.07.23~~
地址选择器增加获取城市编码，感谢@weishd；   
修改注释，优化部分代码，修复一个已知的bug；   
### ~~v1.1.3 - 2016.06.14~~
添加日期时间选择器，感谢@dongzhaoqi；   
### ~~v1.1.2 - 2016.05.06~~
添加二三级联动选择器；   
文件选择器布局调整；   
### ~~v1.1.1 - 2016.04.23~~
地址选择器支持只选择省和市、不能混淆某些类，感谢@Wastrel及@lutas2000；   
### ~~v1.1.0 - 2016.01.29~~
添加注解约束，如“setOffset()”只能是1至4；   
所有枚举类改为常量来表示，据说这样可以节约内存；   
支持自定义选择器的顶部及底部的视图；   
支持使用第三方动画库来实现窗口动画；   
### ~~v1.0.3 - 2016.01.19~~
日期时间、地址、单项、数字等选择器支持伪循环滚动。   
### ~~v1.0.2 - 2016.01.15~~
年或月变动时，保持之前选择的日不动：如果之前选择的日是之前年月的最大日，则日自动为该年月的最大日。   
### ~~v1.0.1 - 2016.01.14~~
精简文件选择器的数据适配器；   
添加选择器顶部确定、取消按钮所在容器的背景色设置。   
### ~~v1.0.0 - 2016.01.13~~
发布到jcenter，支持远程maven依赖。   