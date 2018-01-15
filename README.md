# Julia中文文档

[鸣谢早期的部分翻译工作](#juliacn)；会校审这些已有的翻译稿，将电子版格式从reStructuredText改为Markdown，放弃Sphinx、改用某种JS实现的Markdown解析器。

本项目原则是“宁缺毋滥”，提交的翻译稿严格跟[JuliaDoc](https://github.com/JuliaLang/JuliaDoc)的master分支相应的部分保持语义一致。

## 文件布局
暂时保持如下结构。

    manual/         Julia手册
    stdlib/         Julia标准库文档
	packages/       扩展包文档
	conf.py         Sphinx配置文件
	note/           暂时存放一些笔记之类的东西，将来很有可能移走

## TODO
亟待核实并翻译之。

    ./manual/
			control-flow.rst
            types.rst
            metaprogramming.rst
            networking-and-streams.rst
            parallel-computing.rst
            calling-c-and-fortran-code.rst
            embedding.rst
            packages.rst
            performance-tips.rst
            style-guide.rst
            faq.rst
            noteworthy-differences.rst

---
[截至commit-ddbbb719ac09289719219605ff316fe8fb93cc23，之后的完全由JulialangOrgCN（朱华社区）组织翻译。](id: juliacn)
