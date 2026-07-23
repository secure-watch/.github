# Contributing

[한국어](CONTRIBUTING.ko.md)

Secure Watch manages design, documentation, and code contributions in the open.

| Purpose | Channel |
| --- | --- |
| Ideas and design proposals | GitHub Discussions |
| Confirmed bugs and actionable work | GitHub Issues |
| Documentation and code changes | Pull requests |
| Private security vulnerabilities | The process defined in `SECURITY.md` |

Before contributing, check whether a related Discussion or Issue already exists. Pull requests should include the purpose of the change, key decisions, validation results, and related Issues.

Repository-specific contribution guidelines take precedence.

## Access and contribution boundaries

Secure Watch keeps public OSS contributions open while restricting repository administration:

- Anyone may read public repositories, open Issues and Discussions, and submit pull requests from a fork.
- Protected default branches accept changes through reviewed pull requests rather than direct pushes.
- Repository visibility changes, deletion, transfer, team creation, and organization settings are restricted to organization owners.
- Repository write access is granted per repository through maintainer teams; organization membership does not grant write access by default.
- Workflows from external fork pull requests require maintainer approval before they run.

These organization defaults are administrative controls. Each repository must still configure its own branch rules, CODEOWNERS, required checks, and maintainer permissions.

## Commit messages

Use the following format:

```text
<type>(<scope>): <short summary>
```

Recommended types are `feat`, `fix`, `docs`, `ci`, and `chore`. Useful scopes include `profile`, `policy`, `template`, `label`, `workflow`, and `community`.

Every commit must reference a related Issue with `Refs #123` or `Fixes #123`. Create the Issue before committing if one does not exist.
