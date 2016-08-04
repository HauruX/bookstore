# bookstore 前端页面

之前做过的一个书城的项目的前端界面，基本自己手写。

以现在来看，项目代码本身有很多缺陷，仅放置上来以供参考

### 对于个人的意义
- 第一次较大规模实践前端基础
- 手动调节各种位置，对盒模式有较强的实践
- 较为大量的使用`float`作为布局的方式，意识到`float`带来的父容器高度塌陷等问题。当时通过指定父元素高度避免这个问题。
- 意识到js文件放在顶部会导致读取不到`DOM`元素问题
- 在借鉴其它网站样式时，发现将图标合并为一张图片，意识到效率问题。后来知道这是通过sass、compass自动生成的雪碧图。

### 部分已知的弊端
- 缺乏整个工程统一设计的思想，css仅在每个页面单独使用，割裂性高，并且带来命名冲突问题。应对整个网站进行统一设计，运用层叠样式的思想。
- css、js文件没有较好的整理为一个文件
- 应当css文件引用放在文档顶部，js引用放在文档底部
- 图标可以统一合并成一张图片