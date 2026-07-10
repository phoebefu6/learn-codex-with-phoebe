# Presenter notes - Session 5: Ship it

## Before the session
- GitHub accounts BEFORE the session - chase this hard, twice, starting a week out. Account creation + email verification live eats 15 minutes you do not have. Include a one-line signup link in both reminders.
- Verify GitHub Pages publishing on a fresh test repo the day before - the settings path moves around and propagation delays vary.
- Pre-plan your sabotage for the /review demo: a subtle-but-findable bug (broken relative path, unclosed tag in a nav) planted live but rehearsed.
- Know the git-credential dance for macOS and Windows - authentication is where shipping stalls.

## Timing (45 min)
- 0-3: Welcome - "today it goes live"
- 3-10: Git concepts via Codex - commit, push, remote (Codex runs the commands, they approve)
- 10-20: Demo 1 - repo created, first commit, pushed (Codex-driven)
- 20-30: Demo 2 - sabotage-then-/review
- 30-42: Demo 3 - GitHub Pages on, site LIVE, phones out
- 42-45: The URL-sharing moment + homework

## Demo run-of-show
- Demo 1: let Codex drive git entirely - "put this project on GitHub as a public repo" - with attendees approving each command and asking "what does that do?" at least once. Git through an agent is the gentlest git onboarding that exists.
- Demo 2: sabotage the site yourself on the projector, then run /review and let it catch you. The lesson lands harder when the presenter is the one caught.
- Demo 3 key beat: the live URL on their PHONE - the phone screenshot moment. Everyone loads their own site on their own phone and screenshots it. This is the emotional peak of the entire course. Protect it at all costs; budget slack for Pages propagation delay (have people set up while waiting).

## Watch for
- Missing GitHub accounts (see prep) - the single biggest session killer.
- Auth failures mid-Demo 1: have the personal-access-token / browser-auth flow ready to demo.
- Pages propagation can take a few minutes - fill with the /review demo debrief, never with silence.
- Anxiety about "my site is not good enough to be public." Preempt: shipping early and iterating IS the method; repo can be renamed, site can be updated in minutes - that is next session's whole point.

## Cuts if long
- Git concept theory compresses to nearly zero - Codex explains commands inline anyway.
- Demo 2's /review can shrink to one planted bug instead of two.
- Never cut the phone moment. If everything overruns, everything else gives way first.
