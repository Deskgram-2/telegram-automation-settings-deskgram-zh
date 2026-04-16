# Deskgram 2 设置

设置模块是 Deskgram 2 中配置系统参数的中心区域，包括基础连接、系统选项、API Key、AI 提供商和通知。它是进入主动执行模块之前最重要的基础设施层之一。

[Deskgram 2 中文总览](https://github.com/Deskgram-2/deskgram-2-telegram-automation-zh) | [官网](https://deskgram2.com/) | [Telegram Bot](https://t.me/DG2welcomebot) | [Web Preview](https://deskgram2.com/web-preview)
## 交互式 Web Preview

[![Interactive Demo](https://img.shields.io/badge/DEMO-Try_in_Browser-brightgreen?style=for-the-badge&logo=google-chrome)](https://deskgram2.com/web-preview?path=%2Fapp-demo%2Ffunctions%2Fsettings)

在浏览器中体验这个模块: [打开 Web Preview](https://deskgram2.com/web-preview?path=%2Fapp-demo%2Ffunctions%2Fsettings)



## 模块简介

| 参数 | 内容 |
|---|---|
| 核心任务 | 配置 Deskgram 2 的系统级参数 |
| 适用场景 | 在 Telegram 自动化开始前完成平台准备 |
| 重要区域 | 主设置、系统选项、API Key、通知 |
| 帮助内容 | 连接、AI 提供商、界面行为、共享配置 |
| 关联模块 | 代理管理、账号面板、神经评论 |

## 模块能力

- 存储程序的核心参数；
- 管理系统和界面选项；
- 连接 API Key 和 AI 提供商；
- 控制通知和共享行为；
- 把基础设施准备集中在一个位置。

## 快速开始

1. 打开主设置并检查基础参数。
2. 配置系统选项和界面行为。
3. 需要时添加 API Key 和 AI 提供商。
4. 在启动执行模块前保存整套基础配置。

## 哪些执行模块最依赖这些设置

- [神经评论](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram-zh)，当 AI 提供商和系统级参数会直接影响执行时；
- [私信群发](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-zh)，当全局行为和通知配置需要先稳定下来时；
- [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh)，当你先搭建基础设施层再进入执行模块时；
- [代理管理](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram-zh)，当账号网格依赖一致的环境配置时；
- [任务管理器](https://github.com/Deskgram-2/telegram-task-manager-deskgram-zh)，当你希望控制层在执行前就已经准备完整。

## 适合在什么情况下使用

- 当你第一次准备 Deskgram 2；
- 当工作流中包含 AI 模块和外部 API；
- 当共享行为需要集中配置；
- 当你希望在执行前就把环境准备完整。

## 相比零散配置更方便的地方

| 手动方式 | Deskgram 2 设置 |
|---|---|
| 参数分散在多个窗口里 | 核心设置集中在一个区域 |
| API 和系统项容易遗漏 | 提供统一的平台准备入口 |
| 基础设施总是在执行过程中临时配置 | 可以提前准备运行环境 |
| 通知和行为设置彼此割裂 | 共享配置被集中管理 |
| 长期很难保持配置有序 | 设置模块帮助系统保持稳定 |

## 适用场景

- 第一次搭建 Deskgram 2 系统环境，在基础设施和执行模块启动前完成全局准备；
- 在 [神经评论](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram-zh) 和其他 AI 工作流之前接入 AI 提供商；
- 在大型活动前统一环境、通知和 API 就绪状态；
- 当多个操作者或模块共用同一套程序时，用设置模块保持系统一致性。

## 该选哪个：设置还是账号面板

| 如果你的目标是 | 更适合哪个 |
|---|---|
| 准备 API Key、全局行为和系统参数 | `设置` |
| 整理 Telegram 账号基础 | [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh) |
| 在启动前检查整个平台是否已准备好 | `设置` |
| 按具体工作流整理账号 | [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh) |

## 相关仓库

- [Deskgram 2 中文总览](https://github.com/Deskgram-2/deskgram-2-telegram-automation-zh)
- [代理管理](https://github.com/Deskgram-2/telegram-proxy-manager-deskgram-zh)
- [账号面板](https://github.com/Deskgram-2/telegram-account-manager-deskgram-zh)
- [神经评论](https://github.com/Deskgram-2/telegram-neuro-commenting-deskgram-zh)
- [私信群发](https://github.com/Deskgram-2/telegram-direct-messaging-deskgram-zh)
- [任务管理器](https://github.com/Deskgram-2/telegram-task-manager-deskgram-zh)

## FAQ

### 什么时候最适合进入设置模块？

最好是在启动主动执行模块之前，这样基础环境已经准备好。

### 为什么 API Key 和 AI 提供商放在这里？

因为这里是系统级共享配置的统一入口。
