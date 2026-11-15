# agui-dotnet-shared-state

[![SkillzBench](https://skillzbench.com/api/badge/agui-dotnet-shared-state)](https://skillzbench.com/skills/agui-dotnet-shared-state)

Share structured, evolving state between an AG-UI agent and its client with the AG-UI .NET SDK — the client seeds state on the request, the server reads it, mutates it, and streams the updated state back as snapshots or deltas alongside the chat. USE FOR: sending initial/working state from the client via ChatOptions.RawRepresentationFactory -> RunAgentInput.State; reading inbound state on the server with ChatOptions.TryGetRunAgentInput and RunAgentInput.State; emitting a full state object as a StateSnapshotEvent (or incremental JSON-Patch changes as a StateDeltaEvent) from a DelegatingChatClient via ChatResponseUpdate.RawRepresentation; reading state back on the client from update.RawRepresentation as StateSnapshotEvent. DO NOT USE FOR: passing one-off tool arguments (use agui-dotnet-server-tools); rendering UI components from tool calls (use agui-dotnet-generative-ui); plain chat (use agui-dotnet-streaming-chat); approvals/interrupts, multimodal, or protobuf.

Mirrored from [skillzbench.com/skills/agui-dotnet-shared-state](https://skillzbench.com/skills/agui-dotnet-shared-state) — Trust Score, benchmarks and install options live there.
