# 哈工大《离散数学引论》课本习题答案补充

## 前言

《离散数学引论》是哈尔滨工业大学大一课程 **集合论和图论(HIT-CS31107)** 的配套教材。

考虑到此教材出版时间久远，内容更新缓慢，尤其是课后习题部分错漏部分迟迟不做出修订，部分题目官方也未曾提供参考答案，因此有理由相信，不只是我们对一份完整而正确的《离散数学引论》课后习题参考答案存在需求。这也是创立本项目的原因。

本人将在此不定期上传对于本人来说难或不难、会写或不会写，但在官方提供的参考答案中存在错误、或未提供参考答案的题目及其非官方解析。

## 使用方法

本项目提供的答案使用LaTex美化，并使用KaTex渲染器渲染。由于Github网页端不支持Markdown扩展语法，这意味着在线阅读的体验不佳。如需查看美化后的答案，请将项目`clone`至本地并使用相关编辑器查看。更多内容请查看 [贡献规则 | 先决条件](#先决条件) 以及 [请参见](#请参见) 。

具体来说，你可以直接下载本项目的[源文件](https://github.com/vonbrank/hit-introduction-to-discrete-mathematics/archive/refs/heads/master.zip)，或者：

```bash
git clone git@github.com:vonbrank/introduction-to-discrete-mathematics.git
```

并使用[Typora](https://www.typora.io/)或[vscode](https://code.visualstudio.com/)等软件查看。

## 参考答案目录

+ [第二章 映射](./src/chapter-02)

  + [2.3 映射的一般性质](./src/chapter-02/2.3.md)

+ [第六章 图的基本概念](./src/chapter-06)

  + [6.3 路、圈、连通图](./src/chapter-06/6.3.md)

## 贡献规则

如果你认同项目创立者的观点，并希望贡献本项目，可以参考此处的贡献规则，贡献你的答案。

### 先决条件

#### Git / Github 先决条件

如你所见，这是一个Github项目，显然你需要学习使用Git/Github才能执行代码提交工作，为本项目提交贡献。

更重要的是，如果你能看到这里，并对这段文字感兴趣，说明不论不论你身处哪个大类，将来选择哪个专业，熟练使用git等版本控制系统对于未来的学习和工作是必不可少的。

如果你第一次听说git，本人尤其推荐[这套教程](https://www.liaoxuefeng.com/wiki/896043488029600)。~~顺便一说这里的Python/Java/JavaScript教程也很不错。~~

#### Markdown 先决条件

Markdown 是一个 Web 上使用的文本到HTML的转换工具，可以通过简单、易读易写的文本格式生成结构化的HTML文档。目前 github、Stackoverflow 等网站均支持这种格式。

这是个Github项目，当然要使用Markdown排版。

更多关于Markdown的说明 [请参见](#请参见) 。

#### LaTeX 先决条件

LaTeX是一套排版系统，尤其擅长生成复杂的数学公式，支持扩展语法的Markdown编辑器如Typora，Visual Studio Code等，可以直接编辑并渲染LaTex公式。

本项目提供的答案使用LaTex美化，并使用KaTex渲染器渲染。因此你也需要在KaTex支持的LaTex语法范围内编写，美化并贡献你的答案。

在Markdown中添加LaTex代码非常简单，只需要在Markdown中直接输入LaTex代码，然后在两侧添加`$`即可，如：

```markdown
$x^2 - 1 = 0$
```

由于Katex渲染器只支持LaTex部分语法（尽管如此，其渲染速度通常是MathJax的上百倍），所以请在KaTex支持的语法范围内编写公式。

更多关于Latex/KaTex的说明 [请参见](#请参见) 。 

### 参考答案格式

#### 答案组成

#### 排版

#### LaTex美化

### 错误解析反馈

因为本人太菜了，贡献本项目的大佬们也可能存在疏漏，所以如果你在查看参考答案的过程中发现了纰漏，请提交issue，便于我们进行修正。

## 请参见

+ git入门教程： https://www.liaoxuefeng.com/wiki/896043488029600
+ Markdown语法说明： https://www.markdown.cn/
+ KaTex官方参考手册： https://katex.org/docs/supported.html
+ vscode下的Markdown工作模式 https://zhuanlan.zhihu.com/p/56943330