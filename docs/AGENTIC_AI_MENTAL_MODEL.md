# Agentic AI Mental Model

A useful enterprise agent is not just a prompt wrapped around a model.

I think of an enterprise agent as a bounded decision and execution system with:

- a clear business goal
- trusted context
- approved tools
- explicit memory boundaries
- permission controls
- human approval paths
- evaluation criteria
- observability
- fallback behavior

```text
Agentic AI System =
Business Goal
+ Context
+ Tools
+ Memory
+ Policy
+ Evaluation
+ Human Review
```

## What each part means

**Business Goal**  
The measurable outcome the agent is designed to improve.

**Context**  
The business, user, workflow, policy, and system information required to act usefully.

**Tools**  
The approved APIs, MCP tools, retrieval systems, and workflow actions the agent can use.

**Memory**  
The information the agent can retain across a session, user, entity, or workflow.

**Policy**  
The rules that define permissions, boundaries, approval needs, and prohibited actions.

**Evaluation**  
The test cases, metrics, and review process that determine whether the agent is reliable.

**Human Review**  
The approval, escalation, and override paths required when risk is high.

## How I use this model

I use this model to avoid starting with the model too early. Before designing an agent, I want to understand the user, workflow, data, tools, approval points, and success metrics.

For me, the strongest AI product work starts with a real workflow and then asks what kind of agent, tool, memory, and evaluation system the workflow actually needs.
