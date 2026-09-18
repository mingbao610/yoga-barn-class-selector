# Yoga Barn Class Selector / Yoga Barn 课程选择器

一个面向乌布 The Yoga Barn 的选课助手 skill。它会结合当天真实课表、用户的练习经验、当天感受、课卡限制和可选的日历 / WHOOP 摘要，帮助用户理解课程并做出可执行的选择。回答语言会跟随用户的提问语言。

A Codex skill for choosing classes at The Yoga Barn in Ubud. It combines the live schedule, practice experience, current feelings, class-card constraints, and optional calendar / WHOOP summaries to explain classes and support an actionable choice. Responses adapt to the language of the user’s prompt.

它不代表 Yoga Barn 官方，也不会把 WHOOP 恢复分直接处方成某一堂课。健康数据、日历和本地凭据不包含在仓库中；接入是可选的，没有接入时仍可按用户自述完成基础选课。

## 安装 / Installation

将本目录复制到 Codex skills 目录：

Copy this directory into the Codex skills directory:

```text
~/.codex/skills/yoga-barn-class-selector
```

安装后可直接请求 Codex 使用 Yoga Barn 课程选择器，或显式提到 `yoga-barn-class-selector`。

After installation, ask Codex to use the Yoga Barn class selector or mention `yoga-barn-class-selector` explicitly.

## 主要能力 / Capabilities

- 核对当天乌布动态课表与场次详情
- 按用户目标、经验和当天感受比较课程
- 默认用两堂真实课程做清晰对照，支持二选一
- 明确课卡可用、需另付费和待确认状态
- 可选读取目标日期的日历忙闲和 WHOOP 必要摘要
- 没有连接时降级到自述，不阻塞基础使用
- Responses adapt to Chinese, English, or the dominant language in a mixed-language prompt.

## 边界 / Boundaries

课程目录和场次描述来自 Yoga Barn 公开页面；课程描述不等于医疗建议，也不保证余位、教师风格、教学语言或个人适用性。报名、付款和日历写入需要用户明确要求。

Class and session descriptions come from Yoga Barn’s public pages. They are not medical advice and do not guarantee availability, teacher style, teaching language, or personal suitability. Registration, payment, and calendar writes require an explicit user request.

## License

MIT，见 [LICENSE](LICENSE)。
