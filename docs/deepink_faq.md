# 清墨常见问题 FAQ

### 本地阅读器是什么? 

本地电子书阅读器是用于导入已经下载好的图书的, 不支持书源. 

### 书源地址有吗? 大家可以分享下吗?

清墨不支持书源.

### 我怎么看我想看的书?

可以自己在百度/谷歌/必应等搜索引擎搜索下载后导入清墨.

比如搜索 https://www.bing.com/search?q=阅微草堂笔记+txt

### 我还是搞不懂怎么下载怎么办? T.T

可以小红书之类的上面搜索一下, 

比如搜索: txt/epub小说下载网站求推荐

### 小说怎么导入?

点击右上角 + 号, 可以选择本地文件, 或者自己网盘中的图书导入.

### 在哪里可以下载到清墨App呢?

iOS可以直接在 App Store 搜索清墨下载.

Android可以点击下面链接下载apk, 记得要在浏览器打开哦, 在 qq / 微信里是不行的. 

[lightink-v1.10.4+113-android.apk](http://github.lightink.ltd/https:/github.com/octopusring/Light-Ink/releases/download/v1.10.4/lightink-1.10.4+113-android.apk)

也可以在群文件下载.

### 清墨的图书文件存储

在 Android 中，每个应用都有自己独立的专属文件夹，这个独立空间就叫做 应用沙箱（App Sandbox）。

#### 沙箱的特点：

1. 只有该应用本身能访问自己的文件
2. 其他应用无法读取或修改里面的内容
3. 应用卸载时，沙箱里的文件会自动一起删除

#### 沙箱里的文件存在哪里？

/data/data/<包名>/files/
清墨的包名为 org.octopusring.lightink

#### 我还想了解具体的背景和为什么会这样设计

简单来说这是Android的最佳实践, 最大程度保护了用户的隐私和存储空间的干净整洁, 详见官方文档:
[link](https://developer.android.com/training/data-storage?hl=zh-cn#scoped-storage)