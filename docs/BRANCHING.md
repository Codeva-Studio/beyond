# Branching strategy

## Long-lived branches

- `main`: stable branch for production-ready work.
- `develop`: integration branch for completed feature work.

## Supporting branches

Create supporting branches from `develop` and merge them back through Pull Requests.

| Prefix | Purpose | Example |
|---|---|---|
| `feature/` | New capability or experience | `feature/immersive-gallery` |
| `fix/` | Bug fix | `fix/mobile-navigation` |
| `docs/` | Documentation | `docs/update-workflow` |
| `chore/` | Maintenance or configuration | `chore/github-templates` |
| `refactor/` | Internal restructuring | `refactor/scene-loader` |
| `test/` | Test-related work | `test/scene-transitions` |

Use lowercase words separated by hyphens. Keep branch names concise and descriptive.
