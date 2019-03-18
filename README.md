# 在 `halnedu.com` 上高效学习

## 准备工具

* 健康的大学生
* 桌面操作系统（Windows™，MacOS™ 和 *nix 系均可）
* 靠谱的浏览器（下面以 Google Chrome 72 为例）
* 上课的笔记本（逃



## 学习步骤

* 打开浏览器

![](assets/1.png)

* 进入学习网址

![](assets/2.png)

* 登录

![](assets/3.png)

* 进入学习

![](assets/4.png)

* 进入课程

![](assets/5.png)

* 点击还没有学习的课程

![](assets/6.png)

* 掏出笔记本，准备认真学习

![](assets/7.png)

* 按下 `F12` 打开 Google Chrome 的 DevTools

![](assets/8.png)

* 进入 `Sources`（源代码）

![](assets/9.png)

* 按下 `Ctrl + P`，打开文件搜索 

![](assets/10.png)

* 输入 `videojs-ext`，选择第一个文件进入

![](assets/11.png)

* 此时会看到该文件内容。点击左下角的格式化代码（`{}`）

![](assets/12.png)

* 现在代码能看了

![](assets/13.png)

* 按下 `Ctrl + F` 打开搜索。输入 `_disableSeek`，找到第 qwq 行

![](assets/14.png)

* 单击 qwq 这个行号设置断点

![](assets/15.png)

* 按下 `Ctrl + F` 后输入 `enableFastForward`，找到第 621 行

![](assets/16.png)

* 单击 621 这个行号设置端点

![](assets/17.png)

* 回到原来的浏览器，点击红色框内的进度条

![](assets/18.png)

* 此时 Google Chrome 的 DevTools 窗口会自动弹出，并且会定位到第 qwq 行

![](assets/19.png)

* 点击红框内的文字，找到 `_disableSeek`

![](assets/20.png)

* 双击 `true` 后将其修改为 `false`

![](assets/21.png)

* 按下 `Enter` 键确定

![](assets/22.png)

* 按下 `F8` 继续。 DevTools 会继续定位到第 621 行。点击红框内倒三角符号收起 `local` 一栏

![](assets/23.png)

* 从上至下依次点击红框内文字，看到 `enableFastForward`

![](assets/24.png)

* 双击 `0` 并将其修改为 `1`

![](assets/25.png)

* `Enter` 键确认

![](assets/26.png)

* 按下 `F8` 继续，回到原浏览器窗口。学习完成，收好自己的笔记本以备复习

![](assets/27.png)

* 按时完成作业愉悦身心、增长见识

![](assets/28.png)

* 享受快乐学习



## 提示

1. 请勿爆肝学习，注意身体健康。合理学习益脑，过度学习伤身
2. 提 Issue 很可能没用。欢迎 Pull Request