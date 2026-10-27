# Product Marketing Interview Kit

**Interview prep for product marketing roles, built to run with an AI agent.** For PMMs at every level, from first role to Director and Head of.

It covers the whole loop (recruiter screens, hiring managers, cross-functional panels, take-homes, CEO conversations, and offers) and is drawn from a prep system used across dozens of real PMM loops. It's packaged as skills, so your agent does the research and drilling while you focus on the stories only you can tell.

## What's inside

### Context (`context/`)

Your candidate file. Fill these in once and every skill uses them:

- `candidate-profile.md`: background, strengths, target roles, non-negotiables
- `story-bank.md`: your career stories in a format built for interviews
- `shareable-numbers.md`: which results you can say out loud, and which you can't
- `pipeline.md`: every company, stage, and outcome in one place

### Skills (`skills/`)

| Skill | What it does |
|---|---|
| [`role-decoder`](skills/role-decoder/SKILL.md) | Reads a JD and company signal. Is this PMM role strategic or content throughput? Who does it report to? Should you apply? |
| [`company-brief`](skills/company-brief/SKILL.md) | A sourced one-page brief on the company: products, pricing, customers, competitors, recent moves, and what it means for the role. |
| [`story-bank`](skills/story-bank/SKILL.md) | Turns your experience into impact-first stories with follow-up drills and a one-line memory trigger for each. |
| [`round-prep`](skills/round-prep/SKILL.md) | Prep for a specific round: what this interviewer is testing, likely questions, which stories to use, and questions to ask them. |
| [`mock-interview`](skills/mock-interview/SKILL.md) | Runs a realistic mock round, pushes with follow-ups, and scores your answers. |
| [`case-and-plan`](skills/case-and-plan/SKILL.md) | Take-home exercises, presentation cases, and the 30-60-90 day plan. |
| [`offer-review`](skills/offer-review/SKILL.md) | Questions to ask about an offer (especially startup equity), a negotiation sequence, and a walk-away line. |
| [`debrief`](skills/debrief/SKILL.md) | Post-round debrief, thank-you note, and pipeline update, while it's fresh. |

### Question bank

Kept inside the skills that use them, so they travel with the plugin:

- [Questions you'll be asked](skills/mock-interview/questions-youll-be-asked.md), grouped by what they're really testing
- [Questions to ask](skills/round-prep/questions-to-ask.md), by round
- [Offer and equity questions](skills/offer-review/offer-questions.md)

### Playbook

[The full interview loop](playbooks/interview-loop.md), from "this role looks interesting" to signed offer.

## Quick start

1. Clone or download this repo. Keep your copy **private**: it will hold your real stories and pipeline.
2. Fill in `context/candidate-profile.md` and draft three stories in `context/story-bank.md`. You can ask your agent to help: *"Read my resume and draft my story bank. Ask me for the numbers you don't have."*
3. When a role comes up: *"Read AGENTS.md. Run role-decoder on [JD link], then company-brief."*

**Claude Code (as a plugin):**

```
/plugin marketplace add Hyde-and-Larkin/product-marketing-interview-kit
/plugin install product-marketing-interview-kit@product-marketing-interview-kit
```

The plugin installs the skills, not your candidate file. Copy this repo's `context/` folder into the folder you prep in, or ask Claude to create it from the templates.

Also works in Cursor, Codex, or any chat app where you can upload the files. See [docs/how-to-use.md](docs/how-to-use.md).

## What makes it different

- **Built for product marketing.** Generic interview prep doesn't know that a PMM loop tests positioning judgment, cross-functional influence, and launch outcomes, or that half the battle is figuring out whether the role is strategic at all.
- **Interviews both ways.** Every round has questions *you* should be asking, because a wrong PMM role is expensive to leave.
- **Impact first.** Stories lead with the business result, then the challenge, then what you did. Interviewers decide early.
- **Verified research.** AI-generated company briefs get things wrong (wrong ticker, wrong funding round, wrong competitors). The company-brief skill sources and dates every fact.

## Related

The [Product Marketing Toolkit](https://github.com/Hyde-and-Larkin/product-marketing-toolkit) has the skills for doing the job once you've got it.

## About

Built by [Hyde & Larkin](https://hydelarkin.com) from years of PMM interview loops at companies from seed stage to public. Methods only: no company's confidential interview material is included.

Licensed under [CC BY 4.0](LICENSE.md).
