# 前端
开始做计划的时候 以为会很轻松的完成，结果这些天看书加练习。深深的感到自己的不足，下面总结一下自己这些天的问题。
1.对dom中节点的获取：
①对于element类型的节点其nodeType的值为1.
② parentNode的值可能是document或element
③它的子节点可能是 Element、Text、Comment、ProcessingInstruction、CDATASection 或者 EntityReference

2.html元素需要注意的方面：
①title有关元素的附加说明信息，一般通过工具提示条显示出来
②lang元素内容的语言代码，很少使用
③className与元素的class特性对应

3.css样式的分类：
①内联式 <p style="color:green;font-size:12px">这里文字是绿色。</p>
②嵌入式 在<style>标签中编写
③外部式 把css写在一个单独的文件中用link标签去调用
④三种方法的优先级：  内联式 > 嵌入式 > 外部式
注意：内联元素： （1）、和其他元素都在一行上；（2）、元素的高度、宽度、行高及顶部和底部边距不可设置；（3）、元素的宽度就是它包含的文字或图片的宽度，不可改变。<br>

4.css布局模型 
 元素有三种布局模型：
    （1）、流动模型
        网页在默认状态下的 HTML 网页元素都是根据流动模型来分布网页内容的
        第一点，块状元素都会在所处的包含元素内自上而下按顺序垂直延伸分布，因为在默认状态下，块状元素的宽度都为100%
        第二点，在流动模型下，内联元素都会在所处的包含元素内从左到右水平分布显示
    （2）、浮动模型
        现在我们想让两个块状元素并排显示
        任何元素在默认情况下是不能浮动的，但可以用CSS定义为浮动，如div、p、table、img等元素都可以被定义为浮动
        举例：
            #div1{float:left;}
            #div2{float:right;}
    （3）、层模型（定位相关）

 5.最近四天阅读的博客：

    ① 讲述css规范和标准
    
    
     http://www.shejidaren.com/css-written-specifications.html
    ②css选择器权重和属性继承
     http://www.w3cfuns.com/notes/18338/c656d5027d5d0684789849d5a6f3e57a
    ③内联对象和块对象
     http://www.w3cfuns.com/notes/18165/c08efbe3df40752973d3cc2dab79f9e3
    ④css样式随笔总结
     http://www.w3cfuns.com/notes/18617/28208abf120bdbbd1cc8db0717a059c7<br>
6.还原psd文件。









