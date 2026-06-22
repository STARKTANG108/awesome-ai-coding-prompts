# 🤖 Awesome AI Coding Prompts

> 精选 AI 辅助编程提示词模板，覆盖代码生成、审查、调试、文档、重构等全开发流程。  
> A curated collection of high-quality prompts for AI-assisted software development.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

[中文](#中文版) | [English](#english-version)

---

## 为什么需要这个项目？

AI 编程助手非常强大，但前提是你知道如何与它对话。模糊的提示词只会产生平庸的结果。本项目收录了经过验证的提示词模板，覆盖软件开发生命周期的每个阶段，帮助开发者将 AI 工具的效能最大化。

---

## 📚 目录

- [代码生成](#-代码生成)
- [代码审查](#-代码审查)
- [调试排错](#-调试排错)
- [文档编写](#-文档编写)
- [代码重构](#-代码重构)
- [测试用例](#-测试用例)
- [Git 提交](#-git-提交)
- [架构设计](#-架构设计)

---

## 💡 代码生成

### 从需求描述生成函数
```
请根据以下需求生成一个 [语言] 函数：
需求：[描述功能]
输入：[参数说明]
输出：[返回值说明]
注意事项：[边界条件、性能要求等]
请同时添加详细注释。
```

### 生成数据模型
```
请为以下业务场景创建数据模型：
场景：[场景描述]
需要包含的字段：[字段列表]
语言/框架：[技术栈]
请包含字段类型、注释和基本验证逻辑。
```

### 生成样板代码
```
请为 [技术栈] 项目生成一个 [模块名称] 的样板代码。
功能概述：[描述]
需要遵循的规范：[代码规范或风格]
```

---

## 🔍 代码审查

### 全面代码审查
```
请对以下代码进行全面审查，重点关注：
1. 潜在的 Bug 或逻辑错误
2. 安全漏洞
3. 性能瓶颈
4. 代码可读性和可维护性
5. 是否遵循最佳实践

代码：
[粘贴代码]
```

### 安全性专项审查
```
请对以下代码进行安全性分析：
- 检查 SQL 注入、XSS、CSRF 等常见漏洞
- 检查敏感信息硬编码问题
- 检查权限控制缺陷
- 给出具体的修复建议

代码：
[粘贴代码]
```

---

## 🐛 调试排错

### 错误分析
```
我遇到了以下错误，请帮我分析原因并给出解决方案：

错误信息：
[粘贴报错]

相关代码：
[粘贴代码]

运行环境：[操作系统、语言版本、框架版本]
已尝试的方法：[已尝试的解决方式]
```

### 性能问题排查
```
以下代码在处理大量数据时性能很差，请帮我：
1. 找出性能瓶颈
2. 解释原因
3. 提供优化后的版本

代码：
[粘贴代码]
数据规模：[数据量描述]
```

---

## 📝 文档编写

### 生成函数文档
```
请为以下函数生成完整的文档注释，包括：
- 功能描述
- 参数说明（类型、含义、是否必填）
- 返回值说明
- 异常情况
- 使用示例

函数代码：
[粘贴代码]
```

### 生成 README
```
请为我的开源项目生成一份专业的 README.md，包括：
- 项目名称和简介
- 功能特性列表
- 安装方法
- 快速开始示例
- API 文档（如有）
- 贡献指南
- License 说明

项目信息：[项目描述]
技术栈：[技术栈]
```

---

## ♻️ 代码重构

### 提升可读性
```
请重构以下代码以提高可读性和可维护性：
- 改善命名（变量、函数、类）
- 消除魔法数字和魔法字符串
- 减少代码重复
- 保持原有功能不变，并说明每处改动的原因

原始代码：
[粘贴代码]
```

### 模块化拆分
```
以下代码功能过于集中，请帮我将其拆分为更小的、职责单一的模块：
- 每个模块应只做一件事
- 模块之间保持低耦合
- 给出拆分后的完整代码结构

代码：
[粘贴代码]
```

---

## 🧪 测试用例

### 生成单元测试
```
请为以下函数生成完整的单元测试，要求：
- 覆盖正常流程、边界条件和异常情况
- 使用 [测试框架，如 Jest/pytest/JUnit]
- 每个测试用例添加描述说明

函数代码：
[粘贴代码]
```

---

## 📦 Git 提交

### 生成 Commit Message
```
请根据以下代码变更，生成符合 Conventional Commits 规范的 commit message：

变更内容：
[描述本次变更]

diff：
[粘贴 git diff]
```

### 生成 Pull Request 描述
```
请根据以下信息生成一份规范的 Pull Request 描述：
- 变更类型：[feature/fix/refactor/docs]
- 解决的问题：[问题描述]
- 实现方式：[技术方案]
- 测试情况：[如何测试]
- 是否有 Breaking Change：[是/否]
```

---

## 🏗️ 架构设计

### 技术方案评审
```
请评审以下技术方案的合理性：
需求背景：[业务需求]
提案方案：[方案描述]

请从以下角度分析：
1. 可行性和潜在风险
2. 可扩展性和可维护性
3. 性能和安全性考量
4. 是否有更优替代方案
```

---

## 🤝 Contributing

欢迎提交 Pull Request 贡献更多高质量提示词！请查看 [贡献指南](CONTRIBUTING.md)。

---

## English Version

This repository contains a curated collection of prompt templates for AI-assisted software development. These prompts are designed to work with ChatGPT, Codex, Claude, and other AI coding assistants.

See the Chinese sections above — English translations are in progress. Contributions welcome!

---

## License

[MIT](LICENSE) © 2026
