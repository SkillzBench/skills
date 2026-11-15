# agui-dotnet-protobuf

[![SkillzBench](https://skillzbench.com/api/badge/agui-dotnet-protobuf)](https://skillzbench.com/skills/agui-dotnet-protobuf)

Use the protobuf wire transport (instead of the default Server-Sent Events) for an AG-UI connection with the AG-UI .NET SDK — a compact binary event stream negotiated via the Accept header. USE FOR: making an AGUIChatClient prefer protobuf by wiring an AGUIEventStreamHandler with ProtobufEventStreamFormatter (then SseEventStreamFormatter as fallback) into the HttpClient; enabling a server to answer protobuf by registering ProtobufEventStreamFormatter and negotiating the response format from the request Accept header; understanding the protobuf-or-SSE fallback. DO NOT USE FOR: the default SSE transport or first-time setup (use agui-dotnet-streaming-chat); JSON event serialization questions; tools, state, interrupts, multimodal, or generative UI.

Mirrored from [skillzbench.com/skills/agui-dotnet-protobuf](https://skillzbench.com/skills/agui-dotnet-protobuf) — Trust Score, benchmarks and install options live there.
