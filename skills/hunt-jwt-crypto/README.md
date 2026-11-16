# hunt-jwt-crypto

[![SkillzBench](https://skillzbench.com/api/badge/hunt-jwt-crypto)](https://skillzbench.com/skills/hunt-jwt-crypto)

"Hunt JWT cryptographic failures — alg:none signature-stripping and RS256→HS256 key-confusion that let an attacker forge a token for any identity (e.g. an admin) without knowing a secret. Use when the app authenticates with a JSON Web Token (an `eyJ...` Bearer token in the Authorization header, a cookie, or a login response). This skill OWNS JWT signature/crypto forgery (alg:none, key confusion, kid/jku header injection); hunt-ato covers JWT as one ATO path, hunt-auth-bypass covers SSO/SAML token trust, hunt-api-misconfig covers non-crypto JWT handling. Critical when a forged token grants access to another user's data or an admin-only endpoint."

Mirrored from [skillzbench.com/skills/hunt-jwt-crypto](https://skillzbench.com/skills/hunt-jwt-crypto) — Trust Score, benchmarks and install options live there.
