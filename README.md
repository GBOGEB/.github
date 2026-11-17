# GBOGEB/.github

Default community health files for every repository owned by **GBOGEB**.

GitHub uses a file from this repository only when a repository has **no file of that type of its own** (in its root, `.github/` or `docs/` folder). Nothing here is copied into other repositories, and none of it shows up in their clones.

| File | Default for |
|---|---|
| `CODE_OF_CONDUCT.md` | Every repository without its own code of conduct |
| `CONTRIBUTING.md` | Repositories without contributing guidelines |
| `SECURITY.md` | Repositories without a security policy |
| `SUPPORT.md` | Repositories without support guidance |
| `.github/ISSUE_TEMPLATE/` | Repositories without their own `.github/ISSUE_TEMPLATE/` folder |
| `.github/PULL_REQUEST_TEMPLATE.md` | Repositories without their own pull request template |

## Override rules

- **Issue templates override as a set.** A repository with its own `.github/ISSUE_TEMPLATE/` folder gets none of the templates here, not even the ones it doesn't redefine. Governed repositories (CODEX, ABACUS, pipeline-automation-hub) keep their own forms on purpose.
- **Licences are never inherited.** Each repository needs its own `LICENSE`. GBOGEB repositories default to Apache-2.0.
- **This repository must stay public**, or the defaults stop applying.

## Repository tiers

| Tier | Examples | Community files |
|---|---|---|
| Governed core | CODEX, ABACUS, pipeline-automation-hub | Inherit the code of conduct; keep repo-local issue forms tied to gates and `parked-intent`; keep their own `SECURITY.md` |
| Tools and libraries | gg_MATH, GEMINI, DOCX_RTM_Automation, Q_engineering_tools | Inherit everything here; carry their own `LICENSE` |
| Content, profile, dormant | GBOGEB, cryogenic-compliance | Inherit everything here; archive repositories that are no longer used |
| Forks | — | Not managed here |

## Licence

Apache-2.0, see [LICENSE](LICENSE). `CODE_OF_CONDUCT.md` is adapted from the Contributor Covenant 2.1 (CC BY 4.0).
