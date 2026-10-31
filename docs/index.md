# 编译工程

!!! Info "说明"

    本课程主页为 2026 秋季学期徐伟老师班《编译工程》课程主页。

<hr class="hr-my" data-content="(●′∀｀●) 我是分隔线 (●′∀｀●)">

## 课程简介

本课程重点围绕编译器优化设计，强调适用于当代计算机（多核及嵌入式处理器）的代码生成与优化技术的一般原理和基本实现方法。本课程包括编译器概述、代码生成、并行编译器与依赖性分析、机器无关优化、指令级并行编译、并行性与局部性优化等。本课程将借助开源的编译器基础设施软件，让学生实习有关的优化设计技术。

## 课程信息

### 上课时间与地点

    时间：2~16 周，星期四（3、4、5 节）
    地点：高新校区 G2-B502

### 联系方式

教师

- 主讲教师：徐伟 （<xuweihf@ustc.edu.cn>）

助教

- 肖同欢（<tonghuanxiao@mail.ustc.edu.cn>）
- 储李节（<cljjjkk@mail.ustc.edu.cn>）

其它

- QQ 群：924052437

## 公告

- 2026-10-29：[Lab1](lab1/index.md) 已发布，实验时间：**2026 年 10 月 29 日 — 2026 年 11 月 11 日 23:59**
- 2026-09-10：[Lab0](lab0/index.md) 已发布，Deadline：**2026 年 10 月 25 日 23:59**
<!--
- 2025-10-16：[Lab1](lab1/index.md) 已发布，Deadline：**2025 年 11 月 3 日**
- 2025-10-30: [lab2](lab2/index.md) 已发布，Deadline: **2025 年 11 月 23 日**
-->

## 教学课件

| **标题** | **课件** |
| :----: | :----: |
| 编译工程导论 | [Lecture1（PDF）](ppt/Lecture1-Intro-v2.pdf) |
| 词法分析 | [Lecture2（PDF）](ppt/Lecture2-Lexical-analysis.pdf) |
| 语法分析（1） | [Lecture3（PDF）](ppt/Lecture3-Parser-part1.pdf) |
| 语法分析（2） | [Lecture4（PDF）](ppt/Lecture4-Parser-part2.pdf) |
| 语法分析（3） | [Lecture5（PDF）](ppt/Lecture5-Parser-part3.pdf) |
| 语法分析（4） | [Lecture6（PDF）](ppt/Lecture6-Parser-part4.pdf) |
| 语法分析（5） | [Lecture7（PDF）](ppt/Lecture7-Parser-part5.pdf) |
| 语法分析（6） | [Lecture8（PDF）](ppt/Lecture8-Parser-part6.pdf) |
| 语法分析（7） | [Lecture9（PDF）](ppt/Lecture9-Parser-part7.pdf) |
| Lab0 环境搭建与 Debug | [Lecture10（PDF）](ppt/Lecture10-Lab0%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA%E5%92%8Cdebug.pdf) |
| 摩尔线程环境搭建 | [Lecture11（PDF）](ppt/Lecture11-%E6%91%A9%E5%B0%94%E7%BA%BF%E7%A8%8B%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA%281%29.pdf) |
| Lab1 实验讲解 | [Lecture12（PDF）](ppt/Lecture12-lab1.pdf) |
| 中间代码表示 | [Lecture13（PDF）](ppt/Lecture13-IR.pdf) |
| 机器无关代码优化（1） | [Lecture14（PDF）](ppt/Lecture14-IR%20Opt-part1-v2.pdf) |
| 机器无关代码优化（2） | [Lecture15（PDF）](ppt/Lecture15-IR%20Opt-part2-v2.pdf) |
| 机器无关代码优化（3） | [Lecture16（PDF）](ppt/Lecture16-IR%20Opt-part3-v2%281%29.pdf) |
| 机器无关代码优化（4）：Mem2Reg | [Lecture17（PDF）](ppt/Lecture17-IR%20Opt-part4-Mem2Reg.pdf) |
| Lab2：IR 生成 | [Lecture18（PDF）](ppt/Lecture18-lab2-irgen.pdf) |

## 参考资料

### 教材和参考书

- <span id="textbook"></span>李诚、徐伟、张昱，现代编译器设计与实现，高等教育出版社，2026
- 陈意云、张昱，编译原理（第 3 版），高等教育出版社，2016
- 李诚、徐伟，电子教材，[https://abooks.hep.com.cn/188243](https://abooks.hep.com.cn/188243)
- A. V. Aho, M. S. Lam, R. Sethi, and J. D. Ullman 著，赵建华等译，编译原理，机械工业出版社，2017

### 实验视频

- B站视频：[https://www.bilibili.com/video/BV1D7421N7c4](https://www.bilibili.com/video/BV1D7421N7c4)

### 其他资料

- Stanford 课程主页：[http://web.stanford.edu/class/cs143/](http://web.stanford.edu/class/cs143/)
- MIT 课程主页：[http://6.035.scripts.mit.edu/fa18/](http://6.035.scripts.mit.edu/fa18/)

## 如何使用本文档？

### 关于提示框

为了便于标识，我们在文档中提供了若干提示框。它们有着不同的形式与作用。例如：

!!! Note "一般的提示框长这样"

    里面是这样的文字。

??? Question "有的提示框默认是折叠的，需要点击才能展开"

    然后看到里面的内容。

???+ Success "有的提示框则是默认展开的"

    如果觉得碍事可以点击折叠。

!!! Example "大家可以在后续的文档中接触到它们。"

### 关于搜索

你可以在右上角搜索框中输入想要查询的关键词，文档会给出对应的查询结果与跳转链接。

???+ Note "Tips"

    如果在阅读文档时发现有自己不清楚的知识点，可以先用搜索框查询其是否在先前的文档中出现过。

<!-- <hr class="hr-my" data-content="(●′∀｀●) 我是分隔线 (●′∀｀●)">


???+ Bug "评论系统"

    由于主页上的评论系统映射可能出现问题，以防万一，我们在这里进行一些补充。

    除了上面介绍的内容，本学期的实验文档我们还额外添加了评论系统。大家可以在各个界面下方找到类似的评论栏，登录自己的 GitHub 账号即可发表相应的评论。

    <strong>怎么使用？</strong>

    评论系统的输入采用 Markdown 格式。如果你之前没有用过 Markdown，可以简单地将其当做普通文本（txt）格式，直接输入文字并点击评论即可。如果你对 Markdown 语法有所了解，可以使用 **加粗**、 *斜体* 、句内的 `code block` 等特殊格式，以及相应的标题结构。

    除了留下自己的疑问，大家也可以解答其他同学的疑问。这是一个相互交流、相互合作的平台。我们鼓励合理范围内的讨论与思考~

    <strong>其他方式</strong>

    评论系统实际上是抓取了[这个仓库](https://github.com/USTC-Compiler-2024/Compiler-Comments)下讨论区的内容，所有的评论也会发布在这里。大家可以访问上面的仓库进行阅读。

    如果你没有或者无法登录 GitHub 账号也没关系。除了文档下方的评论系统，在课程群中大家也可以提出自己的问题，我们将统一进行解答。

    欢迎大家在评论系统里畅所欲言！ -->
