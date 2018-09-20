---
layout: post
title:  "拥抱iOS 12的系统自动填充"
date:   2018-09-20 16:52:45 +0800
category: article 
---


### 前言

在 iOS 12 正式更新后，第三方密码管理软件可以接入到系统的自动填充功能中。于是在第一天我就让FantasyPass实现了这一功能，为了确保其它新功能的稳定性，所以在今天发布。

<!--more-->

### 使用

#### 开启自动填充

想要启用密码自动填充功能，只需进入`“设置”>“密码和帐户”`，随后开启`“自动填充密码”`即可。随后用户可以根据需要选择启用自动填充功能的 App，包括 iCloud Keychain。

<img src="/asset/images/system_autofill_setting.png" alt="Javascript Plugin" width="300" />

激活后，用户可以通过点击密码自动填充（显示在软键盘上方的小键图标）并从所需服务中选择信息来访问支持应用程序中的二级验证码。在填写配置的文本字段（例如用户名和密码）之前，设备会通过 Face ID，Touch ID 或 PIN 码对用户进行身份验证，以确保安全。

<img src="/asset/images/img201809181620240.jpg" alt="Javascript Plugin"/>


#### 使用

一般应用或者网站的登录页面，点击输入框之后键盘上会显示一个小钥匙的图标。点击小钥匙，选择FantasyPass，然后选择你想填充的登录项即可。为了让您更好的分辨你需要填充的登录项，在FantasyPass新版中显示了用户名信息，让它更方便使用。

<img src="/asset/images/help_system_autofill.png" alt="Javascript Plugin" width="300" />

#### 总结

在之前由于系统限制，App中无法粘贴密码和自动填充，导致生成复杂的密码登录App时候会非常不方便。现在你可以尽情使用FantasyPass来自动填充网页或者任何App，让FantasyPass成为你的生活好伴侣。之后版本会更加深入这一功能，FantasyPass已经是我日常生活中常用App之一。