# @是什么
import alias通常需要通过@来实现。

## import alias 如何使用？
TS/JS可以通过<font color=red>@/目录名</font>引入文件;
```js
import x form '@/components/Test.vue'
```
CSS/SASS可以通过<font color=red>~@/目录名</font>引入文件。
```css
@import '~@/assets/styles/Test.css';

body{
    background:$red; 
    /* $red是Test.css中声明的一个变量*/
}

$red:#f00 /*Test.css的内容*/
```


### 为什么要使用import alias？
这样就不用去计算相对路径了。
