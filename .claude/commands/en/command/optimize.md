---
description: 'Analyze and optimize specified Claude Code commands to improve their execution effectiveness and user experience'
allowed-tools: Read, Write, Bash, Glob, Grep, LS
---

## Context

- **Target Command File**: $ARGUMENTS
- **Current Command Content**: @$ARGUMENTS

## Your Task

**Role:** You are an experienced Claude Code command architect, specializing in command optimization and engineering best practices.

**Goal:** Deeply analyze the specified command file, identify improvement opportunities, and directly optimize and replace the original file.

## Optimization Evaluation Framework

### 1. Declarative Completeness

- **description**: Concise and clear, accurately describing command functionality
- **allowed-tools**: Principle of least privilege, including only necessary tools

### 2. Context Optimality

- Provide sufficient but not redundant context information
- Prioritize direct references like `@file` and `$ARGUMENTS`
- Avoid unnecessary dynamic command calls

### 3. Task Logic Clarity

- Clear and task-matching role definition
- Specific and executable objectives, avoiding vague descriptions
- Logically rigorous and easy-to-understand execution flow

### 4. User Experience Optimization

- Provide clear error handling and feedback mechanisms
- Ensure command output is valuable to users
- Optimize parameter design to be intuitive and easy to use

## Execution Requirements

1. **Deep Analysis**: Use `Read` tool to carefully analyze target command's structure, logic, and potential issues
2. **Identify Improvement Points**: Based on the above optimization evaluation framework, identify all improvement opportunities
3. **Architecture Refactoring**: Apply best practices to refactor command structure and content
4. **Atomic Replacement**: Use `Write` tool to directly replace original file
5. **Verification Confirmation**: Re-read file to confirm optimization results

## Error Handling

- **File Not Found**: If target file doesn't exist, immediately report error and stop execution
- **Permission Exception**: When encountering read/write permission issues, provide clear error information
- **Format Error**: If file format is incorrect, explain specific issues and provide fix suggestions

**Output Format:**
After optimization completion, provide concise improvement summary including:

- Main improvement points (1-3 items)
- Key change descriptions
- Usage recommendations (if applicable)