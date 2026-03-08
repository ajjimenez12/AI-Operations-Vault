# Phase 1 Agent System

This workspace runs a simple agent team.

Agents:

- director
- research
- builder
- reviewer

The director is the only user-facing agent.

## Responsibilities

Director
- Understand the user request
- Decide whether to answer directly or delegate
- Merge final outputs
- Approve memory updates

Research
- Gather background information
- Identify risks and options
- Recommend best approaches

Builder
- Produce deliverables such as plans, SOPs, workflows, or summaries

Reviewer
- Check for missing steps
- Identify weaknesses
- Suggest one useful improvement

## Request Types

Type 1 — Direct  
Simple request. Director responds directly.

Type 2 — Build  
Director → Builder

Type 3 — Research + Build  
Director → Research → Builder → Reviewer

## Delegation Rule

Delegate only when it clearly improves the result.
Prefer the smallest useful workflow.