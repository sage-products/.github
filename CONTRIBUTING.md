# Contributing to Sage Products

Read the target repository's README and contributor instructions first. Use its
documented setup and validation commands; there is no universal build command
across Sage's software, firmware, and operational repositories.

## Propose and Develop Changes

Describe the problem and expected outcome in the project's designated tracker.
Company contributors should link the Jira issue. Confirm ownership and scope
before starting a substantial change. Use a feature branch such as
`feature/SAGE-123-short-description`, substituting the actual ticket key.

Match the repository's language, formatting, and test conventions. Add meaningful
tests for changed behavior and regressions. Keep credentials, customer records,
and confidential material out of source code, examples, logs, and public issues.

## Submit for Review

Use a concise Conventional Commit subject, such as
`fix(SAGE-123): handle an interrupted connection`. Open a focused pull request
against `develop` where GitFlow is used, or the repository's documented target.
Describe the outcome, linked issue, validation, and material risks. Include
screenshots for visible interface changes. Complete required checks and review
before merging; sensitive changes require additional review under company policy.
