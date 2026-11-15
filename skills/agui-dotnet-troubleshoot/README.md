# agui-dotnet-troubleshoot

[![SkillzBench](https://skillzbench.com/api/badge/agui-dotnet-troubleshoot)](https://skillzbench.com/skills/agui-dotnet-troubleshoot)

Diagnose and fix problems in an AG-UI .NET app built on the AG-UI SDK — when streaming chat, tools, state, interrupts, or the transport misbehave. USE FOR: the agent forgetting earlier turns / history truncated; update.ConversationId always null; state or lifecycle updates that never arrive; a tool throwing at runtime or producing AOT/trim warnings; an unknown-tool error mid-run; 406 Not Acceptable from the endpoint; an interrupt or approval that won't resume; and inspecting the raw AG-UI event stream (curl SSE frames, RawEvent on ChatResponseUpdate.RawRepresentation) to see what's actually on the wire. DO NOT USE FOR: first-time setup or the happy path (use agui-dotnet-streaming-chat); implementing a specific feature cleanly (use the matching agui-dotnet-* skill).

Mirrored from [skillzbench.com/skills/agui-dotnet-troubleshoot](https://skillzbench.com/skills/agui-dotnet-troubleshoot) — Trust Score, benchmarks and install options live there.
