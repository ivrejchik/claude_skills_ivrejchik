# Solve

Spawn a full parallel dev team to solve any problem.

## What it does

Acts as a team lead that:
1. Understands your problem deeply
2. Researches the codebase using parallel Explore agents
3. Plans the work into execution waves
4. Deploys a team of specialized agents (all running Opus)
5. Orchestrates the team, handles blockers, and coordinates handoffs
6. Verifies the work integrates correctly before declaring success

## Usage

```
/solve [optional problem description]
```

## Features

- All agents use the strongest model (Opus)
- Parallel agents run in isolated worktrees to prevent conflicts
- Automatic verification step after team completion
- Proper shutdown and cleanup of all agents
