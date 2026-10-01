# Contributing to ReplAI

Start with the relevant repository's README and development instructions. They define its setup, commands, architecture, and review requirements. Access to private repositories is managed separately.

## Propose a change

Use an existing issue when it covers the work, or open a bug report, feature request, or technical task in the affected repository. Describe the problem, affected component, intended behavior, and how the result can be verified. Keep account-specific questions in the support channel described in [SUPPORT.md](SUPPORT.md).

## Implement and verify

- Work on a focused branch and keep unrelated changes separate.
- Use the repository's documented build, formatting, and validation commands. Choose tests that verify behavior, including meaningful failure cases when applicable.
- When changing an API or event contract, explain compatibility and update affected consumers and generated clients as needed.
- When changing stored data, include the migration plan and describe any backfill, recovery, or deployment ordering required.
- Commit each completed, verified stage to Git with a clear message. Do not include credentials, local environments, generated build artifacts, or customer data.

## Open a pull request

Explain the problem and resulting behavior, link the related issue, and report the checks you ran and their results. Include screenshots for visible interface changes when helpful. Document contract or database changes and any remaining limitations so reviewers can assess the change without the conversation that led to it.
