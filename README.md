An Infinite Descent into Pure Mathematics 中文翻译
=========================================

本 Git 仓库包含 _An Infinite Descent into Pure Mathematics_ 简体中文译本的 TeX 源文件。本书原作者为 Clive Newstead。

本书的官网在[这里](https://infinitedescent.xyz/)。

## 浏览源代码

要想编译源文件，你需要在你的电脑上安装 LaTeX ，或者使用基于浏览器的 LaTeX 编辑器，例如 [Overleaf](https://www.overleaf.com/)，使用 pdfLaTeX 编译器。

根文档为 `book.tex`，它会调用所有其他所需的文件来编译文档。

`book` 文件夹包含本书的大部分实际内容, 并且浏览相当容易。例如，想要找到第 5 章 (_Relations_) 第 5.2 节（_Equivalence relations_）的源文件，只需去到 `book/ch05-relations/s2-equivalence-relations.tex` 即可。

`book/includes` 文件夹包含与调用包、格式化、自定义命令和环境等相关的所有代码。

## 修改与改编

本 TeX 源代码在 [Creative Commons Attribution–ShareAlike 4.0 International licence](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0) 许可下发布。任何衍生作品都必须在相同的许可下发布，并且必须清楚注明 Clive Newstead 为衍生作品所基于的原始作品的创作者。

为确保符合 CC BY-SA 4.0 许可，如果您想修改或改编 TeX 源文件供您自己使用，请将 `book.tex` 文件中的 `\adaptername` 和 `\adapteremail` 命令更改为您的姓名和电子邮件地址。这将自动处理所有必要的属性，并在标题页和版权页上引用您作为改编者。



