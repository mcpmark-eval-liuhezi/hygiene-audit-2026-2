# Open-Source Hygiene Audit — 2026

**Audited account:** [`HeziLiu`](https://github.com/HeziLiu)
**Audit type:** Quarterly account hygiene review (repositories, tags/releases, teams & organizations, org security advisories, open pull requests, open issues & sub-issues)
**Published:** via the `audit-findings` branch of this repository

---

## 1. Identity

| Field | Value |
|---|---|
| Login | `HeziLiu` |
| Display name | Hezi Liu |
| Profile | https://github.com/HeziLiu |
| Company | BUPT/GZU |
| Location | Beijing/Guiyang |
| Bio | "treat me like a tree" |
| Public repos / gists | 4 public repos, 0 public gists |
| Followers / following | 5 / 5 |
| Account created | 2017-05-22 |

---

## 2. Personal Repositories (4 total)

All four repositories are public; **no private repositories were found**. Every repository was checked for git tags and its most recent release.

| # | Repository | Type | Language | Created | Last push | Git tags | Most recent release |
|---|---|---|---|---|---|---|---|
| 1 | [Little-rookie](https://github.com/HeziLiu/Little-rookie) ("Undergraduate coursework") | Source | Java | 2018-05-15 | 2019-06-02 | none | none |
| 2 | [Big-Buzzard](https://github.com/HeziLiu/Big-Buzzard) ("For future....") | Source (empty) | — | 2018-05-15 | 2018-05-17 | none | none |
| 3 | [CodingInterviewChinese2](https://github.com/HeziLiu/CodingInterviewChinese2) (《剑指Offer》第二版源代码) | Fork | C++ | 2019-03-12 | 2019-03-12 | none | none |
| 4 | [awesome-chatgpt-prompts-zh](https://github.com/HeziLiu/awesome-chatgpt-prompts-zh) | Fork | — | 2023-04-14 | 2023-04-14 | none | none |

**Findings:**
- **No git tags on any repository** — none.
- **No releases on any repository** — none.
- No stars, forks, watchers, or open issues on any of the four.
- Two of the four repositories are forks with no divergent work; one (Big-Buzzard) is an empty repository (zero commits' worth of content, no pushes since 2018).

---

## 3. Teams & Organizations

- **Organizations:** one — [`mcpmark-eval-liuhezi`](https://github.com/mcpmark-eval-liuhezi) (member).
- **Teams:** none found — the account belongs to no teams within that organization.
- The organization contains roughly 1,710 repositories (mix of public and private; the search index returned 1,710 at audit time).

---

## 4. Organization Repository Security Advisories

- The **organization-level security-advisory listing** could not be retrieved: the API returned `403 Resource not accessible by personal access token` — the current token does not grant org-wide advisory read scope.
- As a fallback, **per-repository security advisories were checked** on the organization's active repositories:
  - `t2d-trial-landscape` — none found
  - `demo-env-handover` — none found
  - `jwst-briefing` — none found
  - `github-automation-audit` — none found
  - Several other repositories (`claude-code`, `handover-playbook`, `hardware-refresh-budget`, `release-audit-sandbox-2`, `copilot-review-trial`) returned `404 Not Found` on the advisories endpoint (feature not enabled on those repos at check time).

**Net result: none found** — no repository security advisories were visible anywhere the token could reach. Re-running with a token that has org-level advisory scope is recommended for full coverage of the ~1,710 repos.

---

## 5. Open Pull Requests Authored

The account has **no open pull requests in its own repositories** — all open PRs live in the `mcpmark-eval-liuhezi` organization. The org's issue volume is very large and actively changing (search totals fluctuated between ~863–866 during the audit); the following open PRs were identified and verified in the snapshot:

| PR | Title | Repo |
|---|---|---|
| [#53](https://github.com/mcpmark-eval-liuhezi/claude-code/pull/53) | 【Feat】Automate Docker Image Builds with GitHub Actions | claude-code |
| [#52](https://github.com/mcpmark-eval-liuhezi/claude-code/pull/52) | feat: add shell completions (bash, zsh, fish) | claude-code |
| [#51](https://github.com/mcpmark-eval-liuhezi/claude-code/pull/51) | Enhance Statsig event logging in GitHub workflows | claude-code |
| [#1](https://github.com/mcpmark-eval-liuhezi/release-audit-sandbox-2/pull/1) | Dry run: add release audit checklist | release-audit-sandbox-2 |
| [#10](https://github.com/mcpmark-eval-liuhezi/release-drill-lab/pull/10) | Add drill checklist | release-drill-lab |
| [#1](https://github.com/mcpmark-eval-liuhezi/depsec-audit-2026/pull/1) | Quarterly dependency-security audit report: lodash (Q4 2026) | depsec-audit-2026 |
| [#1](https://github.com/mcpmark-eval-liuhezi/hardware-refresh-budget/pull/1) | Add mouse refresh budget analysis (MX Master 3S vs MX Anywhere 3S vs $700 cap) | hardware-refresh-budget |
| [#4](https://github.com/mcpmark-eval-liuhezi/demo-env-handover/pull/4) | Add verification log for demo environment | demo-env-handover |
| [#1](https://github.com/mcpmark-eval-liuhezi/jwst-briefing/pull/1) | JWST research briefing | jwst-briefing |

**Sub-issues on PR threads:** none found — each open PR thread listed above was checked and carries no attached sub-issues.

---

## 6. Open Issues Filed

Open issues authored by the account (all in the `mcpmark-eval-liuhezi` organization; none in personal repositories). The org's open-issue total fluctuated between ~2,482–2,556 during the audit; the following were identified in the snapshot, with their attached sub-issues:

| Issue | Title | Repo | Attached sub-issues |
|---|---|---|---|
| [#15](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/15) | Type 2 Diabetes Trial Landscape Tracker | t2d-trial-landscape | **4** — [#16](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/16) SUNSHINE benchmark, [#17](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/17) FINEROD, [#18](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/18) iCaReMe Registry, [#19](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/19) EXCEED |
| [#17](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/17) | NCT06278207 — FINEROD (Bayer) | t2d-trial-landscape | none |
| [#18](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/18) | NCT03549754 — iCaReMe Global Registry (AstraZeneca) | t2d-trial-landscape | none |
| [#19](https://github.com/mcpmark-eval-liuhezi/t2d-trial-landscape/issues/19) | NCT05663515 — EXCEED (AstraZeneca) | t2d-trial-landscape | none |
| [#1](https://github.com/mcpmark-eval-liuhezi/handover-playbook/issues/1) | Ship the handover pack | handover-playbook | **2** — [#2](https://github.com/mcpmark-eval-liuhezi/handover-playbook/issues/2) Document the deployment runbook (open), [#3](https://github.com/mcpmark-eval-liuhezi/handover-playbook/issues/3) Wire up CI checks (open) |
| [#1](https://github.com/mcpmark-eval-liuhezi/demo-env-handover/issues/1) | Demo environment handover | demo-env-handover | **2** — [#2](https://github.com/mcpmark-eval-liuhezi/demo-env-handover/issues/2) Install ingress-nginx controller (completed), [#3](https://github.com/mcpmark-eval-liuhezi/demo-env-handover/issues/3) Write handover README (completed) |
| [#1](https://github.com/mcpmark-eval-liuhezi/copilot-onboarding-lab/issues/1) | Trial: Copilot coding agent writes AGENT_NOTES.md | copilot-onboarding-lab | **1** — [#2](https://github.com/mcpmark-eval-liuhezi/copilot-onboarding-lab/issues/2) Draft review checklist for agent PRs (open) |
| [#4](https://github.com/mcpmark-eval-liuhezi/github-mcp-adoption-tracker/issues/4) | Pilot Copilot coding agent on a sample task | github-mcp-adoption-tracker | none |
| [#42](https://github.com/mcpmark-eval-liuhezi/claude-code/issues/42) | Clipboard Image Paste Functionality Broken on Mac Terminal | claude-code | none |
| [#43](https://github.com/mcpmark-eval-liuhezi/claude-code/issues/43) | Ctrl+B Keybinding Conflict on Linux (Ubuntu) | claude-code | none |

**Sub-issue summary:** 4 open issues carry attached sub-issues (#15 with 4, handover-playbook #1 with 2, demo-env-handover #1 with 2, copilot-onboarding-lab #1 with 1); all other open issue threads checked have **none**.

---

## 7. Hygiene Observations & Recommendations

1. **Releases/tags:** zero across the entire personal footprint. If any personal repo is meant to be reused, consider at least tagging a stable commit and publishing a release.
2. **Dormant repositories:** all four personal repos have been untouched since 2019 (or 2023 for the fork). Consider archiving `Little-rookie`, `Big-Buzzard`, and the two forks to signal dormancy — `Big-Buzzard` in particular is empty and could be deleted outright.
3. **Team membership:** none — all org access is at member level. If you collaborate in sub-groups, consider joining/creating a team so permissions are scoped.
4. **Advisory coverage:** org-wide advisory listing was blocked by token scope; no advisories found in the reachable per-repo checks. Re-run with an org-admin-scoped token for full coverage of ~1,710 repos.
5. **Open work items:** ~9 open PRs and ~10 open issues (plus 9 attached sub-issues) all live in the `mcpmark-eval-liuhezi` org — several are explicitly labeled demo/dry-run sandboxes ("intentionally left open"); those are candidates for closing out once their demos are complete.
6. **Repo names for this audit:** the repo `hygiene-audit-2026` already existed in the org, so this audit was published to `hygiene-audit-2026-2` per the agreed fallback.

---

*Audit generated end-to-end via the GitHub API. "none found" indicates the lookup returned an empty result at audit time.*
