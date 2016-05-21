# 简介
这份工程是《初等数学个人笔记》一书的LaTeX源代码。此书是我作为一名热爱数学的程序员几年期间积累的初等数学笔记，它的pdf文件准备在百度网盘上公开，届时此处会贴上相应链接。

# 编译
1. LaTeX环境。首先请确保已经安装LaTeX系统，比如texlive。其次本书源代码使用了CTeX文档类，因此请确保CTeX宏包已经正确安装。
2. 下载源代码到本地。
3. 编译
    > cd elementary-math-book
    > xelatex book.tex
    > xelatex book.tex

你没看错，需要编译两次，这能使LaTeX生成正确的引用与目录。编译之后目录下会生成book.pdf电子书，此即《初等数学个人笔记》一书。
