# The Quiet Creator — AI Coaching Companion

[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-1.0-blue)](https://agentskills.io)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](LICENSE)
[![Amazon Book](https://img.shields.io/badge/Amazon-Book-orange)](https://www.amazon.com/dp/B0DT94SPRB)

![The Quiet Creator — AI Coaching Companion](assets/hero.png)

> An AI Agent skill that coaches introverts through real situations — speaking up in meetings, setting boundaries, preparing for high-stakes conversations. Load it once. Use it whenever you need it.

---

## What It Does

This skill turns your AI Agent into a coaching companion for introverts. It doesn't encourage you to "be louder." It gives you structured frameworks (PREP, 3-Door Decision, Energy Audit, Introversion Map) and runs live exercises — roleplaying difficult conversations, practicing the 60-Second Pivot, building a Quiet Win Log over time.

It adapts to your energy today, catches self-critical language and reframes it on the spot, and maintains a journal across sessions so growth is trackable.

---

## Install

```bash
npx skills add ringofai/the-quiet-creator
```

Then say:

> *"I have a difficult conversation coming up. Let me practice."*
> *"I keep getting interrupted in meetings. What do I do?"*
> *"I feel drained and I don't know why. Let's audit my energy."*

---

## Session Types

| Scenario | What happens |
|:---------|:-------------|
| **I have a specific situation** | 10-minute coaching session. One exercise. One takeaway. Done. |
| **I just want to understand myself** | Runs the Introversion Map. You get a personal profile. |
| **I don't know where to start** | Runs an Energy Forecast. The topic emerges from your week ahead. |

All sessions log a Quiet Win. Journal is stored locally at `~/.the-quiet-creator/journal.md`.

---

## What It Handles

| Situation | Framework |
|:----------|:----------|
| Put on the spot — go blank | PREP (Pause, Reframe, Engage, Proceed) |
| Should I go or should I skip? | 3-Door Decision Model |
| Unknown energy drains | Energy Audit |
| Can't seem to improve | Quiet Win Log (tracked across sessions) |
| Need to say no | Boundary Rehearsal (live roleplay) |
| Self-critical spiral | The Reframer (automatic, always on) |

---

## How It Differs from the Book

The book explains concepts. This skill runs them live. Same frameworks, same philosophy — interactive, adaptive, persistent.

---

## Edge Cases Handled

| Situation | Behavior |
|:----------|:---------|
| User is skeptical | 2-min micro-session. No commitment. |
| User gets emotional mid-session | Pauses coaching. Offers grounding or exit. |
| User is from a non-Western culture | Adapts advice to cultural norms — won't push "speak your truth" where it's inappropriate. |
| User has ADHD or is highly sensitive | Offers walking exercises, timers, scribble-based reflection instead of sitting still. |
| User says "this is helpful" but gives no specifics | Detects performative agreement. Asks for one concrete takeaway before closing. |
| User returns after a long gap | Reads journal. Picks up where they left off. |

---

## File Structure

```
the-quiet-creator/
├── SKILL.md         ← Agent instructions
├── README.md        ← You are here
├── LICENSE
└── .gitignore

~/.the-quiet-creator/journal.md   ← Your session history
```

---

## ⭐ Like This?

Star the repo. It helps other introverts find a coaching system, not just encouragement.

## License

[CC BY 4.0](LICENSE) — Free to share and adapt with attribution to Ringo Fai.
