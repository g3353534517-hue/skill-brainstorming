# 头脑风暴 / Brainstorming

![分类](https://img.shields.io/badge/分类-brainstorming-green)

## 简介 / Overview

You MUST use this before any creative work - creating features, building components, adding functionality, or modifying behavior. Explores user intent, requirements and design before implementation.

## 详细说明 / Details

Help turn ideas into fully formed designs and specs through natural collaborative dialogue.

Start by understanding the current project context, then ask questions one at a time to refine the idea. Once you understand what you're building, present the design and get user approval.

<HARD-GATE>
Do NOT invoke any implementation skill, write any code, scaffold any project, or take any implementation action until you have presented a design and the user has approved it. This applies to EVERY project regardless of perceived simplicity.
</HARD-GATE>

## Anti-Pattern: "This Is Too Simple To Need A Design"

Every project goes through this process. A todo list, a single-function utility, a config change — all of them. "Simple" projects are where unexamined assumptions cause the most wasted work. Th...

## 功能特性 / Features

- Brainstorming Ideas Into Designs
- Anti-Pattern: "This Is Too Simple To Need A Design"
- Checklist
- Process Flow
- The Process
- After the Design
- Key Principles
- Visual Companion

## 使用示例 / Usage Examples

```dot
digraph brainstorming {
    "Explore project context" [shape=box];
    "Visual questions ahead?" [shape=diamond];
    "Offer Visual Companion\n(own message, no other content)" [shape=box];
    "Ask clarifying questions" [shape=box];
    "Propose 2-3 approaches" [shape=box];
    "Present design sections" [shape=box];
    "User approves design?" [shape=diamond];
    "Write design doc" [shape=box];
 
...
```

## 文件结构 / File Structure

```
SKILL.md
scripts/frame-template.html
scripts/helper.js
scripts/server.cjs
scripts/start-server.sh
scripts/stop-server.sh
spec-document-reviewer-prompt.md
visual-companion.md
```

## 作者 / Author

Hermes Agent Community

## 许可证 / License

MIT License

---

更多技能请访问：[github.com/g3353534517-hue?tab=repositories](https://github.com/g3353534517-hue?tab=repositories)
