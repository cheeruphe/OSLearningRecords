2023 年春夏季开源操作系统训练营启动&报名交流会

 

会议时间：2023/03/25 11:00-12:00（周六上午11点）

 

\#腾讯会议：231-190-126

会议密码：0325

 

请大家添加到自己的腾讯会议中，会议开始前3分钟会有消息提醒。

 

附训练营介绍：https://github.com/LearningOS/ 

训练营报名表链接：http://chyyyuuu.mikecrm.com/2zxG8dp

 

 

第十届开源操作系统年度技术会议（OS2ATC）

议程安排：

https://www.bagevent.com/event/7951632/p/513655

 

视频直播链接：

https://live.csdn.net/room/Hansen666666/wIIp8dGq

 

现场图片直播：

https://live.photoplus.cn/live/39662692

 

 

# 2023.04.01



## 1  配置Windows本地rustlings开发环境

### 1.1 一文吃透 VS Code+Git 操作（vs code中git的相关配置与使用）



参考链接：https://blog.csdn.net/weixin_53072519/article/details/123914289

 

 

D:\Program Files\Git

  ![image](https://user-images.githubusercontent.com/84122239/230711944-4dcad199-49be-45ff-9fed-c31e4a88a5db.png)


这个地方是空密码
![image](https://user-images.githubusercontent.com/84122239/230711995-3dda29a9-0364-46dc-9b7a-beda62b1ceeb.png)

 


 

很奇怪，刚开始试了一次不成功，什么都没改，又试了一次才成功。

 

 

Vs code中配置git：

https://zhuanlan.zhihu.com/p/482203469

 ![image](https://user-images.githubusercontent.com/84122239/230712009-13678cf7-f43e-4eaf-9335-d834a93f52fb.png)


 

 

 ![image](https://user-images.githubusercontent.com/84122239/230712021-3e5526b6-6811-4aa4-961e-92f1df1f9e96.png)

![image](https://user-images.githubusercontent.com/84122239/230712025-6d10cd78-d46a-48e1-b335-f95c9f2d9fd2.png)
![image](https://user-images.githubusercontent.com/84122239/230712042-4134898b-a055-4d71-9ae4-072337fc056a.png)



最后把这个多余的仓库给删了。

 

需要用的是learningOS里面的链接。

https://github.com/LearningOS/rust-rustlings-cheeruphe

 

SSH地址：

[git@github.com:LearningOS/rust-rustlings-cheeruphe.git](mailto:git@github.com:LearningOS/rust-rustlings-cheeruphe.git)

 

 

 

 

按照官方网站上的步骤，

![image](https://user-images.githubusercontent.com/84122239/230712094-7b9a4fde-dbb9-4f49-a7bd-cf7c8700a537.png)

 

安装rustling教程：

https://zhuanlan.zhihu.com/p/577099148

Windows比较复杂一点

 

解决连接失败的问题：

https://blog.csdn.net/sichen1900/article/details/121909009

 
![image](https://user-images.githubusercontent.com/84122239/230712114-61fe8bae-f024-4c32-96ca-42667474a934.png)
![image](https://user-images.githubusercontent.com/84122239/230712124-3ef49465-0e99-4697-9fa9-5d969ca44df2.png)
![image](https://user-images.githubusercontent.com/84122239/230712129-daefccad-a50a-4b23-ab6b-19c0a4c62c1b.png)

![image](https://user-images.githubusercontent.com/84122239/230712136-101cd119-ab03-40b8-b61c-541cede2b40e.png)



一直超时，去掉vpn之后立刻就能用了。。。

![image](https://user-images.githubusercontent.com/84122239/230712144-bed06ce3-4919-498e-803a-df3d06e0e297.png)
其实是已经安装好了，但是一直没有重启VSCode，重启之后就能用了。不重启没办法用。

 

试了一下还是不行。

 

https://blog.csdn.net/qq_40901613/article/details/115374699

 

练习指导

https://blog.sworld.club/

 

Rust官方教程：

https://www.runoob.com/rust/rust-setup.html

 

 

 

**Visual Studio和Visual Studio Code(VSCode)的区别及如何选择-前端开发自学笔记(7)**

**之前没有安装visual studio环境？？**

![image](https://user-images.githubusercontent.com/84122239/230712169-7712e87c-7088-47dc-b962-227b69b7f3d6.png)
![image](https://user-images.githubusercontent.com/84122239/230712177-229bb399-54f4-4db9-b7f3-7d4715f14911.png)
CodeLLDB安装失败，需要手动安装。

https://www.cnblogs.com/yinyunpan/p/16862583.html

![image](https://user-images.githubusercontent.com/84122239/230712182-ccbbe453-0a6b-45d8-8510-6372a6e19e42.png)
手动安装成功，然后就能在输出地方不报错了。

![image](https://user-images.githubusercontent.com/84122239/230712192-0d6c3997-79dc-4f8a-8a1d-53e929e0b893.png)
 

Rustling watch还是不能用

 

![image](https://user-images.githubusercontent.com/84122239/230712204-57df3787-862f-4b82-8d80-ca23f8e75aaa.png)
 



 

![image](https://user-images.githubusercontent.com/84122239/230712227-c2a051e1-c34f-4c0b-81c9-7ace950237bf.png)
重新安装了visual studio在developer powershell for vs 里面安装rustlings

![image](https://user-images.githubusercontent.com/84122239/230712230-932631ea-57d8-4e7b-b84b-e7c951b97429.png)
应该是安装成果了，重新开了vpn

 

![image](https://user-images.githubusercontent.com/84122239/230712244-e0fa50b2-9d1c-4528-87c9-2d70e3170c5e.png)
 ![image](https://user-images.githubusercontent.com/84122239/230712252-a0b77dd9-b104-4463-a7fb-042da9322eb3.png)

 环境搭建完成

 

 

# 2023.04.02



根据课程提供的学习资源开始学习rust基本语法：

Rust 程序设计语言 简体中文版

学习资源：

https://kaisery.github.io/trpl-zh-cn/

 

 

Rustling如何使用调试：

https://www.163.com/dy/article/HPROV4EE0511CPOJ.html

![image](https://user-images.githubusercontent.com/84122239/230712310-254a316d-a99c-42d7-bb76-d0fc245e1d29.png)
![image](https://user-images.githubusercontent.com/84122239/230712309-b3a18bfe-8d4a-41f3-a078-37d040fe1cfc.png)
终于明白了

Ruslings的用法

 

微信群里面的

大家好~后面会有3次Rustlings答疑课程，为了尽可能给大家提供优质的讲解，希望大家可以把自己在刷Rustlings过程中遇到的问题填写到下面的表格中。在3次答疑过程中，我们会优先选择得票数高的问题进行答疑。

 

【腾讯文档】Rustlings问题列表（2023春季）

https://docs.qq.com/sheet/DVlJqVVh6Z1h3ZHR2?tab=BB08J2

 

##  3 常见的编程概念

### 3.1 **变量不可变**

在尝试改变预设为不可变的值时，产生编译时错误是很重要的，因为这种情况可能导致 bug。如果一部分代码假设一个值永远也不会改变，而另一部分代码改变了这个值，第一部分代码就有可能以不可预料的方式运行。不得不承认这种 bug 的起因难以跟踪，尤其是第二部分代码只是 有时 会改变值。

（）

#### 常量

首先，不允许对常量使用 mut。常量不光默认不可变，它总是不可变。声明常量使用 const 关键字而不是 let，并且 必须 注明值的类型。在下一部分，“数据类型” 中会介绍类型和类型注解，现在无需关心这些细节，记住总是标注类型即可。

常量可以在任何作用域中声明，包括全局作用域，这在一个值需要被很多部分的代码用到时很有用。

最后一个区别是，常量只能被设置为常量表达式，而不可以是其他任何只能在运行时计算出的值。

 

####  隐藏

我们可以定义一个与之前变量同名的新变量。Rustacean 们称之为第一个变量被第二个 隐藏（Shadowing） 了，这意味着当您使用变量的名称时，编译器将看到第二个变量。实际上，第二个变量“遮蔽”了第一个变量，此时任何使用该变量名的行为中都会视为是在使用第二个变量，直到第二个变量自己也被隐藏或第二个变量的作用域结束。可以用相同变量名称来隐藏一个变量，以及重复使用 let 关键字来多次隐藏。

![image](https://user-images.githubusercontent.com/84122239/230712322-344c7f54-551b-43fc-8ebf-8d27f28beead.png)
 

隐藏与将变量标记为 mut 是有区别的。当不小心尝试对变量重新赋值时，如果没有使用 let 关键字，就会导致编译时错误。通过使用 let，我们可以用这个值进行一些计算，不过计算完之后变量仍然是不可变的。

 

mut 与隐藏的另一个区别是，当再次使用 let 时，实际上创建了一个新变量，我们可以改变值的类型，并且复用这个名字。例如，假设程序请求用户输入空格字符来说明希望在文本之间显示多少个空格，接下来我们想将输入存储成数字（多少个空格）：

![image](https://user-images.githubusercontent.com/84122239/230712333-eeb592b3-1edf-4a56-9a87-8b162278ab41.png)
这个mut和隐藏的区别感觉还是挺有意思的，不过这个增加不同的名字，与直接复用之前的名字，相比底层内存占用一样吗？如果都要新开辟空间存这个新变量，那为什么要复用之前的名字呢？

 

### 3.2 数据类型

在 Rust 中，每一个值都属于某一个 数据类型（data type），这告诉 Rust 它被指定为何种数据，以便明确数据处理方式。我们将看到两类数据类型子集：标量（scalar）和复合（compound）。

记住，Rust 是 静态类型（statically typed）语言，也就是说在编译时就必须知道所有变量的类型。根据值及其使用方式，编译器通常可以推断出我们想要用的类型。当多种类型均有可能时，比如第二章的 “比较猜测的数字和秘密数字” 使用 parse 将 String 转换为数字时，必须增加类型注解，像这样：

let guess: u32 = "42".parse().expect("Not a number!");

***\*标量类型：\****

标量（scalar）类型代表一个单独的值。Rust 有四种基本的标量类型：***\*整型、浮点型、布尔类型和字符类型\****。你可能在其他语言中见过它们。让我们深入了解它们在 Rust 中是如何工作的。

####  整型

![image](https://user-images.githubusercontent.com/84122239/230712344-e3062cc7-ec05-451b-94c6-6023439a77e4.png)
 

有符号 和 无符号 代表数字能否为负值，换句话说，这个数字是否有可能是负数（有符号数），或者永远为正而不需要符号（无符号数）。有符号数以补码形式（two’s complement representation） 存储。

![image](https://user-images.githubusercontent.com/84122239/230712350-fc069600-0b23-49be-8c5f-bb7ecc6fd3c6.png)
另外，isize 和 usize 类型依赖运行程序的计算机架构：64 位架构上它们是 64 位的，32 位架构上它们是 32 位的。

那么该使用哪种类型的数字呢？如果拿不定主意，Rust 的默认类型通常是个不错的起点，数字类型默认是i32。isize或usize主要作为某些集合的索引。

#### 浮点型

Rust 也有两个原生的浮点数（floating-point numbers）类型，它们是带小数点的数字。Rust 的浮点数类型是f32和f64，分别占 32 位和 64 位***\*。默认类型是f64，\****因为在现代 CPU 中，它与f32速度几乎一样，不过精度更高。所有的浮点型都是有符号的。

***\*数值运算：\****

Rust 中的所有数字类型都支持基本数学运算：加法、减法、乘法、除法和取余。***\*整数除法会向下舍入到最接近的整数。\****下面的代码展示了如何在 let 语句中使用它们：

文件名：src/main.rs

 

fn main() {

  // addition

  let sum = 5 + 10;

 

  // subtraction

  let difference = 95.5 - 4.3;

 

  // multiplication

  let product = 4 * 30;

 

  // division

  let quotient = 56.7 / 32.2;

  let truncated = -5 / 3; // 结果为 -1

 

  // remainder

  let remainder = 43 % 5;

}

#### **布尔型**

正如其他大部分编程语言一样，Rust 中的布尔类型有两个可能的值：true 和 false。Rust 中的布尔类型使用 bool 表示。例如：

#### **字符类型**

![image](https://user-images.githubusercontent.com/84122239/230712356-d406f9dd-18f7-44e8-a23e-163d406aca83.png)
这个里面提到了字符类型的范围更广。

***\*复合类型\****

复合类型（Compound types）可以将多个值组合成一个类型。Rust 有两个原生的复合类型：***\*元组（tuple）和数组（array）\****。

#### **元组类型**

元组是***\*一个将多个其他类型的值组合进一个复合类型\****的主要方式。***\*元组长度固定：一旦声明，其长度不会增大或缩小。\****

我们使用包含在圆括号中的逗号分隔的值列表来创建一个元组。元组中的每一个位置都有一个类型，而且这些不同值的类型也不必是相同的。

![image](https://user-images.githubusercontent.com/84122239/230712372-b823bd32-a4c1-4dc1-8201-b09531289ef6.png)
tup 变量绑定到整个元组上，因为元组是一个单独的复合元素。为了从元组中获取单个值，可以使用模式匹配（pattern matching）来解构（destructure）元组值，像这样：

![image](https://user-images.githubusercontent.com/84122239/230712391-185591de-6a80-44c3-9888-70e14eb06089.png)
![image](https://user-images.githubusercontent.com/84122239/230712398-a88540a2-4673-4b69-b62d-999afbac8cbc.png)
这个程序创建了一个元组，x，然后使用其各自的索引访问元组中的每个元素。跟大多数编程语言一样，元组的第一个索引值是 0。

不带任何值的元组有个特殊的名称，叫做 单元（unit） 元组。这种值以及对应的类型都写作 ()，表示空值或空的返回类型。如果表达式不返回任何其他值，则会隐式返回单元值。

#### **数组类型**

另一个包含多个值的方式是 数组（array）。与元组不同，数组中的每个元素的类型必须相同。Rust 中的数组与一些其他语言中的数组不同，Rust 中的数组长度是固定的。

当你想要在栈（stack）而不是在堆（heap）上为数据分配空间（第四章将讨论栈与堆的更多内容），或者是想要确保总是有固定数量的元素时，数组非常有用。但是数组并不如 vector 类型灵活。vector 类型是标准库提供的一个 允许 增长和缩小长度的类似数组的集合类型。当不确定是应该使用数组还是 vector 的时候，那么很可能应该使用 vector。第八章会详细讨论 vector。

***\*访问数组元素\****

数组是可以在栈 (stack) 上分配的已知固定大小的单个内存块。可以使用索引来访问数组的元素，像这样：

![image](https://user-images.githubusercontent.com/84122239/230712408-52f15757-da00-4179-9d41-a3f5be69d7a4.png)
 

### **3.3 函数**

Rust 代码中的***\*函数和变量名使用 snake case 规范风格。在 snake case 中，所有字母都是小写并使用下划线分隔单词。\****这是一个包含函数定义示例的程序：

Rust 不关心函数定义所在的位置，只要函数被调用时出现在调用之处可见的作用域内就行。

#### **参数**

我们可以定义为拥有 参数（parameters）的函数，参数是特殊变量，是函数签名的一部分。当函数拥有参数（形参）时，可以为这些参数提供具体的值（实参）。技术上讲，这些具体值被称为参数（arguments），但是在日常交流中，***\*人们倾向于不区分使用 parameter 和 argument 来表示函数定义中的变量或调用函数时传入的具体值。\****

在函数签名中，必须 声明每个参数的类型。这是 Rust 设计中一个经过慎重考虑的决定：要求在函数定义中提供类型注解，意味着编译器再也不需要你在代码的其他地方注明类型来指出你的意图。而且，在知道函数需要什么类型后，编译器就能够给出更有用的错误消息。

***\*语句和表达式\****

函数体由一系列的语句和一个可选的结尾表达式构成。目前为止，我们提到的函数还不包含结尾表达式，不过你已经见过作为语句一部分的表达式。***\*因为 Rust 是一门基于表达式（expression-based）的语言\****，这是一个需要理解的（不同于其他语言）重要区别。其他语言并没有这样的区别，所以让我们看看语句与表达式有什么区别以及这些区别是如何影响函数体的。

***\*语句（Statements）是执行一些操作但不返回值的指令。 表达式（Expressions）计算并产生一个值。让我们看一些例子。\****

![image](https://user-images.githubusercontent.com/84122239/230712422-b825496c-37f7-405c-93a4-71b67d13198a.png)
 

表达式会计算出一个值，并且你将编写的大部分 Rust 代码是由表达式组成的。考虑一个数学运算，比如 5 + 6，这是一个表达式并计算出值 11。表达式可以是语句的一部分：在示例 3-1 中，语句 let y = 6; 中的 6 是一个表达式，它计算出的值是 6。函数调用是一个表达式。宏调用是一个表达式。用大括号创建的一个新的块作用域也是一个表达式，例如：

***\*具有返回值的函数\****

![image](https://user-images.githubusercontent.com/84122239/230712435-df2da601-d1be-499e-889a-e9e0ce82b7e1.png)
five 函数的返回值是 5，所以返回值类型是 i32。让我们仔细检查一下这段代码。有两个重要的部分：首先，let x = five(); 这一行表明我们使用函数的返回值初始化一个变量。因为 five 函数返回 5，这一行与如下代码相同：

 

let x = 5;

其次，five 函数没有参数并定义了返回值类型，不过函数体只有单单一个 5 也没有分号，因为这是一个表达式，我们想要返回它的值。

 

 

![image](https://user-images.githubusercontent.com/84122239/230712452-1ba7f6d5-bd36-460c-a2ed-bf08753a8705.png)
#### **注释**

所有程序员都力求使其代码易于理解，不过有时还需要提供额外的解释。在这种情况下，程序员在源码中留下 注释（comments），编译器会忽略它们，不过阅读代码的人可能觉得有用。

 

这是一个简单的注释：

 

// hello, world

![image](https://user-images.githubusercontent.com/84122239/230712461-2961cd1d-ba38-4eb6-adc1-87e9852b059b.png)
#### **控制流**

根据条件是否为真来决定是否执行某些代码，以及根据条件是否为真来重复运行一段代码的能力是大部分编程语言的基本组成部分。Rust 代码中最常见的用来控制执行流的结构是 ***\*if 表达式和循环\****。

***\*if 表达式\****

![image](https://user-images.githubusercontent.com/84122239/230712471-6eb57887-96e7-4643-981e-68bee4da77da.png)
![image](https://user-images.githubusercontent.com/84122239/230712476-993ecbb6-2f00-4821-ad5e-caa8fd72c265.png)

![image](https://user-images.githubusercontent.com/84122239/230712479-d820adb4-5041-4e1c-9d99-56acfdbef4d2.png)
***\*在 let 语句中使用 if\****

因为 if 是一个表达式，***\*我们可以在 let 语句的右侧使用它\****，例如在示例 3-2 中：

![image](https://user-images.githubusercontent.com/84122239/230712486-ca0f2d79-20ea-42f9-88c1-42b8a058d1a6.png)
记住，代码块的值是其最后一个表达式的值，而数字本身就是一个表达式。在这个例子中，整个 if 表达式的值取决于哪个代码块被执行。***\*这意味着 if 的每个分支的可能的返回值都必须是相同类型；\****在示例 3-2 中，if 分支和 else 分支的结果都是 i32 整型。如果它们的类型不匹配，如下面这个例子，则会出现一个错误：

 

![image](https://user-images.githubusercontent.com/84122239/230712494-1802bbd3-0cd3-4544-baf7-a1eff23909b7.png)
这个和之前其他语言不太一样，if 条件之后的返回值类型都要一致才行。

***\*使用循环重复执行\****

Rust 有三种循环：loop、while 和 for。

使用loop重复执行代码

![image](https://user-images.githubusercontent.com/84122239/230712501-32f1e5fd-64c2-42de-bed7-814128162003.png)
***\*从循环返回值\****

![image](https://user-images.githubusercontent.com/84122239/230712513-750e15c6-5f08-4f2f-b96b-0e0003c478fd.png)
***\*循环标签：在多个循环之间消除歧义\****

如果存在嵌套循环，break 和 continue 应用于此时最内层的循环。你可以选择在一个循环上指定一个 循环标签（loop label），然后将标签与 break 或 continue 一起使用，使这些关键字应用于已标记的循环而不是最内层的循环。下面是一个包含两个嵌套循环的示例

![img](file:///C:\Users\Administrator\AppData\Local\Temp\ksohtml12804\wps46.jpg) 

外层循环有一个标签 counting_up，它将从 0 数到 2。没有标签的内部循环从 10 向下数到 9。第一个没有指定标签的 break 将只退出内层循环。***\*break 'counting_up; 语句将退出外层循环。\****

***\*While条件循环\****

![image](https://user-images.githubusercontent.com/84122239/230712515-58e565c8-9017-43d6-953b-2ca067dc9fcb.png)
![image](https://user-images.githubusercontent.com/84122239/230712518-b6ca5042-da6b-404a-9f98-0fb579eb545d.png)
但这个过程很容易出错；如果索引长度或测试条件不正确会导致程序 panic。例如，如果将 a 数组的定义改为包含 4 个元素而忘记了更新条件 while index < 4，则代码会 panic。这也使程序更慢，因为编译器增加了运行时代码来对每次循环进行条件检查，以确定在循环的每次迭代中索引是否在数组的边界内。

***\*使用for遍历集合\****

![image](https://user-images.githubusercontent.com/84122239/230712529-e09b0395-d69b-4581-bcd1-85098f39019a.png)
![image](https://user-images.githubusercontent.com/84122239/230712539-912d02ff-8be4-468d-89a1-3ad24e37a73a.png)
今天学习完了第三章 常见的编程概念（变量与可变性、数据类型、函数、注释、控制流）。

下面准备提交一些练习试试。

![image](https://user-images.githubusercontent.com/84122239/230712544-52504c64-a039-43f8-a723-ad0ad50096c1.png)
![image](https://user-images.githubusercontent.com/84122239/230712548-fb4cc737-3d73-4179-96b9-af422b993e0a.png)
然后，重新设置

打开git-cmd.exe，然后输入，要分开输入，不能一次输两个git，不然会报错。

git config –-global  user.name "erhyang"

git config -–global  user.email "erhyang@163.com"

![image](https://user-images.githubusercontent.com/84122239/230712564-5944fe81-838c-4e1a-823b-fdcc119bfbf7.png)
测试了一下，能正常提交，显示排名，找了半天排名的链接。

https://learningos.github.io/rust-rustlings-ranking/

 

 

学习记录提交链接：

https://github.com/LearningOS/rust-based-os-comp2023/discussions/170?sort=new

 

发现别人做的学习记录都很不错，自己今天准备也开始提交学习记录。

 

# 2023.04.03

## 4 **认识所有权**

### 4.1 什么是所有权？

所有权（系统）是 Rust 最为与众不同的特性，对语言的其他部分有着深刻含义。它让 Rust 无需垃圾回收（garbage collector）即可保障内存安全，因此理解 Rust 中所有权如何工作是十分重要的。本章，我们将讲到所有权以及相关功能：***\*借用（borrowing）、slice 以及 Rust 如何在内存中布局数据。\****

所有程序都必须管理其运行时使用计算机内存的方式。一些语言中具有垃圾回收机制，在程序运行时有规律地寻找不再使用的内存；在另一些语言中，程序员必须亲自分配和释放内存。Rust 则选择了第三种方式：***\*通过所有权系统管理内存，编译器在编译时会根据一系列的规则进行检查\****。如果违反了任何这些规则，程序都不能编译。在运行时，所有权系统的任何功能都不会减慢程序。

***\*栈（Stack）与堆（Heap）\****

在很多语言中，你并不需要经常考虑到栈与堆。不过在像 Rust 这样的系统编程语言中，值是位于栈上还是堆上在更大程度上影响了语言的行为以及为何必须做出这样的抉择。我们会在本章的稍后部分描述所有权与栈和堆相关的内容，所以这里只是一个用来预热的简要解释。

 

***\*栈和堆都是代码在运行时可供使用的内存，但是它们的结构不同。\****栈以放入值的顺序存储值并以相反顺序取出值。这也被称作 后进先出（last in, first out）。想象一下一叠盘子：当增加更多盘子时，把它们放在盘子堆的顶部，当需要盘子时，也从顶部拿走。不能从中间也不能从底部增加或拿走盘子！增加数据叫做 进栈（pushing onto the stack），而移出数据叫做 出栈（popping off the stack）。***\*栈中的所有数据都必须占用已知且固定的大小。在编译时大小未知或大小可能变化的数据，要改为存储在堆上。\**** 堆是缺乏组织的：当向堆放入数据时，你要请求一定大小的空间。***\*内存分配器（memory allocator）\****在堆的某处找到一块足够大的空位，把它标记为已使用，并返回一个表示该位置地址的 指针（pointer）。这个过程称作 在堆上分配内存（allocating on the heap），有时简称为 “分配”（allocating）。（***\*将数据推入栈中并不被认为是分配\****）。因为指向放入堆中数据的***\*指针是已知的并且大小是固定的\****，你可以将该指针存储在栈上，不过当需要实际数据时，必须访问指针。想象一下去餐馆就座吃饭。当进入时，你说明有几个人，餐馆员工会找到一个够大的空桌子并领你们过去。如果有人来迟了，他们也可以通过询问来找到你们坐在哪。

 

入栈比在堆上分配内存要快，因为（入栈时）分配器无需为存储新数据去搜索内存空间；其位置总是在栈顶。***\*相比之下，在堆上分配内存则需要更多的工作，这是因为分配器必须首先找到一块足够存放数据的内存空间，并接着做一些记录为下一次分配做准备。\****

 

***\*访问堆上的数据比访问栈上的数据慢，因为必须通过指针来访问。\*******\*现代处理器在内存中跳转越少就越快（缓存）。\****继续类比，假设有一个服务员在餐厅里处理多个桌子的点菜。在一个桌子报完所有菜后再移动到下一个桌子是最有效率的。从桌子 A 听一个菜，接着桌子 B 听一个菜，然后再桌子 A，然后再桌子 B 这样的流程会更加缓慢。出于同样原因，处理器在处理的数据彼此较近的时候（比如在栈上）比较远的时候（比如可能在堆上）能更好的工作。

 

当你的代码调用一个函数时，***\*传递给函数的值（包括可能指向堆上数据的指针）和函数的局部变量被压入栈中\****。当函数结束时，这些值被移出栈。

 

***\*跟踪哪部分代码正在使用堆上的哪些数据，最大限度的减少堆上的重复数据的数量，以及清理堆上不再使用的数据确保不会耗尽空间，这些问题正是所有权系统要处理的。\****一旦理解了所有权，你就不需要经常考虑栈和堆了，不过明白了所有权的主要目的就是为了管理堆数据，能够帮助解释为什么所有权要以这种方式工作。

***\*所有权规则\****

1) Rust 中的每一个值都有一个所有者（owner）。
2) 值在任一时刻有且只有一个所有者。
3) 当所有者（变量）离开作用域，这个值将被丢弃。

***\*变量作用域\****

![image](https://user-images.githubusercontent.com/84122239/230712579-468a11e0-e3c6-4b8e-b0cb-35dc20254e72.png)
***\*String类型\****

![image](https://user-images.githubusercontent.com/84122239/230712586-c332dc3c-3ebf-4b61-8730-8b873e6a65b6.png)
***\*内存与分配\****

就字符串字面值来说，我们在编译时就知道其内容，所以文本被直接硬编码进最终的可执行文件中。这使得字符串字面值快速且高效。不过这些特性都只得益于字符串字面值的不可变性。不幸的是，我们不能为了每一个在编译时大小未知的文本而将一块内存放入二进制文件中，并且它的大小还可能随着程序运行而改变。

对于 String 类型，为了支持一个可变，可增长的文本片段，需要在堆上分配一块在编译时未知大小的内存来存放内容。这意味着：

l 必须在运行时向内存分配器（memory allocator）请求内存。

l 需要一个当我们处理完 String 时将内存返回给分配器的方法。

第一部分由我们完成：当调用 String::from 时，它的实现 (implementation) 请求其所需的内存。这在编程语言中是非常通用的。

然而，第二部分实现起来就各有区别了。***\*在有 垃圾回收（garbage collector，GC）的语言中，GC 记录并清除不再使用的内存，而我们并不需要关心它。在大部分没有 GC 的语言中，识别出不再使用的内存并调用代码显式释放就是我们的责任了，跟请求内存的时候一样。\****从历史的角度上说正确处理内存回收曾经是一个困难的编程问题。如果忘记回收了会浪费内存。如果过早回收了，将会出现无效变量。如果重复回收，这也是个 bug。我***\*们需要精确的为一个 allocate 配对一个 free。\****

Rust 采取了一个不同的策略：内存在拥有它的变量离开作用域后就被自动释放。下面是示例 4-1 中作用域例子的一个使用 String 而不是字符串字面值的版本：

![image](https://user-images.githubusercontent.com/84122239/230712595-697349bb-6e79-438d-985f-5f8aedb60e75.png)
这是一个将 String 需要的内存返回给分配器的很自然的位置：当 s 离开作用域的时候。当变量离开作用域，Rust 为我们调用一个特殊的函数。这个函数叫做 drop，在这里 String 的作者可以放置释放内存的代码。Rust 在结尾的 } 处自动调用 drop。

![image](https://user-images.githubusercontent.com/84122239/230712601-91f2ef83-9d1a-4901-9e2b-31257d9b0c0b.png)
***\*变量与数据交互的方式（一）：移动\****

![image](https://user-images.githubusercontent.com/84122239/230712612-53fd9cac-4e91-4668-93eb-4f824e0654c2.png)
![image](https://user-images.githubusercontent.com/84122239/230712617-fe9f1912-541a-44a1-9364-6e3e3b949ccf.png)

长度表示 String 的内容当前使用了多少字节的内存。容量是 String 从分配器总共获取了多少字节的内存。长度与容量的区别是很重要的，不过在当前上下文中并不重要，所以现在可以忽略容量。

 

当我们将 s1 赋值给 s2，String 的数据被复制了，这意味着我们从栈上拷贝了它的指针、长度和容量。我们并没有复制指针指向的堆上数据。换句话说，内存中数据的表现如图 4-2 所示。

![image](https://user-images.githubusercontent.com/84122239/230712630-51ebde62-5e94-4228-b6c9-74a8b790a472.png)
之前我们提到过当变量离开作用域后，Rust 自动调用 drop 函数并清理变量的堆内存。不过图 4-2 展示了两个数据指针指向了同一位置。这就有了一个问题：当 s2 和 s1 离开作用域，他们都会尝试释放相同的内存。***\*这是一个叫做 二次释放（double free）的错误，也是之前提到过的内存安全性 bug 之一。两次释放（相同）内存会导致内存污染，它可能会导致潜在的安全漏洞。\****

为了确保内存安全，在 let s2 = s1; 之后，Rust 认为 s1 不再有效，***\*因此 Rust 不需要在 s1 离开作用域后清理任何东西。\****看看在 s2 被创建之后尝试使用 s1 会发生什么；这段代码不能运行：

![image](https://user-images.githubusercontent.com/84122239/230712641-a018680e-e702-4608-854e-da02811c6861.png)
如果你在其他语言中听说过术语 浅拷贝（shallow copy）和 深拷贝（deep copy），那么拷贝指针、长度和容量而不拷贝数据可能听起来像浅拷贝。不过因为 Rust 同时使第一个变量无效了，这个操作被称为 移动（move），而不是叫做浅拷贝。上面的例子可以解读为 s1 被 移动 到了 s2 中。那么具体发生了什么，如图 4-4 所示。

![image](https://user-images.githubusercontent.com/84122239/230712648-d0917f05-1e9b-4368-96e8-d18537899333.png)
这样就解决了我们的问题！因为只有 s2 是有效的，当其离开作用域，它就释放自己的内存，完毕。

另外，这里还隐含了一个设计选择：Rust 永远也不会自动创建数据的 “深拷贝”。因此，任何 自动 的复制可以被认为对运行时性能影响较小。

***\*变量与数据交互的方式（二）：克隆\****

![image](https://user-images.githubusercontent.com/84122239/230712660-65f3d0d9-7b14-4cc2-8f8a-2c29a0a8d8b5.png)
***\*只在栈上的数据：拷贝\****

![image](https://user-images.githubusercontent.com/84122239/230712669-0e13bbf2-9aba-4d28-ab85-5e00c268a3cb.png)
原因是像整型这样的在编译时已知大小的类型被整个存储在栈上，所以拷贝其实际的值是快速的。这意味着没有理由在创建变量 y 后使 x 无效。换句话说，这里没有深浅拷贝的区别，所以这里调用 clone 并不会与通常的浅拷贝有什么不同，我们可以不用管它。

 

Rust 有一个叫做 Copy trait 的特殊注解，可以用在类似整型这样的存储在栈上的类型上（第十章将会详细讲解 trait）。如果一个类型实现了 Copy trait，那么一个旧的变量在将其赋值给其他变量后仍然可用。

 

Rust 不允许自身或其任何部分实现了 Drop trait 的类型使用 Copy trait。如果我们对其值离开作用域时需要特殊处理的类型使用 Copy 注解，将会出现一个编译时错误。要学习如何为你的类型添加 Copy 注解以实现该 trait，请阅读附录 C 中的 “可派生的 trait”。

 

那么哪些类型实现了 Copy trait 呢？你可以查看给定类型的文档来确认，不过作为一个通用的规则，***\*任何一组简单标量值的组合都可以实现 Copy，任何不需要分配内存或某种形式资源的类型都可以实现 Copy 。\****如下是一些 Copy 的类型：

所有整数类型，比如 u32。

布尔类型，bool，它的值是 true 和 false。

所有浮点数类型，比如 f64。

字符类型，char。

元组，当且仅当其包含的类型也都实现 Copy 的时候。比如，(i32, i32) 实现了 Copy，但 (i32, String) 就没有。

***\*所有权与函数\****

![image](https://user-images.githubusercontent.com/84122239/230712676-a104ef84-b47f-4756-814a-73bfdc4e5ce7.png)
***\*返回值与作用域\****

返回值也可以转移所有权。

![image](https://user-images.githubusercontent.com/84122239/230712684-d966d8ff-df59-4caa-b697-7f1362c7ca62.png)
变量的所有权总是遵循相同的模式：将值赋给另一个变量时移动它。当持有堆中数据值的变量离开作用域时，其值将通过 drop 被清理掉，除非数据被移动为另一个变量所有。

 

虽然这样是可以的，但是在每一个函数中都获取所有权并接着返回所有权有些啰嗦。如果我们想要函数使用一个值但不获取所有权该怎么办呢？如果我们还要接着使用它的话，每次都传进去再返回来就有点烦人了，除此之外，我们也可能想返回函数体中产生的一些数据。

但是这未免有些形式主义，而且这种场景应该很常见。幸运的是，Rust 对此提供了一个不用获取所有权就可以使用值的功能，叫做 引用（references）。

###  4.2 引用与借用

 下面是如何定义并使用一个（新的）calculate_length 函数，它以一个对象的引用作为参数而不是获取值的所有权：

>  fn main() {
>   let s1 = String::from("hello");
>
>   let len = calculate_length(&s1);
>
>   println!("The length of '{}' is {}.", s1, len);
>  }
>
>  fn calculate_length(s: &String) -> usize {
>   s.len()
>  }
>
>  ```
>  
>  ```

 首先，注意变量声明和函数返回值中的所有元组代码都消失了。其次，注意我们传递 `&s1` 给 `calculate_length`，同时在函数定义中，我们获取 `&String` 而不是 `String`。这些 & 符号就是 **引用**，它们允许你使用值但不获取其所有权。图 4-5 展示了一张示意图。

![image](https://user-images.githubusercontent.com/84122239/230712699-0072d819-d9bf-46b7-b372-9de44b4a8f26.png)
 **注意：与使用 `&` 引用相反的操作是 解引用（*dereferencing*），它使用解引用运算符，`*`。我们将会在第八章遇到一些解引用运算符，并在第十五章详细讨论解引用。**

 fn main() {
    let s1 = String::from("hello");

    let len = calculate_length(&s1);
    
    println!("The length of '{}' is {}.", s1, len);

}

fn calculate_length(s: &String) -> usize {
    s.len()
}

 `&s1` 语法让我们创建一个 **指向** 值 `s1` 的引用，但是并不拥有它。因为并不拥有这个值，所以当引用停止使用时，它所指向的值也不会被丢弃。

![image](https://user-images.githubusercontent.com/84122239/230712726-adf7eded-7640-4123-ba22-7f4239623142.png)
![image](https://user-images.githubusercontent.com/84122239/230712738-3f377538-4fef-47d1-ae86-7a3a4e293c52.png)
 **可变引用**

我们通过一个小调整就能修复示例 4-6 代码中的错误，允许我们修改一个借用的值，这就是 **可变引用**（*mutable reference*）：

![image](https://user-images.githubusercontent.com/84122239/230712749-d17516d5-0a2e-4215-bf2e-99b5e0e7da6e.png)
首先，我们必须将 `s` 改为 `mut`。然后在调用 `change` 函数的地方创建一个可变引用 `&mut s`，并更新函数签名以接受一个可变引用 `some_string: &mut String`。这就非常清楚地表明，`change` 函数将改变它所借用的值。

可变引用有一个很大的限制：如果你有一个对该变量的可变引用，你就不能再创建对该变量的引用。这些尝试创建两个 `s` 的可变引用的代码会失败：

![image](https://user-images.githubusercontent.com/84122239/230712753-13ca466b-e4b6-47f0-86bb-3ea0d9cb352a.png)
这个报错说这段代码是无效的，因为我们不能在同一时间多次将 `s` 作为可变变量借用。第一个可变的借入在 `r1` 中，并且必须持续到在 `println！` 中使用它，但是在那个可变引用的创建和它的使用之间，我们又尝试在 `r2` 中创建另一个可变引用，该引用借用与 `r1` 相同的数据。

这一限制以一种非常小心谨慎的方式允许可变性，防止同一时间对同一数据存在多个可变引用。新 Rustacean 们经常难以适应这一点，因为大部分语言中变量任何时候都是可变的。这个限制的好处是 Rust 可以在编译时就避免数据竞争。**数据竞争**（*data race*）类似于竞态条件，它可由这三个行为造成：

- 两个或更多指针同时访问同一数据。
- 至少有一个指针被用来写入数据。
- 没有同步数据访问的机制。

数据竞争会导致未定义行为，难以在运行时追踪，并且难以诊断和修复；Rust 避免了这种情况的发生，因为它甚至不会编译存在数据竞争的代码！

一如既往，可以使用大括号来创建一个新的作用域，以允许拥有多个可变引用，只是不能 **同时** 拥有：

![image](https://user-images.githubusercontent.com/84122239/230712767-79ab5186-4a22-43cd-87e4-3cddbee90428.png)
**这个地方应该是可以创建多个不可变引用，但是在同一个作用域下只能有一个可变引用，也不能同时不可变引用和可变引用同时存在。**

哇哦！我们 **也** 不能在拥有不可变引用的同时拥有可变引用。

不可变引用的用户可不希望在他们的眼皮底下值就被意外的改变了！然而，多个不可变引用是可以的，因为没有哪个只能读取数据的人有能力影响其他人读取到的数据。

注意一个引用的作用域从声明的地方开始一直持续到最后一次使用为止。例如，因为最后一次使用不可变引用（`println!`)，发生在声明可变引用之前，所以如下代码是可以编译的：

![image](https://user-images.githubusercontent.com/84122239/230712773-16ab8fcd-8731-4fa8-b6d6-8099f2b1f4c6.png)
不可变引用 `r1` 和 `r2` 的作用域在 `println!` 最后一次使用之后结束，这也是创建可变引用 `r3` 的地方。它们的作用域没有重叠，所以代码是可以编译的。编译器可以在作用域结束之前判断不再使用的引用。

尽管这些错误有时使人沮丧，但请牢记这是 Rust 编译器在提前指出一个潜在的 bug（在编译时而不是在运行时）并精准显示问题所在。这样你就不必去跟踪为何数据并不是你想象中的那样。

**悬垂应用**

在具有指针的语言中，很容易通过释放内存时保留指向它的指针而错误地生成一个 **悬垂指针**（*dangling pointer*），所谓悬垂指针是其指向的内存可能已经被分配给其它持有者。相比之下，在 Rust 中编译器确保引用永远也不会变成悬垂状态：当你拥有一些数据的引用，编译器确保数据不会在其引用之前离开作用域。

让我们尝试创建一个悬垂引用，Rust 会通过一个编译时错误来避免：

![image](https://user-images.githubusercontent.com/84122239/230712778-78ff3905-6cf8-455c-98ee-0fa6918b5ac6.png)
![image](https://user-images.githubusercontent.com/84122239/230712784-1fad1997-14e2-4170-82c0-59df43f54ac1.png)
![image](https://user-images.githubusercontent.com/84122239/230712789-a63042aa-8a79-4293-9429-21164c4b976f.png)
### 4.3 Slice类型

**字符串 slice**（*string slice*）是 `String` 中一部分值的引用，它看起来像这样：

![image](https://user-images.githubusercontent.com/84122239/230712791-cbe02d2a-1eb4-4302-b62e-1f8c4fbb4456.png)
不同于整个 `String` 的引用，`hello` 是一个部分 `String` 的引用，由一个额外的 `[0..5]` 部分指定。可以使用一个由中括号中的 `[starting_index..ending_index]` 指定的 range 创建一个 slice，其中 `starting_index` 是 slice 的第一个位置，`ending_index` 则是 slice 最后一个位置的后一个值。在其内部，slice 的数据结构存储了 slice 的开始位置和长度，长度对应于 `ending_index` 减去 `starting_index` 的值。所以对于 `let world = &s[6..11];` 的情况，`world` 将是一个包含指向 `s` 索引 6 的指针和长度值 5 的 slice。

图 4-6 展示了一个图例。

![image](https://user-images.githubusercontent.com/84122239/230712798-588ebba4-af8c-43bf-ab05-9ec603a3f773.png)
![image](https://user-images.githubusercontent.com/84122239/230712806-8a2f8082-6292-4e86-adb2-c105f64e1753.png)
![image](https://user-images.githubusercontent.com/84122239/230712813-22d4cda8-667f-4aec-b04f-0e05bece60ff.png)
回忆一下借用规则，当拥有某值的不可变引用时，就不能再获取一个可变引用。因为 `clear` 需要清空 `String`，它尝试获取一个可变引用。在调用 `clear` 之后的 `println!` 使用了 `word` 中的引用，所以这个不可变的引用在此时必须仍然有效。Rust 不允许 `clear` 中的可变引用和 `word` 中的不可变引用同时存在，因此编译失败。Rust 不仅使得我们的 API 简单易用，也在编译时就消除了一整类的错误！（**这个不是很明白，后面是从网上找的其他的解释**）（clear()方法需要修改字符串，因此需要可变引用。由于word已经持有原始字符串的不可变引用，clear()的调用在rust中是不允许的，除非后面没有对word的访问。）

![image](https://user-images.githubusercontent.com/84122239/230712823-2336ff87-7fa9-46eb-a353-69563fdb1bd6.png)
**总结**

所有权、借用和 slice 这些概念让 Rust 程序在编译时确保内存安全。Rust 语言提供了跟其他系统编程语言相同的方式来控制你使用的内存，但拥有数据所有者在离开作用域后自动清除其数据的功能意味着你无须额外编写和调试相关的控制代码。

所有权系统影响了 Rust 中很多其他部分的工作方式，所以我们还会继续讲到这些概念，这将贯穿本书的余下内容。让我们开始第五章，来看看如何将多份数据组合进一个 `struct` 中。

### 4月3号晚上课程

![image](https://user-images.githubusercontent.com/84122239/230712830-38e12755-dda8-4313-a8b2-d9d430499b08.png)
![image](https://user-images.githubusercontent.com/84122239/230712827-e61e5951-1ddf-4fd1-8981-5e10f5c6dc0f.png)
![image](https://user-images.githubusercontent.com/84122239/230712847-4a0f1ec2-dcff-43f7-ac79-b08468e93bcd.png)



# 2023.04.04

昨天晚上的课也讲了结构体和枚举，今天把这块也给看一下。

## 5 结构体定义和实例化

### 5.1 结构体的定义和实例化

定义结构体，需要使用 `struct` 关键字并为整个结构体提供一个名字。结构体的名字需要描述它所组合的数据的意义。接着，在大括号中，定义每一部分数据的名字和类型，我们称为 **字段**（*field*）。例如，示例 5-1 展示了一个存储用户账号信息的结构体：

![image](https://user-images.githubusercontent.com/84122239/230712850-0dec50cc-b138-42e1-9a02-c0de54d5dc40.png)
一旦定义了结构体后，为了使用它，通过为每个字段指定具体值来创建这个结构体的 **实例**。创建一个实例需要以结构体的名字开头，接着在大括号中使用 `key: value` 键 - 值对的形式提供字段，其中 key 是字段的名字，value 是需要存储在字段中的数据值。实例中字段的顺序不需要和它们在结构体中声明的顺序一致。换句话说，结构体的定义就像一个类型的通用模板，而实例则会在这个模板中放入特定数据来创建这个类型的值。例如，可以像示例 5-2 这样来声明一个特定的用户：

![image](https://user-images.githubusercontent.com/84122239/230712854-8d921222-35d6-4235-8cf6-6aecf4a3bfba.png)
为了从结构体中获取某个特定的值，可以使用点号。举个例子，想要用户的邮箱地址，可以用 `user1.email`。如果结构体的实例是可变的，我们可以使用点号并为对应的字段赋值。示例 5-3 展示了如何改变一个可变的 `User` 实例中 `email` 字段的值：

![image](https://user-images.githubusercontent.com/84122239/230712860-d9ec80ac-26ef-4cbd-97cf-2b886a20c353.png)
示例 5-3：改变 `User` 实例 `email` 字段的值

![image](https://user-images.githubusercontent.com/84122239/230712864-c8797125-f4e2-41f8-9f74-90adae9f51e3.png)
示例 5-4：`build_user` 函数获取 email 和用户名并返回 `User` 实例

**使用字段初始化简写语法**

因为示例 5-4 中的参数名与字段名都完全相同，我们可以使用 **字段初始化简写语法**（*field init shorthand*）来重写 `build_user`，这样其行为与之前完全相同，不过无需重复 `username` 和 `email` 了，如示例 5-5 所示。

![image](https://user-images.githubusercontent.com/84122239/230712870-8210591d-5055-416c-aba0-709aac036e72.png)
示例 5-5：`build_user` 函数使用了字段初始化简写语法，因为 `username` 和 `email` 参数与结构体字段同名

这里我们创建了一个新的 `User` 结构体实例，它有一个叫做 `email` 的字段。我们想要将 `email` 字段的值设置为 `build_user` 函数 `email` 参数的值。因为 `email` 字段与 `email` 参数有着相同的名称，则只需编写 `email` 而不是 `email: email`。

**使用结构体更新语法从其他实例创建实例**

使用旧实例的大部分值但改变其部分值来创建一个新的结构体实例通常是很有用的。这可以通过 **结构体更新语法**（*struct update syntax*）实现。

使用结构体更新语法，我们可以通过更少的代码来达到相同的效果，如示例 5-7 所示。`..` 语法指定了剩余未显式设置值的字段应有与给定实例对应字段相同的值。

![image](https://user-images.githubusercontent.com/84122239/230712876-ee28fa6e-6cfe-4c06-afda-a32fa50e0871.png)
示例 5-7：使用结构体更新语法为一个 `User` 实例设置一个新的 `email` 值，不过其余值来自 `user1` 变量中实例的字段

示例 5-7 中的代码也在 `user2` 中创建了一个新实例，但该实例中 `email` 字段的值与 `user1` 不同，而 `username`、 `active` 和 `sign_in_count` 字段的值与 `user1` 相同。`..user1` 必须放在最后，以指定其余的字段应从 `user1` 的相应字段中获取其值，但我们可以选择以任何顺序为任意字段指定值，而不用考虑结构体定义中字段的顺序。

**使用没有命名字段的元组结构体来创建不同的类型**

也可以定义与元组（在第三章讨论过）类似的结构体，称为 **元组结构体**（*tuple structs*）。**元组结构体有着结构体名称提供的含义，但没有具体的字段名，只有字段的类型**。当你想给整个元组取一个名字，并使元组成为与其他元组不同的类型时，元组结构体是很有用的，这时像常规结构体那样为每个字段命名就显得多余和形式化了。

![image](https://user-images.githubusercontent.com/84122239/230712888-7f22bc72-4502-4948-9141-6b4307887f81.png)
注意 `black` 和 `origin` 值的类型不同，因为它们是不同的元组结构体的实例。你定义的每一个结构体有其自己的类型，即使结构体中的字段可能有着相同的类型。**例如，一个获取 `Color` 类型参数的函数不能接受 `Point` 作为参数，即便这两个类型都由三个 `i32` 值组成。**在其他方面，元组结构体实例类似于元组，你可以将它们解构为单独的部分，也可以使用 `.` 后跟索引来访问单独的值，等等。

**没有任何字段的类单元结构体**

我们也可以定义一个没有任何字段的结构体！它们被称为 **类单元结构体**（*unit-like structs*）因为它们类似于 `()`，即[“元组类型”](https://kaisery.github.io/trpl-zh-cn/ch03-02-data-types.html#元组类型)一节中提到的 unit 类型。类单元结构体常常在你想要在某个类型上实现 trait 但不需要在类型中存储数据的时候发挥作用。

![image](https://user-images.githubusercontent.com/84122239/230712893-e0d9c5e4-0a20-4559-b18f-34af1aab9c08.png)
要定义 `AlwaysEqual`，我们使用 `struct` 关键字，我们想要的名称，然后是一个分号。不需要花括号或圆括号！然后，我们可以以类似的方式在 `subject` 变量中获得 `AlwaysEqual` 的实例：使用我们定义的名称，不需要任何花括号或圆括号。想象一下，**我们将实现这个类型的行为，即每个实例始终等于每一个其他类型的实例，也许是为了获得一个已知的结果以便进行测试。（什么意思？）**我们不需要任何数据来实现这种行为，你将在第十章中，看到如何定义特性并在任何类型上实现它们，包括类单元结构体。

**结构体数据的所有权**

可以使结构体存储被其他对象拥有的数据的引用，不过这么做的话需要用上 **生命周期**（*lifetimes*），这是一个第十章会讨论的 Rust 功能。生命周期确保结构体引用的数据有效性跟结构体本身保持一致。如果你尝试在结构体中存储一个引用而不指定生命周期将是无效的，比如这样：

![image](https://user-images.githubusercontent.com/84122239/230712904-9f8f3090-e8c2-4807-a9d7-cc0415eac33f.png)
编译器会报需要生命周期标识符的错误。

### 5.2 结构体示例程序

![image](https://user-images.githubusercontent.com/84122239/230712907-aea08cee-0273-40fb-8136-938068df7add.png)
使用元组重构上面的代码，实现求长方形面积。上面的参数看不出关联性。

![image](https://user-images.githubusercontent.com/84122239/230712914-ca05a36d-b5dc-4905-ac3e-afd02de93481.png)
使用结构体重构：赋予更多意义。我们使用结构体为数据命名来为其赋予意义。我们可以将我们正在使用的元组转换成一个有整体名称而且每个部分也有对应名字的结构体。

![image](https://user-images.githubusercontent.com/84122239/230712915-defe3a62-7847-418c-8ed6-92e14aecd445.png)
这里我们定义了一个结构体并称其为 `Rectangle`。在大括号中定义了字段 `width` 和 `height`，类型都是 `u32`。接着在 `main` 中，我们创建了一个具体的 `Rectangle` 实例，它的宽是 `30`，高是 `50`。

函数 `area` 现在被定义为接收一个名叫 `rectangle` 的参数，其类型是一个结构体 `Rectangle` 实例的不可变借用。第四章讲到过，我们希望借用结构体而不是获取它的所有权，这样 `main` 函数就可以保持 `rect1` 的所有权并继续使用它，所以这就是为什么在函数签名和调用的地方会有 `&`。

`area` 函数访问 `Rectangle` 实例的 `width` 和 `height` 字段（注意，访问对结构体的引用的字段不会移动字段的所有权，这就是为什么你经常看到对结构体的引用）。`area` 的函数签名现在明确的阐述了我们的意图：使用 `Rectangle` 的 `width` 和 `height` 字段，计算 `Rectangle` 的面积。这表明宽高是相互联系的，并为这些值提供了描述性的名称而不是使用元组的索引值 `0` 和 `1` 。结构体胜在更清晰明了。

**通过派生trait增加使用功能**

![image](https://user-images.githubusercontent.com/84122239/230712928-e994f7c3-8f84-4b9f-9a2b-5b2e8148fdf4.png)
在 `{}` 中加入 `:?` 指示符告诉 `println!` 我们想要使用叫做 `Debug` 的输出格式。`Debug` 是一个 trait，它允许我们以一种对开发者有帮助的方式打印结构体，以便当我们调试代码时能看到它的值。

Rust **确实** 包含了打印出调试信息的功能，不过我们必须为结构体显式选择这个功能。为此，在结构体定义之前加上外部属性 `#[derive(Debug)]`。



当我们有一个更大的结构体时，能有更易读一点的输出就好了，为此可以使用 `{:#?}` 替换 `println!` 字符串中的 `{:?}`。在这个例子中使用 `{:#?}` 风格将会输出如下：

![image](https://user-images.githubusercontent.com/84122239/230712937-b9a2b73f-cb5c-4d65-969b-0d77b358b363.png)


另一种使用 `Debug` 格式打印数值的方法是使用 [`dbg!` 宏](https://doc.rust-lang.org/std/macro.dbg.html)。`dbg!` 宏接收一个表达式的所有权（与 `println!` 宏相反，后者接收的是引用），打印出代码中调用 dbg! 宏时所在的文件和行号，以及该表达式的结果值，并返回该值的所有权。

> 注意：调用 `dbg!` 宏会打印到标准错误控制台流（`stderr`），与 `println!` 不同，后者会打印到标准输出控制台流（`stdout`）。我们将在[第十二章 “将错误信息写入标准错误而不是标准输出” 一节](https://kaisery.github.io/trpl-zh-cn/ch12-06-writing-to-stderr-instead-of-stdout.html)中更多地讨论 `stderr` 和 `stdout`。

![image](https://user-images.githubusercontent.com/84122239/230712945-3f1db4c9-686e-401c-9d43-8c439bc339a5.png)
我们可以把 `dbg!` 放在表达式 `30 * scale` 周围，因为 `dbg!` 返回表达式的值的所有权，所以 `width` 字段将获得相同的值，就像我们在那里没有 `dbg!` 调用一样。我们不希望 `dbg!` 拥有 `rect1` 的所有权，所以我们在下一次调用 `dbg!` 时传递一个引用。下面是这个例子的输出结果：

![image](https://user-images.githubusercontent.com/84122239/230712953-a29714aa-7778-4f4f-bfb5-7ab4dfc9417c.png)
我们可以看到第一点输出来自 *src/main.rs* 第 10 行，我们正在调试表达式 `30 * scale`，其结果值是 `60`（为整数实现的 `Debug` 格式化是只打印它们的值）。在 *src/main.rs* 第 14 行 的 `dbg!` 调用输出 `&rect1` 的值，即 `Rectangle` 结构。这个输出使用了更为易读的 `Debug` 格式。当你试图弄清楚你的代码在做什么时，`dbg!` 宏可能真的很有帮助！

### 5.3 方法语法

**方法**（method）与函数类似：它们使用 `fn` 关键字和名称声明，可以拥有参数和返回值，同时包含在某处调用该方法时会执行的代码。

**定义方法**

![image](https://user-images.githubusercontent.com/84122239/230712964-38284ffe-92fe-4c14-9b99-f110b1227b3b.png)
为了使函数定义于 `Rectangle` 的上下文中，我们开始了一个 `impl` 块（`impl` 是 *implementation* 的缩写），这个 `impl` 块中的所有内容都将与 `Rectangle` 类型相关联。接着将 `area` 函数移动到 `impl` 大括号中，并将签名中的第一个（在这里也是唯一一个）参数和函数体中其他地方的对应参数改成 `self`。然后在 `main` 中将我们先前调用 `area` 方法并传递 `rect1` 作为参数的地方，改成使用 **方法语法**（*method syntax*）在 `Rectangle` 实例上调用 `area` 方法。方法语法获取一个实例并加上一个点号，后跟方法名、圆括号以及任何参数。

在 `area` 的签名中，使用 `&self` 来替代 `rectangle: &Rectangle`，`&self` 实际上是 `self: &Self` 的缩写。在一个 `impl` 块中，`Self` 类型是 `impl` 块的类型的别名。方法的第一个参数必须有一个名为 `self` 的`Self` 类型的参数，所以 Rust 让你在第一个参数位置上只用 `self` 这个名字来缩写。注意，我们仍然需要在 `self` 前面使用 `&` 来表示这个方法借用了 `Self` 实例，就像我们在 `rectangle: &Rectangle` 中做的那样。方法可以选择获得 `self` 的所有权，或者像我们这里一样不可变地借用 `self`，或者可变地借用 `self`，就跟其他参数一样。

这里选择 `&self` 的理由跟在函数版本中使用 `&Rectangle` 是相同的：我们并不想获取所有权，只希望能够读取结构体中的数据，而不是写入。如果想要在方法中改变调用方法的实例，需要将第一个参数改为 `&mut self`。通过仅仅使用 `self` 作为第一个参数来使方法获取实例的所有权是很少见的；这种技术通常用在当方法将 `self` 转换成别的实例的时候，这时我们想要防止调用者在转换之后使用原始的实例。

使用方法替代函数，除了可使用方法语法和不需要在每个函数签名中重复 `self` 的类型之外，其主要好处在于组织性。我们将某个类型实例能做的所有事情都一起放入 `impl` 块中，而不是让将来的用户在我们的库中到处寻找 `Rectangle` 的功能。

![image](https://user-images.githubusercontent.com/84122239/230712969-69010443-f360-4991-b5d8-54afffab182d.png)
在这里，我们选择让 `width` 方法在实例的 `width` 字段的值大于 `0` 时返回 `true`，等于 `0` 时则返回 `false`：我们可以出于任何目的，在同名的方法中使用同名的字段。在 `main` 中，当我们在 `rect1.width` 后面加上括号时。Rust 知道我们指的是方法 `width`。当我们不使用圆括号时，Rust 知道我们指的是字段 `width`。

通常，但并不总是如此，与字段同名的方法将被定义为只返回字段中的值，而不做其他事情。这样的方法被称为 *getters*，Rust 并不像其他一些语言那样为结构字段自动实现它们。Getters 很有用，因为你可以把字段变成私有的，但方法是公共的，这样就可以把对字段的只读访问作为该类型公共 API 的一部分。



[`->` 运算符到哪去了？](https://kaisery.github.io/trpl-zh-cn/ch05-03-method-syntax.html#--运算符到哪去了)

在 C/C++ 语言中，有两个不同的运算符来调用方法：`.` 直接在对象上调用方法，而 `->` 在一个对象的指针上调用方法，这时需要先解引用（dereference）指针。换句话说，如果 `object` 是一个指针，那么 `object->something()` 就像 `(*object).something()` 一样。

Rust 并没有一个与 `->` 等效的运算符；相反，Rust 有一个叫 **自动引用和解引用**（*automatic referencing and dereferencing*）的功能。方法调用是 Rust 中少数几个拥有这种行为的地方。

它是这样工作的：当使用 `object.something()` 调用方法时，Rust 会自动为 `object` 添加 `&`、`&mut` 或 `*` 以便使 `object` 与方法签名匹配。也就是说，这些代码是等价的：

```rust
p1.distance(&p2);
(&p1).distance(&p2);
```

第一行看起来简洁的多。这种自动引用的行为之所以有效，是因为方法有一个明确的接收者———— `self` 的类型。在给出接收者和方法名的前提下，Rust 可以明确地计算出方法是仅仅读取（`&self`），做出修改（`&mut self`）或者是获取所有权（`self`）。事实上，Rust 对方法接收者的隐式借用让所有权在实践中更友好。

**带有更多参数的方法**



如果结合示例 5-14 的 `main` 函数来运行，就会看到期望的输出。在方法签名中，可以在 `self` 后增加多个参数，而且这些参数就像函数中的参数一样工作。

**关联函数**

所有在 `impl` 块中定义的函数被称为 **关联函数**（*associated functions*），因为它们与 `impl` 后面命名的类型相关。我们可以定义不以 `self` 为第一参数的关联函数（因此不是方法），因为它们并不作用于一个结构体的实例。我们已经使用了一个这样的函数：在 `String` 类型上定义的 `String::from` 函数。

不是方法的关联函数经常被用作返回一个结构体新实例的构造函数。这些函数的名称通常为 `new` ，但 `new` 并不是一个关键字。例如我们可以提供一个叫做 `square` 关联函数，它接受一个维度参数并且同时作为宽和高，这样可以更轻松的创建一个正方形 `Rectangle` 而不必指定两次同样的值：

![image-20230404112300724](.\picture\image-20230404112300724.png)

关键字 `Self` 在函数的返回类型中代指在 `impl` 关键字后出现的类型，在这里是 `Rectangle`

使用结构体名和 `::` 语法来调用这个关联函数：比如 `let sq = Rectangle::square(3);`。这个函数位于结构体的命名空间中：`::` 语法用于关联函数和模块创建的命名空间。

**多个impl块**

![image-20230404112451637](.\picture\image-20230404112451637.png)

**总结**

结构体让你可以创建出在你的领域中有意义的自定义类型。通过结构体，我们可以将相关联的数据片段联系起来并命名它们，这样可以使得代码更加清晰。在 `impl` 块中，你可以定义与你的类型相关联的函数，而方法是一种相关联的函数，让你指定结构体的实例所具有的行为。

## 6 枚举和模式匹配

### 6.1 枚举的定义

**定义**

可以通过在代码中定义一个 `IpAddrKind` 枚举来表现这个概念并列出可能的 IP 地址类型，`V4` 和 `V6`。这被称为枚举的 **成员**（*variants*）：

![image-20230404112759960](.\picture\image-20230404112759960.png)

**枚举值**

可以像这样创建 `IpAddrKind` 两个不同成员的实例：

![image-20230404113005069](.\picture\image-20230404113005069.png)

注意枚举的成员位于其标识符的命名空间中，并使用两个冒号分开。这么设计的益处是现在 `IpAddrKind::V4` 和 `IpAddrKind::V6` 都是 `IpAddrKind` 类型的。例如，接着可以定义一个函数来获取任何 `IpAddrKind`：

![image-20230404113104844](.\picture\image-20230404113104844.png)

![image-20230404113214516](.\picture\image-20230404113214516.png)

示例 6-1：将 IP 地址的数据和 `IpAddrKind` 成员存储在一个 `struct` 中

我们可以使用一种更简洁的方式来表达相同的概念，仅仅使用枚举并将数据直接放进每一个枚举成员而不是将枚举作为结构体的一部分。`IpAddr` 枚举的新定义表明了 `V4` 和 `V6` 成员都关联了 `String` 值：

![image-20230404113436149](.\picture\image-20230404113436149.png)

我们直接将数据附加到枚举的每个成员上，这样就不需要一个额外的结构体了。这里也很容易看出枚举工作的另一个细节：每一个我们定义的枚举成员的名字也变成了一个构建枚举的实例的函数。也就是说，`IpAddr::V4()` 是一个获取 `String` 参数并返回 `IpAddr` 类型实例的函数调用。作为定义枚举的结果，这些构造函数会自动被定义。

用枚举替代结构体还有另一个优势：每个成员可以处理不同类型和数量的数据。IPv4 版本的 IP 地址总是含有四个值在 0 和 255 之间的数字部分。如果我们想要将 `V4` 地址存储为四个 `u8` 值而 `V6` 地址仍然表现为一个 `String`，这就不能使用结构体了。枚举则可以轻易的处理这个情况：

![image-20230404113647508](.\picture\image-20230404113647508.png)

示例 6-2：一个 `Message` 枚举，其每个成员都存储了不同数量和类型的值

这个枚举有四个含有不同类型的成员：

- `Quit` 没有关联任何数据。
- `Move` 类似结构体包含命名字段。
- `Write` 包含单独一个 `String`。
- `ChangeColor` 包含三个 `i32`。

定义一个如示例 6-2 中所示那样的有关联值的枚举的方式和定义多个不同类型的结构体的方式很相像，除了枚举不使用 `struct` 关键字以及其所有成员都被组合在一起位于 `Message` 类型下。如下这些结构体可以包含与之前枚举成员中相同的数据：



结构体和枚举还有另一个相似点：就像可以使用 `impl` 来为结构体定义方法那样，也可以在枚举上定义方法。这是一个定义于我们 `Message` 枚举上的叫做 `call` 的方法：

![image-20230404114226844](.\picture\image-20230404114226844.png)

**Option枚举和其相对于空值的优势**

这一部分会分析一个 `Option` 的案例，`Option` 是标准库定义的另一个枚举。**`Option` 类型应用广泛因为它编码了一个非常普遍的场景，即一个值要么有值要么没值。**

例如，如果请求一个非空列表的第一项，会得到一个值，如果请求一个空的列表，就什么也不会得到。从类型系统的角度来表达这个概念就意味着编译器需要检查是否处理了所有应该处理的情况，这样就可以避免在其他编程语言中非常常见的 bug。

编程语言的设计经常要考虑包含哪些功能，但考虑排除哪些功能也很重要。Rust 并没有很多其他语言中有的空值功能。**空值**（*Null* ）是一个值，它代表没有值。在有空值的语言中，变量总是这两种状态之一：空值和非空值。

空值的问题在于当你尝试像一个非空值那样使用一个空值，会出现某种形式的错误。因为空和非空的属性无处不在，非常容易出现这类错误。

然而，空值尝试表达的概念仍然是有意义的：空值是一个因为某种原因目前无效或缺失的值。

![image-20230404115032200](.\picture\image-20230404115032200.png)

`Option<T>` 枚举是如此有用以至于它甚至被包含在了 prelude 之中，你不需要将其显式引入作用域。另外，它的成员也是如此，可以不需要 `Option::` 前缀来直接使用 `Some` 和 `None`。即便如此 `Option<T>` 也仍是常规的枚举，`Some(T)` 和 `None` 仍是 `Option<T>` 的成员。

`<T>` 语法是一个我们还未讲到的 Rust 功能。它是一个泛型类型参数，第十章会更详细的讲解泛型。目前，所有你需要知道的就是 `<T>` 意味着 `Option` 枚举的 `Some` 成员可以包含任意类型的数据，同时每一个用于 `T` 位置的具体类型使得 `Option<T>` 整体作为不同的类型。这里是一些包含数字类型和字符串类型 `Option` 值的例子：

![image-20230404115144183](.\picture\image-20230404115144183.png)

`some_number` 的类型是 `Option<i32>`。`some_char` 的类型是 `Option<char>`，这（与 `some_number`）是一个不同的类型。因为我们在 `Some` 成员中指定了值，Rust 可以推断其类型。对于 `absent_number`，Rust 需要我们指定 `Option` 整体的类型，因为编译器只通过 `None` 值无法推断出 `Some` 成员保存的值的类型。这里我们告诉 Rust 希望 `absent_number` 是 `Option<i32>` 类型的。

当有一个 `Some` 值时，我们就知道存在一个值，而这个值保存在 `Some` 中。当有个 `None` 值时，在某种意义上，它跟空值具有相同的意义：并没有一个有效的值。那么，`Option<T>` 为什么就比空值要好呢？

简而言之，因为 `Option<T>` 和 `T`（这里 `T` 可以是任何类型）是不同的类型，编译器不允许像一个肯定有效的值那样使用 `Option<T>`。例如，这段代码不能编译，因为它尝试将 `Option<i8>` 与 `i8` 相加：

![image-20230404115514975](.\picture\image-20230404115514975.png)

很好！事实上，错误信息意味着 Rust 不知道该如何将 `Option<i8>` 与 `i8` 相加，因为它们的类型不同。当在 Rust 中拥有一个像 `i8` 这样类型的值时，编译器确保它总是有一个有效的值。我们可以自信使用而无需做空值检查。只有当使用 `Option<i8>`（或者任何用到的类型）的时候需要担心可能没有值，而编译器会确保我们在使用值之前处理了为空的情况。

换句话说，在对 `Option<T>` 进行运算之前必须将其转换为 `T`。通常这能帮助我们捕获到空值最常见的问题之一：假设某值不为空但实际上为空的情况。

消除了错误地假设一个非空值的风险，会让你对代码更加有信心。为了拥有一个可能为空的值，你必须要显式的将其放入对应类型的 `Option<T>` 中。接着，当使用这个值时，必须明确的处理值为空的情况。只要一个值不是 `Option<T>` 类型，你就 **可以** 安全的认定它的值不为空。这是 Rust 的一个经过深思熟虑的设计决策，来限制空值的泛滥以增加 Rust 代码的安全性。

### 6.2 match控制流结构

Rust 有一个叫做 `match` 的极为强大的控制流运算符，它允许我们将一个值与一系列的模式相比较，并根据相匹配的模式执行相应代码。模式可由字面值、变量、通配符和许多其他内容构成；[第十八章](https://kaisery.github.io/trpl-zh-cn/ch18-00-patterns.html)会涉及到所有不同种类的模式以及它们的作用。`match` 的力量来源于模式的表现力以及编译器检查，它确保了所有可能的情况都得到处理。

可以把 `match` 表达式想象成某种硬币分类器：硬币滑入有着不同大小孔洞的轨道，每一个硬币都会掉入符合它大小的孔洞。同样地，值也会通过 `match` 的每一个模式，并且在遇到第一个 “符合” 的模式时，值会进入相关联的代码块并在执行中被使用。

![image-20230404120832853](.\picture\image-20230404120832853.png)

示例 6-3：一个枚举和一个以枚举成员作为模式的 `match` 表达式

如果分支代码较短的话通常不使用大括号，正如示例 6-3 中的每个分支都只是返回一个值。如果想要在分支中运行多行代码，可以使用大括号，而分支后的逗号是可选的。例如，如下代码在每次使用`Coin::Penny` 调用时都会打印出 “Lucky penny!”，同时仍然返回代码块最后的值，`1`：

![image-20230404121205471](.\picture\image-20230404121205471.png)

**绑定值的模式**

匹配分支的另一个有用的功能是可以绑定匹配的模式的部分值。这也就是如何从枚举成员中提取值的。

作为一个例子，让我们修改枚举的一个成员来存放数据。1999 年到 2008 年间，美国在 25 美分的硬币的一侧为 50 个州的每一个都印刷了不同的设计。其他的硬币都没有这种区分州的设计，所以只有这些 25 美分硬币有特殊的价值。可以将这些信息加入我们的 `enum`，通过改变 `Quarter` 成员来包含一个 `State` 值，示例 6-4 中完成了这些修改：

```

```

![image-20230404121425562](.\picture\image-20230404121425562.png)

示例 6-4：`Quarter` 成员也存放了一个 `UsState` 值的 `Coin` 枚举

在这些代码的匹配表达式中，我们在匹配 `Coin::Quarter` 成员的分支的模式中增加了一个叫做 `state` 的变量。当匹配到 `Coin::Quarter` 时，变量 `state` 将会绑定 25 美分硬币所对应州的值。接着在那个分支的代码中使用 `state`，如下：

![image-20230404150613402](.\picture\image-20230404150613402.png)

如果调用 `value_in_cents(Coin::Quarter(UsState::Alaska))`，`coin` 将是 `Coin::Quarter(UsState::Alaska)`。当将值与每个分支相比较时，没有分支会匹配，直到遇到 `Coin::Quarter(state)`。这时，`state` 绑定的将会是值 `UsState::Alaska`。接着就可以在 `println!` 表达式中使用这个绑定了，像这样就可以获取 `Coin` 枚举的 `Quarter` 成员中内部的州的值。

**匹配Option<T>**

我们在之前的部分中使用 `Option<T>` 时，是为了从 `Some` 中取出其内部的 `T` 值；我们还可以像处理 `Coin` 枚举那样使用 `match` 处理 `Option<T>`！只不过这回比较的不再是硬币，而是 `Option<T>` 的成员，但 `match` 表达式的工作方式保持不变。

比如我们想要编写一个函数，它获取一个 `Option<i32>` ，如果其中含有一个值，将其加一。如果其中没有值，函数应该返回 `None` 值，而不尝试执行任何操作。

![image-20230404151040945](.\picture\image-20230404151040945.png)

**匹配Some(T)**

![image-20230404151550696](.\picture\image-20230404151550696.png)

**匹配是穷尽的**

![image-20230404151941635](.\picture\image-20230404151941635.png)

我们没有处理 `None` 的情况，所以这些代码会造成一个 bug。幸运的是，这是一个 Rust 知道如何处理的 bug。

**通配模式和占位符**

![image-20230404165040663](.\picture\image-20230404165040663.png)

对于前两个分支，匹配模式是字面值 `3` 和 `7`，最后一个分支则涵盖了所有其他可能的值，模式是我们命名为 `other` 的一个变量。`other` 分支的代码通过将其传递给 `move_player` 函数来使用这个变量。

即使我们没有列出 `u8` 所有可能的值，这段代码依然能够编译，因为最后一个模式将匹配所有未被特殊列出的值。这种通配模式满足了 `match` 必须被穷尽的要求。请注意，我们必须将通配分支放在最后，因为模式是按顺序匹配的。如果我们在通配分支后添加其他分支，Rust 将会警告我们，因为此后的分支永远不会被匹配到。

**Rust 还提供了一个模式，当我们不想使用通配模式获取的值时，请使用 `_` ，这是一个特殊的模式**，可以匹配任意值而不绑定到该值。这告诉 Rust 我们不会使用这个值，所以 Rust 也不会警告我们存在未使用的变量。

![image-20230404165239628](.\picture\image-20230404165239628.png)

最后，让我们再次改变游戏规则，如果你掷出 3 或 7 以外的值，你的回合将无事发生。

![image-20230404165428563](.\picture\image-20230404165428563.png)

### 6.3 if let 简介控制流

![image-20230404165958580](.\picture\image-20230404165958580.png)

如果值是 `Some`，我们希望打印出 `Some` 成员中的值，这个值被绑定到模式中的 `max` 变量里。对于 `None` 值我们不希望做任何操作。为了满足 `match` 表达式（穷尽性）的要求，必须在处理完这唯一的成员后加上 `_ => ()`，这样也要增加很多烦人的样板代码。

不过我们可以使用 `if let` 这种更短的方式编写。如下代码与示例 6-6 中的 `match` 行为一致：

![image-20230404170018765](.\picture\image-20230404170018765.png)

`if let` 语法获取通过等号分隔的一个模式和一个表达式。它的工作方式与 `match` 相同，这里的表达式对应 `match` 而模式则对应第一个分支。在这个例子中，模式是 `Some(max)`，`max` 绑定为 `Some` 中的值。接着可以在 `if let` 代码块中使用 `max` 了，就跟在对应的 `match` 分支中一样。模式不匹配时 `if let` 块中的代码不会执行。

使用 `if let` 意味着编写更少代码，更少的缩进和更少的样板代码。然而，这样会失去 `match` 强制要求的穷尽性检查。`match` 和 `if let` 之间的选择依赖特定的环境以及增加简洁度和失去穷尽性检查的权衡取舍。

换句话说，**可以认为 `if let` 是 `match` 的一个语法糖，它当值匹配某一模式时执行代码而忽略所有其他值。**

![image-20230404171001783](.\picture\image-20230404171001783.png)



![image-20230404222141671](.\picture\image-20230404222141671.png)

晚上十点半，提交最近修改的练习。

## 2023.04.05

## 7 使用包、Crate和模块管理项目



今天清明节，中午实验室开会，下午参加了学院举办的一个活动。晚上学习一些rust第七章内容。



可视化学习git：https://learngitbranching.js.org/?locale=zh_CN

### 7.1 包和crate

模块系统的第一部分，我们将介绍包和 crate。

crate 是 Rust 在编译时最小的代码单位。如果你用 `rustc` 而不是 `cargo` 来编译一个文件（第一章我们这么做过），编译器还是会将那个文件认作一个 crate。crate 可以包含模块，模块可以定义在其他文件，然后和 crate 一起编译，我们会在接下来的章节中遇到。

crate 有两种形式：二进制项和库。*二进制项* 可以被编译为可执行程序，比如一个命令行程序或者一个服务器。它们必须有一个 `main` 函数来定义当程序被执行的时候所需要做的事情。目前我们所创建的 crate 都是二进制项。

*库* 并没有 `main` 函数，它们也不会编译为可执行程序，它们提供一些诸如函数之类的东西，使其他项目也能使用这些东西。比如 [第二章](https://kaisery.github.io/trpl-zh-cn/ch02-00-guessing-game-tutorial.html#生成一个随机数) 的 `rand` crate 就提供了生成随机数的东西。大多数时间 `Rustaceans` 说的 crate 指的都是库，这与其他编程语言中 library 概念一致。

*crate root* 是一个源文件，Rust 编译器以它为起始点，并构成你的 crate 的根模块（我们将在 [“定义模块来控制作用域与私有性”](https://kaisery.github.io/trpl-zh-cn/ch07-02-defining-modules-to-control-scope-and-privacy.html) 一节深入解读）。

*包*（*package*）是提供一系列功能的一个或者多个 crate。一个包会包含一个 *Cargo.toml* 文件，阐述如何去构建这些 crate。Cargo 就是一个包含构建你代码的二进制项的包。Cargo 也包含这些二进制项所依赖的库。其他项目也能用 Cargo 库来实现与 Cargo 命令行程序一样的逻辑。

包中可以包含至多一个库 crate(library crate)。包中可以包含任意多个二进制 crate(binary crate)，但是必须至少包含一个 crate（无论是库的还是二进制的）。

7.2 定义模块来控制作用域与私有性

- **从 crate 根节点开始**: 当编译一个 crate, 编译器首先在 crate 根文件（通常，对于一个库 crate 而言是*src/lib.rs*，对于一个二进制 crate 而言是*src/main.rs*）中寻找需要被编译的代码。

- 声明模块

  : 在 crate 根文件中，你可以声明一个新模块；比如，你用

  ```
  mod garden
  ```

  声明了一个叫做

  ```
  garden
  ```

  的模块。编译器会在下列路径中寻找模块代码：

  - 内联，在大括号中，当`mod garden`后方不是一个分号而是一个大括号
  - 在文件 *src/garden.rs*
  - 在文件 *src/garden/mod.rs*

- 声明子模块

  : 在除了 crate 根节点以外的其他文件中，你可以定义子模块。比如，你可能在

  src/garden.rs

  中定义了

  ```
  mod vegetables;
  ```

  。编译器会在以父模块命名的目录中寻找子模块代码：

  - 内联，在大括号中，当`mod vegetables`后方不是一个分号而是一个大括号
  - 在文件 *src/garden/vegetables.rs*
  - 在文件 *src/garden/vegetables/mod.rs*

- **模块中的代码路径**: 一旦一个模块是你 crate 的一部分，你可以在隐私规则允许的前提下，从同一个 crate 内的任意地方，通过代码路径引用该模块的代码。举例而言，一个 garden vegetables 模块下的`Asparagus`类型可以在`crate::garden::vegetables::Asparagus`被找到。

- **私有 vs 公用**: 一个模块里的代码默认对其父模块私有。为了使一个模块公用，应当在声明时使用`pub mod`替代`mod`。为了使一个公用模块内部的成员公用，应当在声明前使用`pub`。

- **`use` 关键字**: 在一个作用域内，`use`关键字创建了一个成员的快捷方式，用来减少长路径的重复。在任何可以引用`crate::garden::vegetables::Asparagus`的作用域，你可以通过 `use crate::garden::vegetables::Asparagus;`创建一个快捷方式，然后你就可以在作用域中只写`Asparagus`来使用该类型。





















​	

















