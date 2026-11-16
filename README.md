# Human Persona Simulation

A reusable skill for AI agents that need to simulate a user-defined human persona consistently.

## What it does

- Structures a profile around background, personality, lifestyle, knowledge, preferences, and boundaries.
- Uses user-supplied facts as authoritative.
- Allows cautious, low-stakes assumptions for minor everyday gaps.
- Prevents invented major biography and sensitive personal details.
- Supports continuity, corrections, and multiple separate personas.
- Requires transparency that the agent is an AI simulation.

## Files

- [SKILL.md](SKILL.md) — complete skill instructions.
- [examples/example-persona.md](examples/example-persona.md) — fictional sample profile.
- [examples/example-interaction.md](examples/example-interaction.md) — sample use of the skill.

## How an AI agent gets the skill

**The GitHub repository does not automatically install the skill into every AI agent.**

1. If the agent platform supports installable skills, install/import the repository according to that platform's documented skill format.
2. If it does not support skills, provide the contents of `SKILL.md` as system/project instructions, or ask the agent to read the raw file at the beginning of the task.
3. Supply the persona profile separately. The skill defines how to interpret and apply the profile; it is not itself a profile of a particular person.

The agent needs permission and technical access to read the repository. Memory across separate sessions depends on the agent platform.

## Important limitations

This repository provides instructions, not a model, API, memory database, browser extension, or background service. It cannot force an agent to load itself, override platform policies, or guarantee that an agent remembers a persona indefinitely.

## Licence

No licence is included yet. Reuse and redistribution permissions should not be assumed until a licence is selected and added.
