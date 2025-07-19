# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 项目概述

这是一个 Claude Code 命令库和实践经验分享项目，收集个人使用心得和社区最佳实践。

## 核心架构

### 命令组织结构
- `.claude/commands/zh/` - 中文命令库
- `.claude/commands/en/` - 英文命令库（结构相同）
- 双语同步：所有命令都有中英文版本

### 命令分类体系
**command/ 目录**：命令管理工具
- `create.md` - 智能命令创建架构师
- `optimize.md` - 基础命令优化工具
- `optimize-advanced.md` - 高级命令架构师
- `optimize-agent.md` - 多代理协作优化器

**code/ 目录**：专业开发工具
- `automation-specialist.md` - 高级自动化专家

## 常用命令

```bash
# 创建新的自定义命令
/create 描述你想要的命令功能

# 优化现有命令（基础版）
/optimize .claude/commands/zh/command/your-command.md

# 深度优化命令（高级版）
/optimize-advanced .claude/commands/zh/command/your-command.md

# 多代理协作优化
/optimize-agent .claude/commands/zh/command/your-command.md

# 自动化任务专家
/automation-specialist 描述你的自动化需求
```

## 命令开发规范

### 标准文件格式
```yaml
---
description: '命令功能的简洁描述'
allowed-tools: ['工具列表']
---

## Context
# 上下文变量和设置

## Your Task
# 角色定义和核心任务

## 执行框架
# 分阶段的执行策略
```

### 开发原则
1. **多语言同步**：
   - 修改命令时必须同时更新中英文版本
   - **重要**：修改中文文档后，必须对应更新所有其他语言版本的文档
   - 包括 README.md、docs/README.en.md、docs/README.zh.md 等
2. **实践导向**：所有命令都应来自真实使用场景
3. **渐进复杂度**：从 create → optimize → optimize-advanced 的学习路径
4. **标准格式**：严格遵循 YAML Front Matter + Markdown 结构

## 项目特色

1. **自举改进**：使用 Claude Code 来改进 Claude Code 使用体验
2. **知识沉淀**：将日常使用经验系统化为可复用的命令
3. **社区共享**：收集和整理社区最佳实践
4. **版本管理**：通过 Git 跟踪命令演进历史

## 开发工作流

1. **创建新命令**：使用 `/create` 快速生成基础模板
2. **迭代优化**：通过 `/optimize` 系列命令不断改进
3. **测试验证**：在实际项目中验证命令效果
4. **文档更新**：及时更新 README 和相关文档
5. **多语言维护**：
   - 修改中文文档后，立即更新对应的英文版本
   - 确保所有语言版本内容保持一致
   - 包括命令文件、README 文档、说明文档等

## 注意事项

- 这不是传统的代码项目，没有构建、测试或代码检查命令
- 主要"开发活动"是创建和优化 Claude Code 自定义命令
- 重点关注命令的实用性和可复用性
- 优先使用简体中文进行交流（基于用户全局配置）