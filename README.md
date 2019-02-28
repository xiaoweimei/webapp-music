### 项目名称：老司机音乐电台
### 功能介绍
1. 实现响应式布局，增强视觉体验
2. 提供了音乐播放、暂停、下一曲功能
3. 提供音乐类型的选取等功能
4. 通过字体翻滚动画来展示歌词
### 技术细节
1. ajax获取后台数据
2. jQuery组装数据，将数据封装成DOM节点，渲染至页面
3. audio API的使用
4. 面向对象的方法来处理问题(组块的封装)
**遇到的问题**
1. footer下面字体图标绝对定位之后被footer所覆盖
**解决方案**
1. 逐行检查代码发现其父元素上设置了overflow:hidden造成溢出的元素不显示，改掉之后就好了
### 项目收获
1. 进一步对事件绑定有了清晰的认识
2. 可以初步进行响应式布局
3. 面向对象的练习可以使逻辑更加完整，代码更加规范
### 技术栈关键字: jQuery、CSS3、ajax、响应式、字体图标、浮动、定位、vh的使用、面向对象、媒体查询、事件代理


[效果预览地址](https://xiaoweimei.github.io/webapp-music/)
