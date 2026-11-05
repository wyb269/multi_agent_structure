# 多智能体协同架构

本仓库整理 14 种多智能体协同架构及 4 项工程基础能力。每种架构一份 Markdown 文档，包含原理、流程、适用场景和相关示例。

| 序号 | 架构 | 文档 |
| --- | --- | --- |
| 1 | Pipeline：流水线架构 | [查看](architectures/01-pipeline.md) |
| 2 | Supervisor / Manager-Worker：主子智能体架构 | [查看](architectures/02-supervisor.md) |
| 3 | Hierarchical：层级式多智能体架构 | [查看](architectures/03-hierarchical.md) |
| 4 | Router：路由分发架构 | [查看](architectures/04-router.md) |
| 5 | Parallel：并行协作架构 | [查看](architectures/05-parallel.md) |
| 6 | Graph / DAG：图工作流架构 | [查看](architectures/06-graph-dag.md) |
| 7 | Evaluator-Optimizer：评估优化循环架构 | [查看](architectures/07-evaluator-optimizer.md) |
| 8 | Handoff / Swarm：智能体交接架构 | [查看](architectures/08-handoff.md) |
| 9 | Group Chat：群聊协商架构 | [查看](architectures/09-group-chat.md) |
| 10 | Debate / Voting：辩论与投票架构 | [查看](architectures/10-debate-voting.md) |
| 11 | Blackboard：黑板共享架构 | [查看](architectures/11-blackboard.md) |
| 12 | Event-Driven：事件驱动架构 | [查看](architectures/12-event-driven.md) |
| 13 | Planner-Executor：动态规划执行架构 | [查看](architectures/13-planner-executor.md) |
| 14 | Hybrid：混合式架构 | [查看](architectures/14-hybrid.md) |

## 工程基础能力

以下四项能力帮助多智能体系统稳定运行，可与上面的架构组合使用。

| 序号 | 能力 | 文档 |
| --- | --- | --- |
| 1 | 智能体之间的数据交付标准 | [查看](foundations/01-data-contract.md) |
| 2 | 状态、记忆与上下文隔离 | [查看](foundations/02-state-memory-context.md) |
| 3 | MCP 和 A2A 的作用 | [查看](foundations/03-mcp-a2a.md) |
| 4 | 人工介入（Human-in-the-Loop） | [查看](foundations/04-human-in-the-loop.md) |

## 阅读方式

这些模式分属不同维度，可以组合使用：主子与层级侧重组织关系；流水线、并行、图工作流和循环侧重执行顺序；交接、黑板和事件驱动侧重控制或信息传递。产品案例经常同时体现多种模式；示例需求用于说明协作过程。
