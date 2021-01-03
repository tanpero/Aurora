# Aurora: Modern C++ Package Manager

---

## 简介

Aurora 是一个 Modern C++ 包管理器，尝试提供易于使用和可扩展的 Modern C++ 包管理机制。它具有以下基础特性：

- 基于源码而非二进制文件进行包的发行和下载。
- 使语义化版本管理贯穿于包的生命周期；
- 将包的构建细节封装起来，任务交给具体的构建系统，再根据不同构建系统抽象出一套面向用户的、统一的构建原语。
- 利用成熟的托管平台提供去中心化的包仓库，既提供官方的包仓库，也支持从第三方包管理器和个人仓库中安装包。
- 快速浏览各类信息以做出决策，例如用模糊名称搜索包、查看包环境信息、查看包信息等。
- 执行预定的用户脚本。
- 集成一些辅助功能以让开发过程中的一些琐碎过程更为高效，例如：
  - 分析包的依赖情况及其开源协议;
  - 根据需求自动建立目录结构、构建系统文件模板和文档模板；
  - 向包的作者提出意见和缺陷报告；
  - ……以及更多。
  
## 安装

```bash
npm install --global aurora
```

## 支持平台

- [x] Windows (x86, x64)
- [ ] MacOS (i386, x86_64, arm64)
- [ ] Linux (i386, x86_64, cross-toolchains ..)
- [ ] *BSD (i386, x86_64)
- [ ] Android (x86, x86_64, armeabi, armeabi-v7a, arm64-v8a)
- [ ] iOS (armv7, armv7s, arm64, i386, x86_64)
- [ ] MSYS (i386, x86_64)
- [ ] MinGW (i386, x86_64, arm, arm64)
- [ ] Cross Toolchains

## 支持的包管理器仓库

- [官方仓库：Aurora Community](https://github.com/Aurora-Community/)
- [用户自建仓库](https://github.com/tanpero/aurora-node/wiki/private-package/)
- [ ] Conan (conan::openssl/1.1.1g)
- [ ] Vcpkg (vcpkg:ffmpeg)
- [ ] Homebrew/Linuxbrew (brew::pcre2/libpcre2-8)
- [ ] Pacman on archlinux/msys2 (pacman::libcurl)
- [ ] Clib (clib::clibs/bytes@0.0.4)
- [ ] Dub (dub::log 0.4.3)
