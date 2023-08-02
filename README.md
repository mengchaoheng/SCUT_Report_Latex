# 华南理工大学硕/博士课程论文LaTeX模板

本项目始于2023年，可用于撰写华南理工大学硕/博士课程论文。模版参考了[maoruimas](https://www.cnblogs.com/maoruimas/p/12774996.html)。

## 快速使用：

编写自己的body.tex文件，编译main.tex即可.

详情可参考学位论文模版以及ctex文档。硕士课程论文去掉英文题目/摘要页即最后一页，博士课程论文记得修改该页的页码。封面（以及博士课程论文的最后一页）使用doc文件另存为cover.pdf后，在main.tex调用，编译main.tex即可生成论文pdf文件：main.pdf

编译之前首先安装[texlive](https://www.tug.org/texlive/)，找到对应系统（Linux，win，macOS）的版本。注意macOS是MacTeX。

编译有二种方法：

1.使用VSCode。设置参考`settings.json`，使用方法详情参考学位论文[讨论区](https://github.com/mengchaoheng/SCUT_thesis/discussions)。点击XeLaTeX选项编译。

2.使用TeXstudio，首次编译建议从主文件`main.tex`开始编译，首先在`TeXstudio的Options->Configure TeXstudio->build`中，编译器(Dufault Compiler)选择`XeLaTeX`，默认文献工具(Default Bibliography Tool)选`Biber`。

