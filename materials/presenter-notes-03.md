# Presenter notes - Session 3: Agents and skills

## Before the session
- Rehearse the $skill-creator flow end to end the night before - skill scaffolding output changes between versions and you want no live surprises.
- Prepare a deliberately BAD skill description ("helps with stuff") and a good one, to demo why triggering fails - the contrast is the lesson.
- Check attendees' sites have an AGENTS.md from Session 2; have a quick /init catch-up path for stragglers.
- Know the .agents/skills folder layout cold: SKILL.md, where it lives, how plugins bundle it. You will be asked.

## Timing (45 min)
- 0-3: Welcome, where we are in the build
- 3-11: AGENTS.md hierarchy - global vs project, what belongs where
- 11-16: Skills concept - encoded taste that triggers when relevant
- 16-27: Demo 1 - build $site-design-system with $skill-creator
- 27-36: Demo 2 - hand-write $content-voice (small, from scratch)
- 36-42: Demo 3 - trigger testing, implicit and explicit
- 42-45: Homework + Q&A

## Demo run-of-show
- Demo 1: extract the design system FROM their existing homepage - "look at my site and write a skill capturing its design rules." Their taste, formalized.
- Demo 2: hand-writing $content-voice demystifies skills - it is just a markdown file with a good description. Keep it under 20 lines.
- Demo 3 key beat: the implicit-trigger test moment - ask for a new element WITHOUT naming the skill and watch the design system apply itself. That silent trigger is the payoff of the whole session. Never cut it.

## Watch for
- Vague skill descriptions = skills that never fire. This is THE stumble of the session. If someone's trigger test fails, the description is almost always the culprit - fix it live as a teaching moment.
- People stuffing everything into AGENTS.md instead of skills. Rule of thumb: always-true goes in AGENTS.md; sometimes-relevant becomes a skill.
- Over-engineering: someone will start a 200-line skill. Redirect: short skills trigger better.

## Cuts if long
- Cut Demo 2's hand-written skill to homework (keep the explanation of what is inside a SKILL.md).
- The AGENTS.md hierarchy discussion can compress to the one-table version.
- Never cut Demo 3's trigger test - it is the proof the session worked.
