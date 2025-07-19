# Claude Code Garden

一个专门用于收集和分享 Claude Code 技巧、命令和最佳实践的仓库。

A dedicated repository for collecting and sharing Claude Code tips, commands, and best practices.

## 概述 / Overview

本仓库旨在为 Claude Code 用户提供一个集中的资源库，包含高质量的自定义命令、使用技巧和工程化最佳实践。无论您是初学者还是高级用户，都能在这里找到有用的资源。

This repository aims to provide Claude Code users with a centralized resource library containing high-quality custom commands, usage tips, and engineering best practices. Whether you're a beginner or advanced user, you'll find useful resources here.

## 目录结构 / Directory Structure

```
.claude/
├── commands/
│   ├── zh/                    # 中文命令
│   │   ├── command/          # 通用命令优化工具
│   │   │   ├── create.md     # 智能命令创建架构师
│   │   │   ├── optimize.md   # 命令优化工具
│   │   │   ├── optimize-advanced.md    # 高级命令架构师
│   │   │   └── optimize-agent.md       # 多代理协作优化器
│   │   └── code/             # 代码相关专家
│   │       └── automation-specialist.md # 高级自动化专家
│   └── en/                    # English Commands
│       ├── command/          # General Command Optimization Tools
│       │   ├── create.md     # Intelligent Command Creation Architect
│       │   ├── optimize.md   # Command Optimization Tool
│       │   ├── optimize-advanced.md    # Advanced Command Architect
│       │   └── optimize-agent.md       # Multi-Agent Collaborative Optimizer
│       └── code/             # Code-Related Specialists
│           └── automation-specialist.md # Advanced Automation Specialist
```

## 命令介绍 / Command Overview

### 中文命令 / Chinese Commands

#### 命令管理工具 / Command Management Tools

- **create.md** - 智能命令创建架构师：根据自然语言描述，自动分析、设计并创建符合项目规范的 Claude Code 自定义命令文件
- **optimize.md** - 命令优化工具：分析并优化指定的 Claude Code 命令，提升其执行效果和用户体验  
- **optimize-advanced.md** - 首席命令架构师：对指定的 Claude Code 命令进行架构级深度重构，交付体现最佳实践的生产级典范之作
- **optimize-agent.md** - 命令生态总指挥：并行编排多个专家子代理，对指定的Claude Code命令进行架构级的深度重构

#### 代码专家工具 / Code Specialist Tools

- **automation-specialist.md** - 高级自动化专家：基于复杂度评估的脚本优先策略，提供计划-审核-执行-报告的四步自动化解决方案

### English Commands

#### Command Management Tools

- **create.md** - Intelligent Command Creation Architect: Automatically analyze, design, and create Claude Code custom command files that comply with project specifications based on natural language descriptions
- **optimize.md** - Command Optimization Tool: Analyze and optimize specified Claude Code commands to improve their execution effectiveness and user experience
- **optimize-advanced.md** - Principal Command Architect: Perform architecture-level deep refactoring of specified Claude Code commands, delivering production-grade exemplary works that embody best practices
- **optimize-agent.md** - Chief Orchestrator of Command Ecosystem: Coordinate multiple expert sub-agents in parallel to perform architecture-level deep refactoring of specified Claude Code commands

#### Code Specialist Tools

- **automation-specialist.md** - Advanced Automation Specialist: Providing script-priority strategy based on complexity assessment, offering a four-step automation solution of plan-review-execute-report

## 使用方法 / Usage

### 基本使用 / Basic Usage

在 Claude Code 中使用斜杠命令调用：

Use slash commands in Claude Code:

```bash
# 中文命令 / Chinese Commands
/create 我需要一个用于代码重构的命令
/optimize .claude/commands/my-command.md
/optimize-advanced .claude/commands/my-command.md
/optimize-agent .claude/commands/my-command.md
/automation-specialist 批量处理图片文件

# English Commands
/create I need a command for code refactoring
/optimize .claude/commands/my-command.md
/optimize-advanced .claude/commands/my-command.md
/optimize-agent .claude/commands/my-command.md
/automation-specialist batch process image files
```

### 高级功能 / Advanced Features

- **智能创建**：使用 `create` 命令基于自然语言描述自动生成新命令
- **渐进式优化**：从 `optimize` 到 `optimize-advanced` 再到 `optimize-agent`，提供不同级别的命令优化
- **自动化专家**：使用 `automation-specialist` 处理复杂的自动化任务

- **Intelligent Creation**: Use `create` command to automatically generate new commands based on natural language descriptions
- **Progressive Optimization**: From `optimize` to `optimize-advanced` to `optimize-agent`, providing different levels of command optimization
- **Automation Expert**: Use `automation-specialist` to handle complex automation tasks

## 贡献指南 / Contributing

欢迎提交新的命令、改进现有命令或分享使用心得！

We welcome submissions of new commands, improvements to existing commands, or sharing of usage experiences!

### 提交流程 / Submission Process

1. Fork 此仓库 / Fork this repository
2. 创建功能分支 / Create a feature branch
3. 添加或修改命令文件 / Add or modify command files
4. 确保命令遵循项目规范 / Ensure commands follow project specifications
5. 提交 Pull Request / Submit a Pull Request

### 命令规范 / Command Specifications

- 使用标准的 YAML frontmatter 格式
- 提供清晰的描述和工具列表
- 包含完整的上下文信息和执行指令
- 遵循最小权限原则配置 allowed-tools

- Use standard YAML frontmatter format
- Provide clear descriptions and tool lists
- Include complete context information and execution directives
- Follow principle of least privilege for allowed-tools configuration

## 许可证 / License

MIT License - 详见 [LICENSE](LICENSE) 文件

MIT License - See [LICENSE](LICENSE) file for details

## 联系方式 / Contact

如有问题或建议，请通过 GitHub Issues 联系我们。

For questions or suggestions, please contact us through GitHub Issues.