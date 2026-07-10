# Official source coverage map

Sources: OpenAI's official Codex documentation at [learn.chatgpt.com/docs](https://learn.chatgpt.com/docs) and the free courses/videos at [OpenAI Academy](https://academy.openai.com) (Intro to Codex, Codex for Beginners, Codex 101, Codex for Builders, Codex for Work), plus the [openai/codex](https://github.com/openai/codex) open-source repo. Target: teach ~80% of the working content of each mapped source. Codex ships fast - the docs changelog is re-checked before each delivery of the course.

Verified facts baked into the course (fetched 2026-07-09):
- Codex included in ALL ChatGPT plans; Plus meters usage per 5-hour window; cloud tasks + code reviews share the pool.
- Models: GPT-5.6 Sol (deep reasoning) / Terra (default) / Luna (fast) + GPT-5.4 mini; switch via /model.
- CLI: /init (AGENTS.md), /status, /permissions, /model, /review, /skills; codex exec; codex resume; MCP support.
- AGENTS.md hierarchy: ~/.codex/AGENTS.md (global) → repo root → subdirectory.
- Skills: open cross-agent standard; SKILL.md (name + description = trigger) + optional scripts/, references/, agents/openai.yaml; live in .agents/skills (repo) or ~/.agents/skills (user); trigger implicitly, via /skills, or $skill mention; $skill-creator scaffolds; plugins bundle for sharing; Claude Code skills are drop-in compatible.
- Prompting guide: Goal / Context / Output / Boundaries (GCOB); results over steps; iterate in follow-ups.

## Session 1 - Meet Codex: your AI engineering teammate

| Official source | Coverage |
|---|---|
| Codex quickstart (docs) | ✓ install, sign-in, first run, desktop-app path |
| Prompting guide (docs) | ✓ GCOB + Codex-specific habits (repro steps, constraints, ask verification) |
| Models & pricing (docs) | ✓ Sol/Terra/Luna, Plus 5-hr windows, credits, /model habit |
| Intro to Codex + Codex for Beginners (Academy) | ✓ agent concept, five surfaces, onboarding |
| Permissions (docs) | ◐ working level; full depth in Session 2 |

## Session 2 - First build: from plan to homepage

| Official source | Coverage |
|---|---|
| Codex 101 (Academy) | ✓ the build loop, navigating a project, real tasks |
| Personalization / AGENTS.md (docs) | ◐ v1 for the project; hierarchy completed in Session 3 |
| Permissions (docs) | ✓ full: levels, sandbox boundary, promote-as-trust-builds |

## Session 3 - AGENTS.md and skills: your taste, encoded

| Official source | Coverage |
|---|---|
| Build skills (docs) | ✓ full: SKILL.md anatomy, locations, triggering, $skill-creator, plugins |
| Personalization / AGENTS.md (docs) | ✓ completed: global/repo/subdir hierarchy, what belongs where |
| Codex for Builders (Academy) | ◐ skills portion |

## Session 4 - Design and content: make it yours

| Official source | Coverage |
|---|---|
| Prompting guide, applied | ✓ content workflows, critique loops |
| Codex for Work (Academy) | ◐ content/document workflows adapted to the site |
| Codex 101 iteration patterns | ✓ |

## Session 5 - Ship it: git, review, and going live

| Official source | Coverage |
|---|---|
| Code review (docs) | ✓ /review locally + Codex on GitHub PRs |
| CLI reference - git/review workflows | ✓ |
| Quickstart-to-production path | ✓ GitHub Pages publish + update loop |

## Session 6 - Power moves: automation, cloud, and beyond

| Official source | Coverage |
|---|---|
| Developer commands / codex exec (docs) | ✓ non-interactive runs, scripts, CI patterns |
| Codex cloud (docs) | ✓ delegation, parallel tasks, limits |
| MCP in Codex (docs) | ◐ overview + one working connection |
| Codex for Builders (Academy) | ✓ automation portions |

**Not covered by design:** enterprise/Business admin setup (course targets a personal Plus plan), API-key auth mode, and anything behind Academy certificates/assessments.
