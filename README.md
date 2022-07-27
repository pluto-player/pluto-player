# Pluto Player

## v1.0.3

支持 DropBox 账号登录
支持 播放本地视频
新TV播放器UI
添加部分按钮键盘事件
支持非公开配置接口 支持401返回 弹出用户名密码登录
直播独立桌面快捷方式
驱动器/直播快捷菜单


## v1.0.2

WebDAV 兼容 [aList](https://github.com/alist-org/alist)
当贝播放器支持
收藏按钮 / 倒序快捷操作
多语言支持
嗅探支持外挂脚本
添加 SurfaceView Plus

## v1.0.1

迅雷库已剔除,不支持磁力!!!

**播放器**

添加锁定功能
支持画中画模式
添加按键响应
片头片尾设置 支持触屏长按 支持重置 支持遥控上下键快速加减
显示/关闭时间
显示/关闭网速
手机/电视模式切换
非播放页自动息屏

**应用**
首页快捷切换源 手机点击源名称 电视点击菜单键
自定义壁纸
自定义直播源
自定义数据保存位置
首页自定义按钮显示
触屏手势优化
多jar支持

```
{"key":"***","name":"***","api":"***","type":3,"filterable":1,"quickSearch":1,"searchable":1,"plugin":"http://****/*.jar"},
```

网盘部分 内置了 WebDAV
开启方式

```
"drives": [{"server":"","userName":"","password":"","type":"webdav"}]
```

部分BUG修复
