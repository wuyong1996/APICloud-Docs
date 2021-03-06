/*
Title: 有米广告SDK接入
Description: 有米广告平台接入指南
*/

### 前言
欢迎您使用有米平台广告，在使用有米平台广告之前，您需要前往[有米主站](https://www.youmi.net/)注册开发者账号．当您注册成功并进入到有米后台时，您可以为您的应用申请**appid**以及**appsecret**，appid和appsecret用于在使用有米模块时初始化需要传入的值．

目前仅支持**Android**平台

### 申请应用APPID流程

1. 登陆有米主站后台
2. 点击**添加应用**，并填写应用必要的信息
  ![](/img/adsYoumi/1.png)
3. 点击下一步，获得发布ID(appId)和应用密钥(appSecret)
  ![](/img/adsYoumi/2.png)
4. 按照**APICloud平台->开放SDK->adsYoumi**接入说明，将上述appId和appSecret接入到应用中即可
5. 当贵应用接入完毕后，请上传贵应用的apk包到[有米平台](https://www.youmi.net)审核，当贵应用审核通过后，贵应用才可以获得广告收益．
  ![](/img/adsYoumi/3.png)

## 有米平台在APICloud上支持的广告类型

### 积分墙

#### 积分墙简介
1. 有米积分墙是在APP内展示各种广告任务以供用户完成任务获得虚拟币的页面
2. 广告任务包括安装试用优质应用、注册、填表等
3. 用户完成任务获得虚拟币的同时，APP的开发者也能获得收入
4. 有米积分墙现有“全屏积分墙”和“对话框式积分墙”两种形式


#### 全屏积分墙
* 点击积分墙入口，以跳转到全屏页面的方式展示积分墙
* 页面美观大方，与APP完美结合，为用户带来良好体验
![](/img/adsYoumi/wall-2.jpg)

#### 对话框积分墙
* 点击积分墙入口，以对话框的形式在原来的APP页面弹出积分墙
* 减少了页面切换的次数，让积分墙与应用的搭配更自然
![](/img/adsYoumi/wall-3.jpg)