# TNT Growth — Google Ads Skills for Claude

Claude skills derived from the Google Ads playbook TNT Growth runs across high-spend paid-search accounts. Each one is a self-contained, runnable workflow — and also a complete SOP you can read end to end even if you never run it through Claude.

New skills ship roughly **one per week**.

## Install

Install any skill by copying it into your Claude skills folder:

```bash
mkdir -p ~/.claude/skills/<skill-name>
cp skills/<skill-name>/SKILL.md ~/.claude/skills/<skill-name>/SKILL.md
# if the skill has a references/ folder, copy it too:
cp -r skills/<skill-name>/references ~/.claude/skills/<skill-name>/ 2>/dev/null
```

Or read any `SKILL.md` straight through — each one is a complete SOP on its own.

**Want new skills as they drop?** Each one is announced — with how to put it to work on a real account — through the TNT Growth newsletter: [tntgrowth.com/skills](https://tntgrowth.com/skills).

## Skills

| Skill | What it does | Status |
|---|---|---|
| **search-term-scorer** | Scores Google Ads search terms 1-10 for relevance and produces an upload-ready negative keyword list | ✅ Available |
| **negative-library-starter** | Builds a categorized starter negative library from the business — before you have search-term data | ✅ Available |
| **ads-audit** | 34-point account health audit → scorecard + prioritized fix list | 🔜 Next |
| **funnel-bottleneck** | Walks the funnel stage-by-stage to pinpoint exactly where performance breaks | 🔜 Soon |
| **launch-readiness** | Decides whether an account is ready to launch Search / PMax / Demand Gen | 🔜 Soon |
| _more weekly_ | keyword-rehab, budget calculator, CFO pitch, forecast, incrementality, competitor analysis, + API-driven skills | 🔜 |

## How these are built
- **Written for the user, not just for Claude.** Read any `SKILL.md` and you have a usable operating procedure.
- **Each skill ships with** a worked example and tests (`tests/`), and a reference library (`references/`) where one helps.
- **Modify freely.** Swap in your own thresholds and benchmarks. Keep the frontmatter `description` stable — that's what tells Claude when to fire the skill.

## About
Built by [TNT Growth](https://tntgrowth.com/skills). Questions or want the full-stack version run on your account? Start at the link.

_Licensed under the [MIT License](LICENSE)._
