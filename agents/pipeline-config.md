# MODEL SELECTION
Default model: replace-with-your-model

Per-role overrides:
- Orchestrator: replace-with-your-model
- Planner: replace-with-your-model
- Coder: replace-with-your-model
- Tester: replace-with-your-model
- Reviewer: replace-with-your-model

Fallbacks:
- Primary: replace-with-your-model
- Secondary: replace-with-your-model

# THIRD-PARTY SKILLS
Add skill files under /agents/skills/ or /.agents/skills/.
Each skill file should include:
- Name
- Purpose
- Inputs
- Outputs
- Constraints
- Example usage

Registered skills:
- /.agents/skills/design-taste-frontend/SKILL.md

The orchestrator loads skills by matching phase and inputs.
