# 主题
主题使用前请确保`cssLoader`插件处于打开状态
## Microrange
作者：*MicroBlock*
![Black](black.png)
![White](white.png)
## 安装
在网易云内点击设置，滑到最下面，点击打开配置文件夹，将`microrange.css`，`microrange-black.css`放入stylesheets文件夹
#### Stylesheet JSON
黑色版（配合“酷炫黑”主题使用）
```json
,{
    "name":"Microrange Black",
    "file":"microrange-black.css",
    "enabled":false
}
```

白色版
```json
,{
    "name":"Microrange White",
    "file":"microrange.css",
    "enabled":false
}
```

## 自定义
自定义背景图：更改对应css文件的第二行为
```css
    background: url("图片地址");
```
