# learn-codex-with-phoebe

Six 45-minute sessions with OpenAI's Codex, on a regular ChatGPT Plus subscription. The course has one running project: by Session 5, your personal website - about, product showcase, ideas - is live on GitHub Pages, built from scratch with Codex, and you understand every step that got it there.

**Live site:** https://phoebefu6.github.io/learn-codex-with-phoebe/

Sibling course: [learn-claude-with-phoebe](https://phoebefu6.github.io/learn-claude-with-phoebe/) - same format, Anthropic's Claude.

## The series

| # | Session | Difficulty | You leave with |
|---|---------|-----------|----------------|
| 1 | Meet Codex: your AI engineering teammate | 🟢 Easiest | Codex installed on Plus, GCOB prompting, your SITE_PLAN.md |
| 2 | First build: from plan to homepage | 🟢 Easy | AGENTS.md v1, a working homepage, the iteration habit |
| 3 | AGENTS.md and skills: your taste, encoded | 🟡 Medium | A design-system skill + content-voice skill that fire automatically |
| 4 | Design and content: make it yours | 🟡 Medium | Three real pages, polished, mobile-checked, accessible |
| 5 | Ship it: git, review, and going live | 🟠 Hard | Your live URL, the /review habit, the update loop |
| 6 | Power moves: automation, cloud, and beyond | 🔴 Hardest | codex exec scripts, cloud delegation, a weekly maintenance playbook |

Sources: OpenAI's official [Codex docs](https://learn.chatgpt.com/docs) and free [OpenAI Academy](https://academy.openai.com) courses (Intro to Codex, Codex for Beginners, Codex 101, Codex for Builders). Coverage mapping in [`materials/official-course-map.md`](materials/official-course-map.md) - each session teaches ~80% of its sources' working content. Everything runs on a personal ChatGPT Plus plan; no Team or Enterprise features required.

## How a session runs

Each page works for presenting live AND self-study afterwards:

- **Live / Self-study tags** on every concept card
- **Build-along demos** advancing the one running project - no toy exercises
- **Copy-paste prompt boxes** (one-click copy) with GCOB-structured asks
- **Click-to-zoom diagrams**, toggle accordions, reading progress bar, section dots, and a **projector zoom** button
- A **3-question check-yourself quiz** and a **cheat sheet** per session
- Instructor run-of-show in `materials/presenter-notes-0N.md`

## Repo layout

```
index.html              landing page - six sessions + choose-your-path
courses/                one HTML page per session
assets/                 shared stylesheet + page behavior (vanilla JS, no build)
materials/              presenter notes + official source coverage map
```

Static HTML/CSS/JS, no build step, prints cleanly.

---

Created and taught by Phoebe Fu.
