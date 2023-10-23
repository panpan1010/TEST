# CSS基础认知 

## CSS的介绍

CSS:层叠样式表

CSS作用：给页面中的HTML标签设置样式

## CSS语法规则

- css写在style标签中，style标签一般写在head标签里面，title标签下面

![image-20231017200918392](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017200918392.png)

 注：1.style里写的都是CSS     2.选择器{css属性}          3.选择器：查找标签

- 字变大 px像素：front-size:30px
- 背景颜色： background-color

## 示例：



![image-20231017202503066](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017202503066.png)

![image-20231017202523159](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017202523159.png)

# CSS引入方式

## 内嵌式

CSS写在style标签中

提示：style标签虽然可以写在页面任意位置，但是通常约定写在**head**标签中

## 外联式

CSS写在一个单独的.css文件中

提示：需要通过link标签在网页中引入

示例：

![image-20231017203634905](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017203634905.png)

在.css文件中直接写代码即可

## 行内式

CSS写在标签的style属性中

提示：基础班不推荐使用，之后会配合js使用

![image-20231017204741514](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017204741514.png)

 ## 三种引入方式的特点区别

![image-20231017205012565](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017205012565.png)

# 选择器-标签

  ## 结构：

标签名{css属性名：属性值；}

## 作用

通过标签名，找到页面中所有这类标签，设置样式

## 注意点

- 标签选择器选择的是一类标签，而不是单独某一个
- 标签选择器无论嵌套关系有多深，都能找到对应的标签

![image-20231017210150964](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017210150964.png)

# 选择器-类

## 结构

.类名{css属性名：属性值；}

## 作用

通过类名，找到页面中所有的带有这个类名的标签，设置样式

## 注意点

![image-20231017211423687](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017211423687.png)

示例：

![image-20231017211935751](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017211935751.png)

# 选择器-id

![image-20231017213131445](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017213131445.png)

![image-20231017213204238](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017213204238.png)

# 选择器-通配符

![image-20231017213745313](C:\Users\86186\AppData\Roaming\Typora\typora-user-images\image-20231017213745313.png)