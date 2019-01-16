## 前言
>感觉现在的面试越来越难了，问得也越来越深，但是说实话很不实用，有应试的感觉。面试问各种原理，各种算法，实际用到的有多少？面试造核弹，工作拧螺丝。很多干了多年（5+）的真正资深反而在面试表现上还不如做了几周面试准备的应届生，难道这些应届生能力上比这些熟手强？或者有什么根据说他们的“潜力”强？真正入职了之后面对的是一个迭代接一个迭代，一个产品接一个产品，为了生活为了房子为了贷款不停的在工作，技术的沉淀又能有多少？又能有多少时间能给你去实践一个个新get的知识点？
>
>作为9年的安卓开发，刚毕业就进入正规外企开始安卓开发，一步一步从初级到中级到高级到现在的架构，app leader，期间也因为公司业务快速学习IOS,web vue等，各种新技术也保持着接触，到现在也没有止步不前。但这些并不代表我现在就已经掌握了所有这些曾经接触过的技术。**人的忘性是无可避免的，没有谁会一直记得不经常使用到的东西，但对一个开发来说，真正宝贵的应该是学习新技术快速使用的经验，面对新业务能快速深入理解并能给出风险和边际连带影响的提示，解决问题的思路、态度和与团队完美配合的工作方法。**
>
>但是现在的社会肤浅的，是喜欢人云亦云的，是崇尚浮夸的。为了适应这个现实，我从而有了这个app的构思，希望能帮助到有面试需要的同学。
***


目录

[TOC]

## 结构构思
不搞什么花里花哨的东西，全是最常用的干活，讲究的就是精准实用，并不是要大家都会所有的技能，面试之前能熟悉就好，能背诵更好，应试之用。

### 页签形式的主界面
列表类型包含
* java基础
* android基础
* 算法
* 热更新/插件化/组件化
* 常用设计模式
* 架构模式
* java源码解读
* android源码解读
* 常用库原理及对比，rxjava等
* rn,weex,flutter,cordova
* 流行的效果式样

每一个页签用懒加载形式加载,按最热的形式排序
每一个item点开后都用fragment展现
自用先用本地json读取，以后如果想收费了再搞接口读取。或者搞本地json文件，读取每个页签所需要用到的数据。这样就可以不限定安卓了，其他所有的内容都可以让用户自己编辑定制

###  具体内容
#### java基础
#### android基础
#### 算法
#### 热更新/插件化/组件化
#### 常用设计模式
#### 架构模式
#### java源码解读
#### android源码解读
#### 常用库原理及对比，rxjava等
#### rn,weex,flutter,cordova
#### 流行的效果式样

## 开源协议

```
MIT License

Copyright (c) 2018 张沅龙

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
