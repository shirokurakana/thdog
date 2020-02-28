# 东方狗更新日志

![thdog](https://image.moeloli.cc/images/2020/01/12/logo256.png)

## 1.0.4

- 修复了wiki内部分文字不显示的问题

- 修复了微博部分样式显示不正确的问题

- 添加了快速查看东方Project超话的入口

- 修复了一处显示问题

## 1.0.3

- 增加了随机东方图的功能

- 修改应用图标为正式版图标

- 修改搜索栏为圆角风格

- 优化了清除缓存的提醒

- 在「关于」中放置官网链接

- 修复了两处显示bug

## 1.0.2

- 更新应用API为25（首次安装应用不会再提示版本过低了）

- 增加了清除缓存的功能（页面元素显示不正常或占用空间过大时可以尝试此功能）

- 增加了查看更新日志的功能

- 增加了一处为THBWiki捐款的入口

- 修复了一处bug

## 1.0.1

- 解决了主页面不能返回的问题（但代价是砍掉了确认退出的功能）

## 1.0.0

- 重新设计应用logo

- 更改了应用图标、开屏图片和侧滑栏顶部图片，分辨率更高，更加美观

- 完成了侧边栏的功能

- 开始使用更合理的版本号

- 去除了一些不必要的权限，现有权限6项：
  - ACCESS\_WIFI\_STATE  允许程序访问Wi-Fi网络信息
  - ACCESS\_WIFI\_STATE 允许程序访问网络信息
  - INTERNET 允许程序打开网络套接字
  - WRITE\_EXTERNAL\_STORAGE 允许程序写入SD卡（用于保存图片，图片保存路径：`/storage/emulated/0/Pictures/东方狗/`，有些时候系统不会将此目录的图片添加到图库，会导致相册、QQ等软件无法找到保存的图片，原因未知，可以尝试手动将这些文件移出该目录）
  - READ\_EXTERNAL\_STORAGE 允许程序访问SD卡（用于在识图功能中上传手机图片）
  - ACCESS\_MEDIA\_LOCATION 允许程序获取图片的地理位置信息（去不掉，去掉了会重新开启）
