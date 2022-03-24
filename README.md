# 我的web页面说明
- **样式的解释**
- **排版欠佳**
- **部分内容解释来自网络**
## 页面所使用的的样式属性有哪些：
- CSS
- `background 背景属性`
- background-color 背景颜色
  - background-color: #fffce9;
- background-image 背景图片
  - background-image: url(图片路径);
- background-repeat 背景平铺方式
  - background-repeat: no-repeat; 
    - repeat	默认。背景图像将在垂直方向和水平方向重复。
    - repeat-x	背景图像将在水平方向重复。
    - repeat-y	背景图像将在垂直方向重复。
    - no-repeat	背景图像将仅显示一次。
    - inherit	规定应该从父元素继承 background-repeat 属性的设置。
- background-position 背景位置
  - background-position: right top;
    - top 顶部
    - left 左边
    - right 右边
    - bottom 底部
    - center 居中
- background-attachment 背景滚动
  - background-attachment: fixed;
    - scroll	背景图片随着页面的滚动而滚动，这是默认的。
    - fixed	背景图片不会随着页面的滚动而滚动。
    - local	背景图片会随着元素内容的滚动而滚动。
    - initial	设置该属性的默认值。 
    - inherit	指定 background-attachment 的设置应该从父元素继承。
- `font字体属性`
- font-size 字体大小
  - font-size: 16px;
- font-style 字体样式
  - font-style: italic；
    - normal	默认值 标准的字体样式。
    - italic	斜体的字体样式。
    - oblique	倾斜的字体样式。
    - inherit	规定应该从父元素继承字体样式。
- font-weight 字体加粗
  - font-weight: bold;
    - normal	默认值。定义标准的字符。
    - bold	定义粗体字符。
    - bolder	定义更粗的字符。
    - lighter	定义更细的字符。
    - 100 - 900 定义由粗到细的字符。400 等同于 normal，而 700 等同于 bold。
    - inherit	规定应该从父元素继承字体的粗细。
- text-indent 首行缩进
  - text-indent: 2em;
- line-height 行高
  - line-height: 40px;
    - normal	默认。设置合理的行间距。
    - number	设置数字，此数字会与当前的字体尺寸相乘来设置行间距。
    - length	设置固定的行间距。
    - %	基于当前字体尺寸的百分比行间距。
    - inherit	规定应该从父元素继承 line-height 属性的值。
- color 文本颜色
  - color: #f00000;
    - #fff 三位十六进制
    - #f00000 六位十六进制
    - red 颜色名字
    - inherit	规定应该从父元素继承颜色。
- text-decoration 文本修饰
  - text-decoration: underline;
    - none	默认。定义标准的文本。
    - underline	定义文本下的一条线。
    - overline	定义文本上的一条线。
    - line-through	定义穿过文本下的一条线。
    - blink	定义闪烁的文本。
    - inherit	规定应该从父元素继承 text-decoration 属性的值。
- text-align 文字对齐方式
  - text-align: center;
    - left	把文本排列到左边。默认值：由浏览器决定。
    - right	把文本排列到右边。
    - center	把文本排列到中间。
    - justify	实现两端对齐文本效果。
    - inherit	规定应该从父元素继承 text-align 属性的值。
