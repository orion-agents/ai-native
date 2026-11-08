# ai-native

[English](README.md) | [简体中文](README.zh-CN.md)

**Forget the working directory. Forget the orchestration overhead. Think and act in an AI-native way.**

## Why we need a new way of working

The number of AI agents is growing fast, but we still manage them like people: assign tasks one by one, prescribe working directories, track sessions, coordinate dependencies by hand, and move results back into the main workflow. It is like managing an airport with the methods of a bus station. As aircraft and flights multiply, manually directing every move becomes a bottleneck.

We need to delegate management authority to AI agents. People define the destination, the rules, and the risk boundaries. Within that mandate, agents plan, break down work, collaborate, execute, and verify. Managers focus on goals, policies, and outcomes instead of remotely directing every step.

## What AI-native work means

AI-native is not another chat interface or scheduler layered onto the old process. It changes how work is organized:

- **Start with intent.** Describe the outcome, constraints, and acceptance criteria instead of deciding up front which directory, tool, or manual sequence must be used.
- **Grant agency.** Within clear permissions, budgets, and risk boundaries, agents can choose how to decompose work, select collaborators, sequence tasks, and handle routine failures.
- **Let teams form around the work.** Bring agents together as the task requires. Independent work can happen in parallel; dependent work proceeds in sequence. Adding agents should not require adding a matching amount of human dispatch work.
- **Coordinate through verifiable results.** Hand work off through task definitions, shared state, patches, evidence, and acceptance criteria—not copied conversation histories or constant human monitoring.
- **Keep human control over direction and boundaries.** People set goals and policies. Actions that are irreversible or high impact require escalation when the authorization rules call for it. Agents act autonomously within their mandate and remain accountable for outcomes.

“Forget the working directory” does not mean discarding work records. It means the directory is no longer the entry point or the object of management. Work state and artifacts should remain traceable, recoverable, and transferable; folders and worktrees are execution details.

## A collaboration pattern in practice

The current `ai-native` project uses Manager–Worker collaboration as a starting point. A user states an outcome. The Manager clarifies scope and completion criteria, then assigns bounded subtasks to suitable Workers. When parallel work is useful, each Worker handles an independent task in an isolated workspace. Workers return a concise summary, changes or patches, verification evidence, and unresolved questions. The Manager reviews the work, resolves conflicts, and integrates the result.

This practice reflects the core direction of AI-native work: people provide intent, agents organize execution; work is centered on tasks and outcomes; Workers receive explicit authority; and Managers focus on routing, quality, and risk instead of relaying every instruction. It is an evolving reference, not a mandate to use fixed roles or directories for every task.

## Vision

People should be able to say where they want to go and which rules must hold, then trust AI agents to assemble the right capabilities and carry the work from understanding and planning through collaboration and verification. People can focus on direction, judgment, and creativity. Agents get enough authority to make things happen within reliable boundaries.
