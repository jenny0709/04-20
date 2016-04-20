# 颜色和透明度

> css中颜色表示方式: 

- rgb(0-255,0-255,0-255)  css2
- #000000  十六进制颜色   css2
- 关键词 red green blue purple pink   css2
- rgba(0-255,0-255,0-255,0-1) 可以让文字颜色、背景颜色变成透明  css3

> css3中表示透明度:

- background-color:transparent;
- opacity:0 -1;
- filter:Alpha(opacity=0-100); IE滤镜

> 浏览器前缀:

1. 火狐浏览器  -moz-
2. IE          -ms-
3. chrome      -webkit-
4. 欧鹏        -o-

> 模糊效果:

-webkit-filter:blur(10px);

> 灰度效果:

-webkit-filter:grayscale(0 | 1);
- 1 :灰色
- 0 :正常