# 顶级吸引力三重奏

一个面向成年人约会与亲密关系问题的 Agent Skill。它把问题拆成三层：内在基础、互动判断和行动推进，输出具体建议，同时坚持双向选择、明确同意和尊重拒绝。

## 它能帮助你

- 分析刚认识、聊天、邀约、第一次约会等阶段；
- 判断哪些是事实，哪些只是焦虑推测；
- 写出自然、低压力、允许拒绝的表达；
- 处理回复变慢、被拒绝、朋友区和关系确认；
- 把注意力从控制对方转回自我成长与互惠判断。

它不提供操控、贬低、纠缠、跟踪、欺骗或绕开同意的技巧，也不保证任何关系结果。

## 安装

### Codex / 通用 Agent Skills 目录

```bash
git clone https://github.com/duliangkuan/attraction-mastery-framework.git
cp -R attraction-mastery-framework ~/.agents/skills/
```

Windows PowerShell：

```powershell
git clone https://github.com/duliangkuan/attraction-mastery-framework.git
Copy-Item -Recurse attraction-mastery-framework "$env:USERPROFILE\.agents\skills\"
```

安装后可直接询问约会问题，或显式调用：

```text
使用 $attraction-mastery-framework 分析：我们认识两周，见过一次，我想自然地约她第二次见面。
```

## 目录

```text
attraction-mastery-framework/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── framework.md
    ├── scenarios.md
    └── sources-and-boundaries.md
```

## 来源与声明

三层结构受到 Mystery、Robert Greene 和 Owen Cook 的公开作品启发，但本项目不把其观点描述为心理学定律。公开版已移除贬低、操控、外貌分级和规避拒绝等内容。完整说明见 [来源与使用边界](references/sources-and-boundaries.md)。

早期版本由[女娲 · Skill 造人术](https://github.com/alchaincyf/nuwa-skill)辅助生成；公开版由 [duliangkuan](https://github.com/duliangkuan) 重新编辑和维护。

## 许可

本仓库原创文本采用 [CC BY-NC-SA 4.0](LICENSE.md) 许可。允许署名后的个人学习、分享和非商业改编；商业使用需另行获得授权。引用作品与名称的权利归各自权利人所有。
