# agui-dotnet-reasoning

[![SkillzBench](https://skillzbench.com/api/badge/agui-dotnet-reasoning)](https://skillzbench.com/skills/agui-dotnet-reasoning)

Surface a reasoning/thinking model's intermediate thoughts separately from its final answer with the AG-UI .NET SDK — so a client can show the agent "thinking" before it responds, and handle that reasoning trace correctly across turns. USE FOR: distinguishing the model's reasoning trace from its answer on the client by matching TextReasoningContent vs TextContent in each ChatResponseUpdate's Contents; rendering thinking and answer in different ways as they stream; deciding whether to carry the reasoning text into later turns (whether to append/resend the model's reasoning back into conversation history). DO NOT USE FOR: plain text streaming with no reasoning display (use agui-dotnet-streaming-chat); tools, shared state, interrupts, multimodal, generative UI, or protobuf.

Mirrored from [skillzbench.com/skills/agui-dotnet-reasoning](https://skillzbench.com/skills/agui-dotnet-reasoning) — Trust Score, benchmarks and install options live there.
