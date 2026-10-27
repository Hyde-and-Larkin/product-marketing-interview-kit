---
name: round-prep
description: "Prepare for one specific interview round: recruiter screen, hiring manager, cross-functional peer, panel, executive or CEO, or a skip-level. Covers what this interviewer is really testing, likely questions with suggested stories, a tailored 'why this role' answer, and questions to ask that fit the interviewer's background. Use before any scheduled conversation."
---

# Round Prep

> **Part of the [Product Marketing Interview Kit](../../README.md).** Read `context/candidate-profile.md` and `context/story-bank.md`, plus any `company-brief` and `role-decoder` output for this company.

## Inputs

- Company and role
- Round type and interviewer name/title (and LinkedIn summary, if the candidate has it)
- Anything the recruiter shared about the round

## What each round is really testing

| Round | They're deciding... | Lead with |
|---|---|---|
| Recruiter screen | Are you plausible, interested, and in range? | Clear 60-second pitch, crisp "why this role," comp handled calmly |
| Hiring manager | Can you do this job, and will you make my life easier? | Two strongest stories matched to the role's biggest problem |
| Product partner | Will you make my product more successful, or just ask for things? | Influencing-without-authority and data-changed-the-decision stories |
| Sales / CS partner | Will you give my team things they actually use? | Enablement that changed win rates or ramp, field empathy |
| Peer PMM | Are you good to work with, and do you raise the bar? | How you work, how you give and take feedback |
| Panel / presentation | Can you think on your feet and structure a problem? | See `case-and-plan` |
| Exec / CEO | Do you have a point of view on our business? | Company-level impact, your POV from the brief, strategic questions |
| Skip-level / final | Any reason not to hire? | Consistency, enthusiasm, good questions |

## Output

```
## [Company]: [Round] with [Interviewer, title]

**What they're testing:**

**Your 60-second intro, tailored:** (base version from the profile, last beat rewritten for this company)

**Why this role, why now:** (honest, specific to this company)

**Likely questions → story to use** (start from `../mock-interview/questions-youll-be-asked.md`)
| Question | Story | Note |

**Prepared answers for the two hardest questions:**

**Questions to ask** (5-7, tailored to this interviewer):
- About the role and what success looks like
- About the team and how PMM works with them
- About the business or strategy
- One that connects to the interviewer's own background

**Watch-outs:** (gaps they may probe, topics to steer around, comp handling if it comes up)
```

## Tailoring questions to the interviewer

Generic questions waste the slot. Use the interviewer's role and background:

- A Product lead: "Who owns positioning today, PMM or Product? How do you want that to work?"
- A sales leader: "Where do reps lose deals today, and what do they wish they had?"
- An exec with a notable past company: "You saw [past company] scale through [stage]. What patterns do you see here?"
- Everyone: "What would I need to have accomplished in 12 months for you to call this a great hire?"

Pull from `questions-to-ask.md` in this folder and rewrite for the person.

## Guardrails

- Map every likely question to a real story. If there's no story for an important question, say so; that's a gap to fix before the round.
- Don't script answers word for word. Bullets and triggers; the candidate should sound like a person.
- Recruiter screens: suggest deferring a specific number on comp until scope is clear, unless the candidate prefers otherwise. See `offer-review`.
