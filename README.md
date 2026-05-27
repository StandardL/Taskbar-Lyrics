# 基于原版修改的内容

1. fix c++ backend 偶发的空指针引用崩溃
2. fix 设置页标题文本没有翻译 
3. fix 无法设置歌词字体的问题
4. 部分歌词使用了 `[time1][time2]` 的格式，对其做了兼容
5. 带翻译的歌词能显示翻译

![sample](dist/taskbar-lyrics-sample.png)

## 食用方法

1. 在 C:\betterncm 目录下，创建plugins_dev目录
2. 进入倒plugins_dev目录，新建taskbar_lyrics文件夹
3. 把dist文件夹内所有问题复制到taskbar_lyrics目录下。
4. 重载网易云音乐

已知问题：**与AMLL不兼容**

# Taskbar-Lyrics

当前主分支为2.0版本，目前还在开发中，目前能够编译使用

BetterNCM插件，在任务栏上嵌入歌词，目前仅建议Windows 11

只适配原版任务栏，使用第三方软件修改后出现问题的均不解决！

![preview](plugin/public/preview.png)
