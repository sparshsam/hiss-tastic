# Security

## Scope

HissTastic is a local Python/Pygame game prototype. It does not currently use accounts, API keys, databases, external services, telemetry, or network requests.

## Environment Variables

No environment variables are required at this stage. If future modernization work adds configuration or credentials, `.env.example` must be updated with placeholder values only and real `.env` files must remain uncommitted.

## Reporting a Vulnerability

Please report security issues privately — do not open a public issue.

Use GitHub's private vulnerability reporting:

1. Open the **Security** tab of this repository.
2. Click **Report a vulnerability**.
3. Complete the form with as much detail as you can provide.

Include: a clear description of the issue, reproduction steps, the HissTastic version, and the expected impact. Do not post exploit details in unrelated public forums.

## Policy

- `.env`, `.env.*`, and `*.local` files are gitignored.
- Bundled Python installer binaries are excluded from version control.
- Dependencies should be reviewed before addition.
- No secrets, tokens, local credentials, or generated build artifacts should be committed.

For the ecosystem-wide security standard, see [ecosystem-standards](https://github.com/sparshsam/ecosystem-standards).
