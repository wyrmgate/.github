# Contributing to Wyrmgate

Wyrmgate repositories may be private, public, or source-available depending on the component. Follow the contribution policy of the repository you are working in when it provides more specific guidance.

## Development workflow

- Work from a short-lived branch.
- Keep changes focused and reviewable.
- Open a pull request against the repository's default branch.
- Ensure required checks pass before merge.
- Prefer squash merging unless a repository explicitly documents another strategy.
- Do not commit generated secrets, credentials, private keys, tokens, or environment-specific secret files.

## Commit messages

Use a concise conventional prefix where practical:

- `feat:` new functionality
- `fix:` bug fixes
- `docs:` documentation
- `refactor:` internal restructuring
- `test:` test changes
- `build:` build-system changes
- `ci:` CI/CD changes
- `chore:` maintenance
- `security:` security-related changes

## Security-sensitive changes

Authentication, authorization, cryptography, token handling, session management, tenant boundaries, and privilege changes require additional scrutiny. Include relevant tests and describe security implications in the pull request.

## Licensing

Do not assume that a repository is open source merely because it is hosted on GitHub. The license stated in each repository governs use and redistribution. If no license is present, no additional license rights are granted by default.
