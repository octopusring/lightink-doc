# 清墨常见问题 FAQ

### 本地阅读器是什么? 

本地电子书阅读器是用于导入已经下载好的图书的, 不支持书源. 

### 我怎么看我想看的书?

可以自己在百度/谷歌/必应/小红书/公众号等自行搜索, 下载后导入清墨.

### 小说怎么导入?

点击右上角 + 号, 可以选择本地文件, 或者自己网盘中的图书导入.


### 清墨的图书文件存储

在 Android 中，每个应用都有自己独立的专属文件夹，这个独立空间就叫做 应用沙箱（App Sandbox）。

#### 沙箱的特点：

1. 只有该应用本身能访问自己的文件
2. 其他应用无法读取或修改里面的内容
3. 应用卸载时，沙箱里的文件会自动一起删除

#### 沙箱里的文件存在哪里？

`/data/data/<包名>/files/` 清墨的包名为 org.octopusring.lightink

其中, 图书文件在 `<上面的路径>/flutter/book/`, 主题中的图片文件在 `<上面的路径>/flutter/background_image/`

#### 我还想了解具体的背景和为什么会这样设计

简单来说这是Android的最佳实践, 最大程度保护了用户的隐私和存储空间的干净整洁, 详见官方文档:

[https://developer.android.com/training/data-storage?hl=zh-cn#scoped-storage](https://developer.android.com/training/data-storage?hl=zh-cn#scoped-storage)