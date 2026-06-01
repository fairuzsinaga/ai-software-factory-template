---
description: "Use when: working in this repo. Always enforce the pipeline loop and read workflow inputs before any work."
---

# Pipeline Rule

Always run the pipeline loop (Planner -> Coder -> Tester -> Reviewer) until the goal is reached.

Before starting any phase work:
- Read /agents/global-workflow.md
- Read /agents/pipeline-config.md
- Read /10-progress/status.md

Do not skip pipeline steps. If a step cannot proceed, record the blocker and route back to Planner.
