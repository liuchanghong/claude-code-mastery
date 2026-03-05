# Claude Code 实战精通手册
# Claude Code: The Practical Mastery Handbook

> **写给真正想用好 Claude Code 的开发者**
>
> 不是官方文档的翻译。不是入门教程的堆砌。
> 这是一本让你读完就能用、用完就上瘾的实战手册。

> **For developers who want to truly master Claude Code**
>
> Not a translation of the official docs. Not a pile of beginner tutorials.
> This is a battle-tested handbook you can apply immediately and get addicted to.

---

## 这本书是给谁的 / Who This Book Is For

- 你会写代码，但不一定是 AI 专家
- 你听说过 Claude Code，但还没发挥出它的真正威力
- 你讨厌那种"AI 很厉害，以下是 10 个技巧"的废话文章
- 你希望读完一本书就能真正改变工作方式

- You can write code, but you're not necessarily an AI expert
- You've heard of Claude Code, but haven't unlocked its real power
- You're sick of "AI is amazing, here are 10 tips" fluff articles
- You want to read one book and genuinely change how you work

**你的背景不重要。**
iOS 开发者、后端工程师、全栈、脚本仔——只要你写代码，这本书就适合你。

**Your background doesn't matter.**
iOS dev, backend engineer, full-stack, scripter—if you write code, this book is for you.

---

## 如何阅读这本书 / How to Read This Book

**不用从头读到尾。** 这本书按你的需求设计：

**You don't have to read it front to back.** This book is designed around your needs:

| 你的情况 | 从这里开始 | Your situation | Start here |
|---------|-----------|---------------|-----------|
| 刚安装 Claude Code | 第 1 章 → 第 2 章 → 第 3 章 | Just installed Claude Code | Chapter 1 → Chapter 2 → Chapter 3 |
| 用了一段时间但感觉没发挥威力 | 第 4 章 → 第 7 章 → 第 10 章 | Using it but not feeling the power | Chapter 4 → Chapter 7 → Chapter 10 |
| 想在 iOS/Swift 项目里用 | 第 9 章（可单独阅读） | Want to use it in iOS/Swift projects | Chapter 9 (standalone read) |
| 想彻底改造工作流 | 第 11 章 → 第 13 章 | Want to overhaul your workflow | Chapter 11 → Chapter 13 |
| 遇到具体问题 | 直接查附录 | Have a specific problem | Go straight to the Appendix |

每章开头都有 **TL;DR**，5 秒钟知道这章值不值得你读。

Every chapter starts with a **TL;DR**—5 seconds to decide if it's worth your time.

---

## 章节目录 / Table of Contents

| # | 章节 / Chapter | 中文概括 | English Summary |
|---|---------------|---------|----------------|
| [00](./00-preface.md) / [EN](./00-preface_en.md) | 序言：打破你对 AI 助手的幻想 / Preface: Shattering Your AI Assistant Illusions | 为什么 90% 的人用 Claude Code 都用错了 | Why 90% of people use Claude Code wrong |
| [01](./01-mental-model.md) / [EN](./01-mental-model_en.md) | 你需要的核心心智模型 / The Mental Model You Need | 不理解这个，其他技巧都是白搭 | Without this, every other technique is built on sand |
| [02](./02-setup-and-first-steps.md) / [EN](./02-setup-and-first-steps_en.md) | 安装与最重要的第一步 / Setup & Your First Critical Steps | 10 分钟内完成配置并跑出第一个有价值的结果 | Configured and delivering value in 10 minutes |
| [03](./03-art-of-instructions.md) / [EN](./03-art-of-instructions_en.md) | 指令的艺术 / The Art of Instructions | 你说什么，比 Claude Code 有多厉害更重要 | What you say matters more than how smart Claude is |
| [04](./04-file-and-code-operations.md) / [EN](./04-file-and-code-operations_en.md) | 代码操作精通 / Code Operations Mastery | 读、写、搜、改——掌握 Claude Code 的核心能力 | Read, write, search, edit—master Claude Code's core |
| [05](./05-git-workflow.md) / [EN](./05-git-workflow_en.md) | Git 工作流集成 / Git Workflow Integration | 让 Claude Code 成为你最靠谱的代码伙伴 | Make Claude Code your most reliable coding partner |
| [06](./06-debugging.md) / [EN](./06-debugging_en.md) | 调试的艺术 / The Art of Debugging | 把 Bug 消灭速度提升 10 倍 | Kill bugs 10x faster |
| [07](./07-claude-md-mastery.md) / [EN](./07-claude-md-mastery_en.md) | CLAUDE.md 的秘密 / The CLAUDE.md Secret | 让 Claude Code 永远记住你的规则 | Make Claude Code remember your rules forever |
| [08](./08-building-real-projects.md) / [EN](./08-building-real-projects_en.md) | 构建真实项目 / Building Real Projects | 从零到完整功能的完整流程 | Complete workflow from zero to working feature |
| [09](./09-ios-and-swift.md) / [EN](./09-ios-and-swift_en.md) | iOS & Swift 专项 / iOS & Swift Deep Dive | iOS 开发者专属的实战模式 | Patterns built for iOS developers |
| [10](./10-advanced-techniques.md) / [EN](./10-advanced-techniques_en.md) | 高级技巧：成为 1% / Advanced Techniques: Join the 1% | 自定义命令、Hooks、MCP、并行任务 | Custom commands, Hooks, MCP, parallel tasks |
| [11](./11-workflows-and-automation.md) / [EN](./11-workflows-and-automation_en.md) | 工作流与自动化 / Workflows & Automation | 打造你的 10x 开发日常 | Build your 10x developer daily routine |
| [12](./12-mistakes-and-fixes.md) / [EN](./12-mistakes-and-fixes_en.md) | 最常见的错误与解法 / Common Mistakes & Fixes | 少踩这些坑，少浪费几百小时 | Avoid these pits, save hundreds of hours |
| [13](./13-expert-mindset.md) / [EN](./13-expert-mindset_en.md) | 专家心智 / The Expert Mindset | 从"会用"到"精通"的最后一跃 | The final leap from "can use" to "mastery" |
| [附录](./APPENDIX.md) / [EN](./APPENDIX_en.md) | 快速参考手册 / Quick Reference | 命令、快捷键、Flags 大全 | Commands, shortcuts, flags cheat sheet |

---

## 读前须知 / Prerequisites

这本书默认你：
- 有基础的命令行使用经验（知道 `cd`、`ls`）
- 有一门编程语言的实战经验
- 已经安装或准备安装 Claude Code

This book assumes you:
- Have basic command-line experience (know `cd`, `ls`)
- Have real-world experience with at least one programming language
- Have installed or are about to install Claude Code

如果你还没安装，先看[第 2 章](./02-setup-and-first-steps.md)。

If you haven't installed it yet, start with [Chapter 2](./02-setup-and-first-steps_en.md).

---

*基于 Claude Code (claude-sonnet-4-6) 实战经验编写 / Written from hands-on experience with Claude Code (claude-sonnet-4-6)*

*最后更新：2026 年 3 月 / Last updated: March 2026*
