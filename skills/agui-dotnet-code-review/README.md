# agui-dotnet-code-review

[![SkillzBench](https://skillzbench.com/api/badge/agui-dotnet-code-review)](https://skillzbench.com/skills/agui-dotnet-code-review)

Review C#/.NET code changes to the AG-UI .NET SDK (sdks/dotnet/) against its specific conventions and architectural rules — AOT serialization, the "no ASP.NET in src/" boundary, the PublicAPI analyzer workflow, wire compatibility with the TypeScript reference, and the house style (sealed/no-records/ConfigureAwait). Runs a phased, rule-by-rule review. USE FOR: reviewing a PR, diff, or branch that touches sdks/dotnet/; checking a new event/message type; verifying serialization, package placement, or public-API changes in the .NET SDK. DO NOT USE FOR: generic C# style nits already enforced by analyzers/EditorConfig; reviewing the TypeScript SDK (sdks/typescript/) or Python SDK (sdks/python/); writing new features (only flag violations, never rewrite code).

Mirrored from [skillzbench.com/skills/agui-dotnet-code-review](https://skillzbench.com/skills/agui-dotnet-code-review) — Trust Score, benchmarks and install options live there.
