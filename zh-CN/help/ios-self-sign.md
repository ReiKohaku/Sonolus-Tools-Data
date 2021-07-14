# iOS自签教程

\* 本教程整理自网络，描述可能与实际情况有偏差，请您在参照时仔细甄别。

*本教程适用于 Sonolus Testflight 测试名额已满时，需要安装 Sonolus 体验的用户。*

*请注意，本教程并非懒人教程，需要您自己具备一定的动手能力。*

#### 前期准备

* 您的PC设备（电脑）

* 您的iOS设备

* [爱思助手](https://www.i4.cn/pros.html)

#### 安装爱思助手

请自行百度

#### 通过爱思助手为Sonolus签名

##### 准备工作

1. 从官网复制**最新版安卓安装包链接**，将链接末尾的`.apk`改成`.ipa`，例如：将`https://sonolus.com/download/Sonolus_0.5.2.apk`改为`https://sonolus.com/download/Sonolus_0.5.2.ipa`；

   > 如果下载太慢，试试将`sonolus.com`改成`sonolus.reikohaku.fun`，例如`https://sonolus.reikohaku.fun/download/Sonolus_0.5.2.ipa`

2. 将您的手机/iPad连接电脑后打开爱思助手，找到**设备标识(UDID)**并点击复制；

3. 点击**工具箱**页面，在“更多工具”中找到**IPA签名**并点击；

4. 点击**使用Apple ID签名**，找到**添加Apple ID**并点选，输入您的Apple ID账号密码，并将刚刚复制好的UDID输入第三行中；

5. 点击左上角的**添加IPA文件**，导入Sonolus的ipa包并点击游戏图标前面的方框；

6. 点击右下角的**开始签名**，等待签名完成。

#### 通过爱思助手安装Sonolus

1. 点击**我的设备**，找到**应用游戏**；
2. 点击**导入安装**，导入签名后的游戏本体，等待安装完成。

#### 注意事项
- 爱思助手的签名有效期为7天。超过签名有效期后，需要您重新按照[正式签名](self-sign#正式签名)内的步骤重新签名，并重新覆盖安装。