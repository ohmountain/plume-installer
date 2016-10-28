# PLUME-INSTALLER
PLUME-INSTALL 是一个跨平台、用于快速安装 [`plume`](https://github.com/zhangbaitong/plume) 的工具。使用**plume-install**需要安装**git**和**composer**,并且保证他们在环境变量内；windows下需要安装vs2015运行时

## 编译
```bash
cargo build --release
```

windows 需要安装 Visual Studio 2013 或者 Visual Studio 2015。

## 用法
```
plume-install new $project_name $version
```
version 目前支持 1 和 2，分别安装 plume1 和 plume2。由于墙的原因，**安装依赖**可能会很慢，可以`ctrl`+`c`后手动`composer install`。