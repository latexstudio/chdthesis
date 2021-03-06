# 长安大学研究生学位论文 LaTeX 模板

本模板基于chinathesis https://github.com/latexstudio/ChinaThesis 项目二次开发，感谢zepinglee同学。

包含硕士和博士两个选项，本科模板与研究生格式相差较大，可以使用我之前写的模板https://github.com/xiaoleeza/chdpaper 。

使用方法与chinathesis基本一致，下面贴出原贴使用说明：

本项目是国内高校学位论文 LaTeX 模板的一个编写框架，
包括模板代码、注释、文档，示例论文，以及用于维护模板的持续集成和单元测试。
该框架针对国内高校 LaTeX 模板的普遍需求提供了指南，并尽可能使格式与内容分离，
旨在帮助编写高质量的中文模板，也可供已有模板进行参考。

主要特性：
- 支持跨平台使用，兼容最新的 TeX Live, MacTeX 和 MikTeX 发行版，
  并向后兼容到 2016 年的版本
- 不支持已经过时的 CTeX 套装
- 数学符号遵循国内的排版习惯
- 参考文献格式符合 GB/T 7714
- 单元测试（l3build）
- 持续集成（travis-ci）

![](./githubimg/doctor.jpg)
![](./githubimg/master.jpg)

## 使用模板

模板使用说明文档 `chinathesis.pdf`

编译论文 `main.pdf`：
```
latexmk -xelatex main.tex
```

清理论文编译过程中的临时文件：
```
latexmk -c main.tex
```

以上编译过程也可以用 `make` 工具：
```
make            # 编译生成论文 main.pdf
make clean      # 删除编译过程中生成的临时文件
```



#### 免责声明 

1. 本模板的发布遵守 LATEX Project Public License，使用前请认真阅读协议内容 

2. 本模板创立参照官方严格的论文写作手册，并同时参照硕士 / 博士学位论文doc文档对比修改 

3. 本模板创立参照官方严格的论文写作手册，并同时参照硕士 / 博士学位论文doc文档对比修改 

4. 长安大学对论文写作提供写作指南与官方doc模板，本模板的出发点是方便大家使用专业的高效的论文书写工具，其重点在于注重排版质量、命令规范、使用方便、更新及时，符合论文撰写说明。
   但任何由于使用本模板而引起的论文格式审查问题均与本模板作者无关。 

5. 欢迎提出修改意见。
6. 本声明摘自nudtpaper-2.2.pdf。
