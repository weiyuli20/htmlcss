##  1_
双标签 
``` <div></div> ```  中间可以放入内容

单标签 ```<input/>  <img/> ```

```<intput type="text"/>  ```type指定输入框类型

div 和css 可以实现绝大数的布局

margin 是盒子的外边框

padding 是盒子的内边框

margin-top margin-bottom margin-left margin-right  
快捷调出方式 mt mb ml mr

## 2_
```width:98%; ``` 宽度指定为百分比，宽度可以随着创库宽度变化而变化

盒子的高度等于实际高度+内边距

```padding-top: 30px;  box-sizing: border-box;```
padding和box-sizing同时出现不会改变盒子的原始高度

样式 ```display: flex;``` 可以实现盒子内部元素横着排列

```text-align: center; ``` 内容水平居中

```line-height: 52px; ``` line-heifht 行高和盒子高度一致时，内容垂直居中


```cursor: pointer;``` 点击时手指效果

```user-select: none;```  禁止选中，内容不能选中复制

```margin: 8px auto;``` 第一个值上下，auto 左右自适应

```justify-content: space-between;``` div里的元素自动平分空间

```align-items: center;``` 元素垂直居中

```text-decoration: line-through;``` 删除线

```opacity: 0.5;``` 透明度

## 3_js
js的简单语法，js代码写在html的script标签里
```
<script>
        let a = 1
        let arr = [1,2,3]
        let flag = true
        let obj = {
            name: 'zhangsan',
            age: 18
        }

        function test() {
            console.log('test')
        }
        console.log(a,arr,flag,obj)
        for(let i = 0; i < arr.length; i++){
            console.log(arr[i])
        }

        obj.name = 'lisi'
        console.log(obj)
        test()
    </script>
```


