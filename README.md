# Yoga Barn Class Selector / Yoga Barn 课程选择器

一个面向乌布 The Yoga Barn 的选课助手 skill。它会结合当天真实课表、用户的练习经验、当天感受、课卡限制和可选的日历 / WHOOP 摘要，帮助用户理解课程并做出可执行的选择。回答语言会跟随用户的提问语言。

A Codex skill for choosing classes at The Yoga Barn in Ubud. It combines the live schedule, practice experience, current feelings, class-card constraints, and optional calendar / WHOOP summaries to explain classes and support an actionable choice. Responses adapt to the language of the user’s prompt.

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
  Check Ubud’s live schedule and session details.
- 按用户目标、经验和当天感受比较课程  
  Compare classes using the user’s goals, experience, and current feelings.
- 默认用两堂真实课程做清晰对照，支持二选一  
  Present two real sessions side by side so the user can choose between them.
- 明确课卡可用、需另付费和待确认状态  
  Distinguish class-card eligible, separately paid, and unresolved payment status.
- 可选读取目标日期的日历忙闲和 WHOOP 必要摘要  
  Optionally use relevant calendar availability and WHOOP summaries for the target date.
- 根据用户提问的语言回答  
  Respond in Chinese, English, or the dominant language of a mixed-language prompt.

## 边界 / Boundaries

课程目录和场次描述来自 Yoga Barn 公开页面；它们用于帮助理解和比较课程，不替代医疗建议，也不保证余位或个人适用性。报名、付款和日历写入需要用户明确要求。

Class and session descriptions come from Yoga Barn’s public pages. They help users understand and compare sessions, but do not replace medical advice or guarantee availability or personal suitability. Registration, payment, and calendar writes require an explicit user request.

## License

MIT，见 [LICENSE](LICENSE)。  
MIT License, see [LICENSE](LICENSE).
