# iconfont
1. [iconfont-阿里巴巴矢量图标库](http://www.iconfont.cn/)
2. 选好所需要的小图标后加入购物车，添加至项目
3. 点击生成代码,复制粘贴到css代码中（在线编译器）；或下载压缩包至本地，打开文件iconfont.css，复制全部代码粘贴至css代码中（本地）
```
@font-face {
  font-family: 'iconfont';  /* project id 694897 */
  src: url('//at.alicdn.com/t/font_694897_q8gyl6kbgmsra4i.eot');
  src: url('//at.alicdn.com/t/font_694897_q8gyl6kbgmsra4i.eot?#iefix') format('embedded-opentype'),
  url('//at.alicdn.com/t/font_694897_q8gyl6kbgmsra4i.woff') format('woff'),
  url('//at.alicdn.com/t/font_694897_q8gyl6kbgmsra4i.ttf') format('truetype'),
  url('//at.alicdn.com/t/font_694897_q8gyl6kbgmsra4i.svg#iconfont') format('svg');
}
```
4. 给icon图标所在的标签添加```class="iconfont"```属性，并添加下面的代码到css代码中
```
.iconfont{
    font-family: "iconfont" !important;
    font-style: normal;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    font-size:  ;
    color:  ;
}
```
5. 将图标代码（&#xe600）改写成（\e600）,添加至css代码中
```
.iconfont:before { 
  content: "\e600";
}
```
6. 
```
.iconfont:hover {
  color: #D81E06;
}
```
