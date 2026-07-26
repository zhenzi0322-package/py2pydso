<p align="center">
  <h1>py2pydso</h1>
  <a href="https://pypi.org/project/py2pydso/"><img src="https://img.shields.io/pypi/v/py2pydso.svg" alt="PyPI version"></a>
  <a href="https://pypi.org/project/py2pydso/"><img src="https://img.shields.io/badge/Python-3.8~3.14-3776AB?logo=python&logoColor=white" alt="Python"></a>
  <a href="https://github.com/zhenzi0322-package/py2pydso/blob/master/LICENSE"><img src="https://img.shields.io/pypi/l/py2pydso.svg" alt="License"></a>
</p>

> 将`Python`源文件编译为`.pyd/.so`原生扩展，以便分发和保护源代码。

---

## ✨ Features

- 🔒 **源码保护** — 将 `.py` 编译为 `.pyd`/`.so` 原生扩展，不暴露源码
- 📦 **三种编译模式** — 单文件 / 模块目录 / 完整 wheel 包
- 🗂️ **智能过滤** — 自动保留 `__init__.py` 等元文件，支持自定义排除
- 📝 **类型提示** — 自动生成 `.pyi` 存根文件，保留 IDE 补全体验
- 🌍 **跨平台** — `Windows` (`.pyd`) / `Linux` / `macOS` (`.so`) 全支持

---

## 安装

```bash
pip install py2pydso
```

安装完成后，可通过以下命令验证：

```bash
python -m py2pydso --help
```