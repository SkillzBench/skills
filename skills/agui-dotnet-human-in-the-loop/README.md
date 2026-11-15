# agui-dotnet-human-in-the-loop

[![SkillzBench](https://skillzbench.com/api/badge/agui-dotnet-human-in-the-loop)](https://skillzbench.com/skills/agui-dotnet-human-in-the-loop)

Pause an AG-UI agent run for a human, then resume it, with the AG-UI .NET SDK — gate a sensitive tool behind explicit approval, or interrupt a run to collect free-form input from the user before continuing. USE FOR: requiring human approval before a tool executes (ApprovalRequiredAIFunction + ToolApprovalRequestContent/ToolApprovalResponseContent, resume by appending the request + CreateResponse(approved)); pausing a run to ask the user a question and resuming with their answer (InterruptRequestContent / InterruptResponseContent, RunAgentInput.Resume); how a paused run surfaces as RUN_FINISHED outcome=interrupt and how the client detects and answers it. DO NOT USE FOR: tools that run without approval on the server (use agui-dotnet-server-tools) or in the client (use agui-dotnet-client-tools); plain chat (use agui-dotnet-streaming-chat); shared state, generative UI, multimodal, or protobuf.

Mirrored from [skillzbench.com/skills/agui-dotnet-human-in-the-loop](https://skillzbench.com/skills/agui-dotnet-human-in-the-loop) — Trust Score, benchmarks and install options live there.
