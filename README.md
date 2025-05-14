# NJU 软件系统设计 (2025) 设计模式部分实验文档

![mkdocs](https://img.shields.io/badge/docs-mkdocs-blue.svg)
![material](https://img.shields.io/badge/theme-material-orange.svg)

本仓库为南京大学软件学院2025年春季学期"软件系统设计"课程设计模式部分的实验文档存档。

## 📌 仓库说明

- 本仓库为​​实验文档备份​​，课程结束后OJ系统将关闭
- 文档内容已做适当删改，仅保留核心部分
- 作为学习参考资料，可能不再更新维护

## 🛠️ 环境配置

### 基础环境要求

- Python 3.6+
- pip 包管理工具

### 安装依赖

```bash
pip install mkdocs mkdocs-material
```

## 🚀 快速使用

### 本地开发预览

```bash
mkdocs serve
```

访问 http://127.0.0.1:8000 查看实时更新的文档

### 简易部署

如果你想**简单地**在服务器上部署一个网站，可以使用下面的命令

```bash
nohup mkdocs serve --dev-addr=0.0.0.0:8000 > output.log 2>&1 &
```

## 🗂 项目结构

    mkdocs.yml    # 配置文件
    docs/         # 文档目录
        index.md  # 文档首页
        ...       # 其他Markdown文档和资源

