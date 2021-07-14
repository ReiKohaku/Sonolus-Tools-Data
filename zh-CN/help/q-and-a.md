# 疑难解答

此文档整理了一些常见问题的解决方案。

如果您发现这里面没有您要找的问题的解决方案，请[联系我们](/#加入我们)。

## 怎么下载Sonolus？

参阅[快速上手Sonolus](/guide/quick-start)。

## iOS打不开Testflight页面怎么办？

如果您无法打开TestFlight，您可以做如下尝试：

1. 打开**设置**-**无线局域网**；
2. 连接可用的Wi-Fi网络；
3. 点击Wi-Fi网络名称右方的**显示信息**按钮；
4. 在该Wi-Fi网络详情部分向下滚动，找到**DNS**部分；
5. 点击修改DNS为8.8.8.8；
6. 点击左上角的**Wi-Fi**按钮退出设置，再尝试使用TestFlight。

## 提示“Testflight名额已满”怎么办？

有两个解决方案：

1. 等待开发者更换新的Testflight邀请链接；
2. 参阅[iOS自签教程](/help/ios-self-sign)。

## 有没有xx游戏/xx游戏的地址是什么？

参阅[服务器列表](/server-list)。

## 掉帧/卡顿怎么办？

在主界面点击**全局设置**按钮。

<center><img src="assets/help/q-and-a/home-page-settings.jpg" style="width: 100%; max-width: 640px" /></center>

降低**图像**下的**渲染比例**和**抗锯齿**的值后再试。

## 谱面和音频对不上怎么办？

您需要调整音频偏移。

在主界面点击**全局设置**按钮。

<center><img src="assets/help/q-and-a/home-page-settings.jpg" style="width: 100%; max-width: 640px" /></center>

调整**偏移**下的**设备音频偏移**和**设备输入偏移**后再试。您也可以使用**校准**功能，可以方便地对偏移进行校准。

*请注意：调整**设备输入偏移**极容易导致奇怪的输入判定，如非必要请勿调整。*

## 我觉得玩起来怪怪的是怎么回事？

Sonolus本质上只是**模拟器**，必然无法完全还原本家体验。

如果您不能接受这些差异，您可以放弃使用Sonolus而去体验本家。

