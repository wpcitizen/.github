# Contributing to WP Citizen projects

Thank you for taking the time to improve a WP Citizen project. These shared guidelines are a starting point; a repository may add project-specific instructions that take precedence.

## Before you start

1. Read the target repository's README, supported-version policy, and existing contribution notes.
2. Search open and closed issues and pull requests before opening a duplicate.
3. For a substantial change, open or join a discussion/issue first so the scope can be agreed before significant work begins.
4. By participating, you agree to follow the [Code of Conduct](CODE_OF_CONDUCT.md).

## Reporting a bug

Use the repository's bug report form where available. Include a concise summary, reproduction steps, expected and actual behavior, relevant WordPress/PHP/plugin versions, and sanitized logs where useful.

Do not include passwords, API keys, payment details, personal data, production database dumps, or other secrets. Security vulnerabilities must be reported privately; see [SECURITY.md](SECURITY.md).

## Suggesting a feature

Use the feature-request form and explain the problem before prescribing a solution. Describe who benefits, the workflow involved, alternatives considered, and any compatibility or accessibility implications.

## Pull requests

- Keep changes focused and reasonably small.
- Follow the coding style, architecture, and conventions already used by the target repository.
- Add or update tests for behavior changes where the project has a test suite.
- Run the relevant linting, static analysis, and tests documented by that repository.
- Update documentation, changelogs, translations, and screenshots when the change affects them.
- Consider WordPress and PHP compatibility, accessibility, performance, privacy, and security.
- Do not commit generated build output, credentials, local configuration, or unrelated formatting changes unless the project explicitly requires them.
- Explain the motivation and implementation in the pull request description; link related issues with closing keywords where appropriate.

## Review process

Maintainers may ask for changes, tests, clarification, or a narrower scope. A pull request is not accepted until required checks pass and an authorized maintainer approves it. Be constructive and patient during review.

## Licensing

By submitting a contribution, you confirm that you have the right to submit it and that it can be distributed under the license stated by the target repository. This organization-wide guide does not grant a license or replace a project's `LICENSE` file.
