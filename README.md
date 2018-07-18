

# Eclipse | Formatter & CodeTemplates 格式化和代码注释

团队里面最好能统一风格，这样在看别人代码的时候就比较清晰。

## CodeTemplates

> 写注释比不写好    
> 注释的格式其实也有模板的

- 没有用注释模板 
![image](http://paz1myrij.bkt.clouddn.com/20180718165007.png)

- 使用注释模板 
![image](http://paz1myrij.bkt.clouddn.com/20180718165620.png)

` /** */ `  一般用在`Method`上面    
` // `  单行注册用在代码的上面， 也有人用在代码的后面，但是个人不建议    


## Formatter

> 关于代码格式化目前只碰到大括号是否独立一行的情况        
> 一下格式化是以大括号独立一行为标准    

- 格式化前 
![image](http://paz1myrij.bkt.clouddn.com/20180718165620.png)

- 格式化后
![image](http://paz1myrij.bkt.clouddn.com/20180718170025.png)

格式化后代码阅读起来比较清晰   

## Eclipse 配置`Formatter` 

在Eclipse工具栏选择 `Preferences` -> `Java` -> `Code Style` -> `Formatter`

![image](http://paz1myrij.bkt.clouddn.com/20180718171438.png)

- 选择 `Edit...` 或者 ‘New...’

![image](http://paz1myrij.bkt.clouddn.com/20180718171618.png)

### `Indentation` 缩进

我个人习惯将`Tab policy` 选择为 `Spaces only`，因为可以保证在不同的IDE中代码的兼容性比较好   
在使用Tab的时候实际上是空了4格    

### `Brace positions` 配置大括号

- `Same line` 在同一行
- `Next line` 换行（大括号独立一行）
- `Next line indented` 换行并缩进
- `Next line on wrap` 不知道

**其他的配置没有研究过，有兴趣可以自己去研究**   
或者参考[玩转Eclipse — 自动代码规范化 - CSDN博客](https://blog.csdn.net/jmyue/article/details/11060003)

或者直接导入我的`Formatter `模板

## Eclipse 配置`CodeTemplate`

在Eclipse工具栏选择  `Preferences` -> `Java` -> `Code Style` -> `Code Templates`    
![](http://paz1myrij.bkt.clouddn.com/20180718181437.png)    
 
在`Comments` 中 配置各个类型的注释格式

选中类型后选择`Edit...`开始编辑
![image](http://paz1myrij.bkt.clouddn.com/20180718182305.png)
`Insert Variable...` 可以选择各种参数    

配置好后使用方式是在`method`上 输入`/** + 回车` 就会显示配置的注释    

也可以下载我的`CodeTemplate` 模板导入  
如果使用我的模板请将`@author` 改成你自己的名字



