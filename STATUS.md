# Repo Status Audit — 2026-04-25

**Audited by:** Claude Code (automated audit)
**Branch:** audit/status-2026-04
**Repo:** dimijazz/awesome-ai-agents
**Repo type:** Public curated awesome-list (marketing / portfolio)

---

## Summary

| Item | Detail |
|------|--------|
| Deployment target | GitHub Pages / GitHub.com (static markdown, no build pipeline) |
| Stack | Markdown only — no package.json, no CI/CD config, no linters |
| Last commit | 2026-03-17 (39 days ago) |
| Total commits | 1 (single initial commit) |
| Files | 1 (`README.md`) — no CONTRIBUTING.md, no LICENSE, no CI badge checks |
| Stale entries (broken/outdated) | 3 flagged (see below) |

---

## Stale / Broken Flags

| # | Entry | Section | Issue |
|---|-------|---------|-------|
| 1 | `Claude Agent SDK` → links to `github.com/anthropics/claude-code` | Frameworks & Libraries | Wrong URL — Claude Agent SDK is `github.com/anthropics/agent-sdk`; claude-code is the CLI |
| 2 | `Claude Code` platform link → `claude.ai/claude-code` | Agent Platforms | URL redirects — correct landing is `claude.ai/download`; description says "Autonomous coding" which is accurate but the link may 404 for some regions |
| 3 | `CONTRIBUTING.md` referenced in Contributing section | Contributing | File does not exist in the repo — link will 404 on GitHub |

---

## Missing Items (High-Impact Gaps as of 2026-04-25)

- **LICENSE file** — required for Awesome List badge compliance (should be CC0 or MIT)
- **CONTRIBUTING.md** — referenced but absent
- **CI / link-checker** — no GitHub Actions workflow to catch dead links automatically
- **New entries missing:** Pydantic AI, Google ADK, OpenAI Agents SDK, Mastra, LlamaIndex Workflows — all released/stable since initial commit

---

## Recommendations (Priority Order)

1. **Fix the CONTRIBUTING.md link or create the file** — immediate 404 for any visitor who clicks it
2. **Add LICENSE (CC0-1.0)** — required for official Awesome List compliance
3. **Add a GitHub Actions link-checker** (e.g. `lychee-action`) — prevents future dead links
4. **Add missing 2025–2026 frameworks** (Google ADK, OpenAI Agents SDK, Pydantic AI, Mastra) — keeps the list relevant and drives traffic
5. **Pin the Awesome badge check** — run `awesome-lint` in CI to maintain curation standards

---

## Overall Health

**Score: 5 / 10**
Single-commit repo, no CI, missing license and contribution doc, 3 stale/broken references. Content is solid but needs maintenance and a few new high-profile additions to remain a credible marketing asset.
