
flexbox 弹性盒子模型

1、容器属性

下面这两个属性，可以对比理解。
align-content: flex-start | flex-end | center | space-between | space-around | stretch;
justify-content: flex-start | flex-end | center | space-between | space-around;

子元素排列方向
flex-direction：row | row-reverse | column | column-reverse

子元素超出父容器时是否换行
flex-wrap：nowrap | wrap | wrap-reverse

复合属性，简写 flex-direction,flex-wrap
flex-flow：[ flex-direction ] || [ flex-wrap ]

子元素在侧轴（纵轴）方向上的对齐方式
align-items：flex-start | flex-end | center | baseline | stretch

2、项目属性

order属性定义项目的排列顺序。数值越小，排列越靠前，默认为0

align-self属性允许单个项目有与其他项目不一样的对齐方式，可覆盖align-items属性。默认值为auto，表示继承父元素的align-items属性，如果没有父元素，则等同于stretch。
align-self: auto | flex-start | flex-end | center | baseline | stretch;


引用

http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html

https://css-tricks.com/snippets/css/a-guide-to-flexbox/

https://scotch.io/tutorials/a-visual-guide-to-css3-flexbox-properties


