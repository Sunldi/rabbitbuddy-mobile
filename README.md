# RabbitBuddy 手机端

> 装在您手机上的 AI 搭档——与电脑版同一个账号，随身带、随时用。
>
> 接自己的模型就能对话办事；扫码连上电脑后，还能替您盯着电脑上的任务、随手批准。

[![Release](https://img.shields.io/github/v/release/Sunldi/rabbitbuddy-mobile)](https://github.com/Sunldi/rabbitbuddy-mobile/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/Sunldi/rabbitbuddy-mobile/total)](https://github.com/Sunldi/rabbitbuddy-mobile/releases)

**[下载最新版本](https://github.com/Sunldi/rabbitbuddy-mobile/releases/latest)** · [历史版本](https://github.com/Sunldi/rabbitbuddy-mobile/releases) · [问题反馈](https://github.com/Sunldi/rabbitbuddy-mobile/issues)

系统要求：Android 8.0 及以上

---

## 能做什么

- **登录同一账号**：邮箱验证码登录，与官网 / 电脑版同一账号，订阅与额度随身可见
- **本地助手**：接入您自己的模型服务（兼容 OpenAI 接口规范）即可对话办事；长记忆记在本机，看得见、删得掉
- **扫码连电脑**：对着电脑版「手机连接」的二维码扫一下即连上；电脑上的任务进展推到手机，需要批准的事随手点
- **手机能力（逐项授权）**：读指定文件夹（只读）、读屏与代点、读通知（念验证码）、后台保持连接——每一项在设置里都念当前状态，没开的递真能开的入口
- **自动化**：看电脑上已有的定时任务并按暂停/恢复；本机自动规则
- **外观**：深色 / 浅色 / 跟随系统三档主题

## 下载与安装

1. 打开 [Releases](https://github.com/Sunldi/rabbitbuddy-mobile/releases) 页面，在最新版本的 **Assets** 中下载 `RabbitBuddy-<版本号>.apk`
2. 打开 APK 按系统提示安装；首次安装需允许「安装未知应用」
3. 更新版本：下载新 APK 直接覆盖安装即可，登录态与本机数据保留

> 安装包已用官方密钥签名。非应用商店渠道安装时，系统可能出现风险提示，属正常现象。

## 首次使用

1. 打开 App，用邮箱收验证码登录（与官网 / 电脑版同一账号）
2. 要用本地助手：设置 → 本地模型 → 添加，填入名称、连接地址、API 密钥和型号（支持兼容 OpenAI 接口规范的服务）
3. 要连电脑：设置 → 连接设备 → 扫码，对着电脑版「手机连接」页的二维码扫一下

> 模型调用产生的费用由您选择的服务商按实际用量收取，请留意其计费规则。

## 您的数据在哪里

- 登录与账号信息只走加密连接（HTTPS）到官网服务
- 手机与电脑之间的任务内容端到端加密，只在您的两台设备上
- 对话内容会发送给您自己接入的模型服务，用于生成回复（由您选择的服务商处理）
- 本机记忆、授权记录都存在手机本机，设置里可查看、可清除
- 隐私政策与服务条款：App 内 设置 → 关于 RabbitBuddy，或访问 [rabbitidea.com](https://rabbitidea.com)

## 常见问题

**必须自己接入模型服务吗？** 本地助手是。接入任意兼容 OpenAI 接口规范的服务即可使用；连接电脑后用的是电脑上已配好的模型。

**不连电脑能用吗？** 能。本地助手独立可用；连电脑解锁的是任务盯守与随手批准。

**支持 iOS 吗？** 暂仅提供 Android 版本，iOS 在规划中。

## 关于本仓库

- 本仓库用于发布官方安装包，**不包含源代码**
- 新版本在本仓库发布，下载覆盖安装即可；也可以随时在 App 内查看当前版本（设置 → 关于 RabbitBuddy）
- 安装包及相关内容版权归作者所有

## 反馈

遇到问题或有建议，欢迎 [提交 Issue](https://github.com/Sunldi/rabbitbuddy-mobile/issues)。
或邮箱<2664541799@qq.com>，QQ同号。抖音ID：51912256774(打火机),关注了解相关资讯！