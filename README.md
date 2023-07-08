# 编辑

本文档基于mkdocs编写，如果你需要继续编辑并且预览效果，你需要以下步骤：

1. 安装Python
2. 安装mkdocs
3. git clone 本文档
4. 使用你喜欢的编辑器编辑

其他相关问题可以在下面找到。

## 安装Python

你可以选择：

1. [Python官网](https://www.python.org/)下载
2. 使用 [anaconda](https://www.anaconda.com/download/)
    + 嫌anaconda臃肿可以使用miniconda，可以从[清华源](https://mirrors.tuna.tsinghua.edu.cn/anaconda/miniconda/)下载

## 恢复Python依赖

```bash
pip install -r requirements.txt
```

## 导出Python依赖

```bash
pip freeze > requirements.txt
```
保留 `requirements.txt` 里面的 `mkdocs` 和 `mkdocs-bootswatch` 两个依赖，其他删除即可。截至编写本文档时 `requirements.txt` 的内容如下：

```text
mkdocs==1.4.3
mkdocs-bootswatch==1.1
```
你的 `requirements.txt` 文件中唯一可变的是 `==` 后的数字（即版本号），其他多余内容均需要删除。
