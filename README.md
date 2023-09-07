# 华南理工大学研究生学位（毕业）论文开题报告LaTeX模板

模版参考了华南理工大学硕/博士课程论文，只是加了个框。然后前几页和后几页的表格直接从word生成的PDF获取，`\includepdf`属于懒人神器了。

## 快速使用：

1.先填好cover.docx，然后生成PDF，然后

2.编写自己的body.tex文件，编译main.tex即可。

3.记得修改cover.docx后几页的页码，取决于main.tex写了几页，重新生成PDF，再编译一次，这样页码就接上了。


编译之前首先安装[texlive](https://www.tug.org/texlive/)，找到对应系统（Linux，win，macOS）的版本。注意macOS是MacTeX。

编译有二种方法：

1.使用VSCode。设置参考`settings.json`，使用方法详情参考学位论文[讨论区](https://github.com/mengchaoheng/SCUT_thesis/discussions)。点击XeLaTeX选项编译。

2.使用TeXstudio，首次编译建议从主文件`main.tex`开始编译，首先在`TeXstudio的Options->Configure TeXstudio->build`中，编译器(Dufault Compiler)选择`XeLaTeX`，默认文献工具(Default Bibliography Tool)选`Biber`。

