# agui-cross-sdk-parity

[![SkillzBench](https://skillzbench.com/api/badge/agui-cross-sdk-parity)](https://skillzbench.com/skills/agui-cross-sdk-parity)

Keep the AG-UI .NET SDK at feature and wire-format PARITY with the canonical reference SDKs (TypeScript is the source of truth; Python is types/encoder only). USE FOR: porting a feature/event/behavior that landed in the TS (or Python) SDK into .NET, verifying the .NET wire format (JSON, SSE, protobuf) matches the reference, locating where the reference implementation and compatibility fixtures live, mapping a TS concept to the .NET event/client/encoder model, resolving an upstream protocol fix (e.g. a Microsoft.Extensions.AI / Microsoft Agent Framework issue) that needs a .NET counterpart, deciding which .NET package owns a change. DO NOT USE FOR: the mechanics of writing a specific test (use agui-dotnet-unit-tests for serialization round-trips, agui-dotnet-integration-tests for cross-language / E2E harness mechanics, agui-dotnet-wire-types for JSON/proto type rules, agui-dotnet-transport for SSE/HTTP transport details). This skill is about the PARITY PROCESS and where the reference lives, not test authoring.

Mirrored from [skillzbench.com/skills/agui-cross-sdk-parity](https://skillzbench.com/skills/agui-cross-sdk-parity) — Trust Score, benchmarks and install options live there.
