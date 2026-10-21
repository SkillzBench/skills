# agentwhy-session-audit

[![SkillzBench](https://skillzbench.com/api/badge/agentwhy-session-audit)](https://skillzbench.com/skills/agentwhy-session-audit)

Checks which private files (.env, keys, secrets) Claude Code and its subagents reached in this project, whether a value came into an agent's context, and which key to change, by running the open source agentwhy CLI over the session records Claude Code already keeps on disk. Use when the user asks whether the agent or a subagent read their .env or other secrets, which private files a session touched, whether a key leaked into the conversation, or which key to rotate. Runs locally and never prints a secret value.

Mirrored from [skillzbench.com/skills/agentwhy-session-audit](https://skillzbench.com/skills/agentwhy-session-audit) — Trust Score, benchmarks and install options live there.
