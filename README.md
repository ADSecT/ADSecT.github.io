# ADSecT

本仓库是基于Sphinx + Read the Docs + Github搭建的文档管理仓库，记录本人在Autonomous Driving Security领域研究的一些资料。



**Read the Docs：** 是一个基于 Sphinx 的免费文档托管项目。该项目在 2010 年由 Eric Holscher、Bobby Grace 和 Charles Leifer 共同发起。2011年3月，Python 软件基金会曾给 Read the Docs 项目资助 840 美元，作为一年的服务器托管费用。此后，受到越来越多开源社区和开发者的关注，2017年11月，Linux Mint 宣布将所有文档转移到 Read the Docs，目前 Read the Docs 已经托管了超过 90000 份文档。

- Read the Docs 网站：https://readthedocs.org/



**Sphinx：** 是一个基于 Python 的文档生成项目。最早只是用来生成 Python 的项目文档，使用 reStructuredText 格式。但随着 Sphinx 项目的逐渐完善，目前已发展成为一个大众可用的框架，很多非 Python 的项目也采用 Sphinx 作为文档写作工具，甚至完全可以用 Sphinx 来写书。

- Sphinx 网站：http://sphinx-doc.org/
- Sphinx 使用手册：https://zh-sphinx-doc.readthedocs.io/en/latest/index.html



## 使用说明

安装最新版本的 Sphinx 及依赖。

```shell
pip3 install -U Sphinx
```

为了完成本示例，还需要安装以下软件包。

```shell
pip3 install sphinx-autobuild
pip3 install sphinx_rtd_theme
pip3 install recommonmark
pip3 install sphinx_markdown_tables
```

本地编译

```shell
sphinx-autobuild source build/html
```

