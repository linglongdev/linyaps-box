# 说明

该仓库用于在 build.deepin.com 构建 linyaps-box

## 项目

latest 每日构建

https://build.deepin.com/project/show/linglong:CI:latest

最新 release 构建

https://build.deepin.com/project/show/linglong:CI:release

## 分支说明

分为 latest 和 release，latest 会每天自动更新，release 每周六自动使用最新的 release/xx 更新

### obs_latest

用于构建非 deepin/uos 发行版的 linyaps-box

代码来自 https://github.com/OpenAtom-Linyaps/linyaps-box master 分支

rpm 和 debian 目录来自 https://github.com/deepin-community/linyaps-box master 分支，删除 patches 目录

### obs_latest_deepin

用于构建适用于 deepin/uos 发行版的 linyaps-box

代码来自 https://github.com/OpenAtom-Linyaps/linyaps-box master 分支

rpm 和 debian 目录来自 https://github.com/deepin-community/linyaps-box master 分支

### obs_release

代码来自 https://github.com/deepin-community/linyaps-box 最新的 release/xx 分支，删除 patches 目录

### obs_release_deepin

代码来自 https://github.com/deepin-community/linyaps-box 最新的 release/xx 分支
