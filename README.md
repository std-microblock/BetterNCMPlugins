# BetterNCMPlugins
BetterNCM的官方插件库

# 主题
## 安装方式
1. 在网易云内点击设置，滑到最下面，点击`打开配置文件夹`，将主题文件夹下的内容全部放入`stylesheets`文件夹
2. 打开`stylesheets`文件夹下的`all.json`，将主题设置JSON追加在最后

如安装`Microrange`主题：
```json
[
    {
        "file":"block.css",
        "enabled":true
    }
]
```
修改为
```json
[
    {
        "file":"block.css",
        "enabled":true
    }
    ,{
    "name":"Microrange White",
    "file":"microrange.css",
    "enabled":false
    } 
]
```
## 启用主题
1. 在网易云内点击设置，滑到最下面，点击编辑CSS设置
2. 将主题下的`enabled`值改为true

## 主题列表

| 主题名 | 作者 | 预览图 |
| -- | -- | -- |
| [Microrange](Stylesheets/Theme-Microrange) | [MicroBlock](https://github.com/MicroCBer) | ![](Stylesheets/Theme-Microrange/black.png) |
| [Unbounded](Stylesheets/Theme-Unbounded) | [MicroBlock](https://github.com/MicroCBer) | ![](Stylesheets/Theme-Unbounded/main.png) |
| [Unbounded-Unblur](Stylesheets/Theme-Unbounded-Unblur) | [Skykey](https://github.com/skykeyjoker) | <img src="Stylesheets/Theme-Unbounded-Unblur/main.png" style="zoom:83%;" /> |
