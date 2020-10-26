# openwrt-packages [![liuran001](https://img.shields.io/badge/Fork-liuran001-blue.svg?style=flat&logo=appveyor)](https://github.com/liuran001) 
国内常用OpenWrt软件包源码合集，每天自动更新


这里luci软件主要是18.06版本用的


现在可以使用git pull来更新了


## 食用方式（18.06）：
`还是建议按需取用，不然碰到依赖问题不太好解决`
1. 先cd进package目录，然后执行
```bash
 git clone https://github.com/OpenWrt-Actions/OpenWrt-Packages
```
2. 或者添加下面代码到feeds.conf.default文件
```bash
 src-git OpenWrt-packages https://github.com/OpenWrt-Actions/OpenWrt-Packages
```
3. 先cd进package目录，然后执行
```bash
 svn co https://github.com/OpenWrt-Actions/OpenWrt-Packages/branches/packages
```

## 不要为了下载而Fork这个项目，而且你Fork了不修改是不能自动拉取源码并推送的
`Actions页面报错是正常的，因为只有上游有更新时才能成功上传`
