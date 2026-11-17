# guarding-destructive-operations

[![SkillzBench](https://skillzbench.com/api/badge/guarding-destructive-operations)](https://skillzbench.com/skills/guarding-destructive-operations)

Add and review preconditions on operations that delete, overwrite, rewrite history, or resolve a caller-supplied name to a filesystem path — refusing instead of warning, placing the guard ahead of the first mutation, structural classification rather than string-prefix matching, name validation plus resolved-path containment as two independent checks, why a guard on the destructive path is invisible to the dry-run, and mutation-testing each half separately. Use when writing or reviewing a `--rebuild`/`--reset`/`--purge` command, a bulk delete, a history rewrite, an `rm -rf`-shaped step, or any code that turns an argument into a file path.

Mirrored from [skillzbench.com/skills/guarding-destructive-operations](https://skillzbench.com/skills/guarding-destructive-operations) — Trust Score, benchmarks and install options live there.
