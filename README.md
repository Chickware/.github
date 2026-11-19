# .github

Organization-wide defaults for Chickware repositories on GitHub.

Files in this repository (issue templates, pull request template, and other
community health files) apply to every repository in the `chickware`
organization that does not define its own.

## Contents

Planned:

- `ISSUE_TEMPLATE/`: issue forms (bug, feature, task)
- `pull_request_template.md`: default PR description, including the linked
  issue, the human-review checklist for agent-authored PRs, and the
  `Co-Authored-By` trailer reminder

## Contributing

- Work on a branch named `type/<issue-number>-short-description`.
- Conventional Commits for commits and PR titles (e.g. `docs(templates): add bug report form`).
- PRs linked to an issue, squash-merged; agent PRs need human review.
- This repository has no CHANGELOG or releases.

## License

[MIT](LICENSE).
