# JavaFX 文档项目
JavaFX 文档项目旨在从网络上收集重要的 JavaFX 信息，并在作者许可的情况下将其整理成一个单一的资料来源，以形成一本有凝聚力的书。

该项目由 [Jonathan Giles](http://www.jonathangiles.net) 发起，但任何人都可以做出贡献。任何问题、疑虑或反馈都应首先通过 [E-mail](mailto:jonathan@jonathangiles.net) 发送给 Jonathan。

## 阅读文档
文档可在线阅读，并将始终展示最新的编辑。目前有两种阅读形式：
 

- 通过 [单页网站](https://fxdocs.github.io/docs/html5/index.html) 阅读
- 通过 [单个 PDF 文件](https://fxdocs.github.io/docs/pdf/index.pdf) 阅读。


## 构建流程
该文档是用 AsciiDoc 编写的。每次提交到此 GitHub 仓库时，都会运行一次构建流程，从而生成 [HTML](https://fxdocs.github.io/docs/html5/index.html) 与 [单个 PDF 文件](https://fxdocs.github.io/docs/pdf/index.pdf) 的新内容。JavaFX 文档项目使用 GitHub Actions 来执行 AsciiDoc 源代码的持续集成。当前构建状态为：

![Build Docs](https://github.com/FXDocs/docs/workflows/Build%20Docs/badge.svg)

手动构建：

```
./gradlew run
```

这将会在 `build/docs/` 目录中生成 `html5` 与 `pdf` 目录。
