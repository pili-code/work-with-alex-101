---
name: work-with-alex
description: A team-wide guide for working with Alex (Alessandro Alter), TDP cofounder. Use whenever anyone is prepping an update, report, review, agenda, or ask for Alex, deciding how to present numbers or a recommendation to Alex, or asking "how do I present this to Alex" / "make this Alex-ready" — in any function (design, engineering, ops, sales/GTM). Alex is business- and numbers-oriented: he wants the conclusion first, a verified number behind every claim, and a decision to make.
---

# Work with Alex 101

A guide for the whole team on working with Alex (Alessandro Alter), TDP cofounder. Not function-specific
— the way he thinks, communicates, and decides is consistent across design, engineering, ops, and GTM.
Grounded in a study of 10 real meeting transcripts (see `analysis/gtm-sync-analysis.md`), but the
principles apply to every interaction.

**Who Alex is, in one line:** business- and numbers-oriented, fast, hands-on, allergic to fluff. He
wants the conclusion first, a verified number behind every claim, and a decision to make.

**When helping anyone prep for Alex, enforce the checklist at the bottom of this file.**

## 1. Communication
- **Lead with the conclusion. Never narrate the process.** "Just give us the conclusion so we can talk about what matters." Backstory goes in an appendix only if asked.
- **Concise and structured** — bullets over paragraphs. "Be more structured and concise; focus on key business results."
- **Small, specific asks get fast answers.** For feedback, send a pointed question on Signal, not a wall of text: "What do you think about the first paragraph?" beats "please review this doc."
- **Right channel:** Signal for quick/urgent feedback, the team channel for routine. Don't book a call for what a message can resolve.

## 2. Reporting numbers (where trust is won or lost)
- **Every claim gets a number** (conversion rate, $, count). No number = he stops trusting it.
- **Every number gets a verifiable source.** "Estimated" ≠ "tracked," and he catches the difference.
- **Show trends (▲/▼), not vanity totals.** He wants the delta vs last period.
- **Never say "tested" unless you can show it worked.** The rule above all others:
  > "Don't tell me it's tested and then it's not. Because next time you tell me something, I need to ask you seven questions to trust the answer." (May 14)
  One verified number beats five estimated ones. Reliability is the currency.
- **Unit economics** where relevant: CAC, break-even, margin, revenue quality.

## 3. Getting a decision
- **Bring a recommendation, not an open question.** "Here's the situation, here's what I'd do, agree?"
- **Frame experiments test-and-kill** — he's biased to action. Give a confidence level and a kill criterion. "Why decide up front it'll fail? Test it, we can always kill it."
- **Separate must-have from nice-to-have** — he protects focus hard.

## 4. What frustrates him (steer clear)
- Long narratives that bury the point.
- Claiming something is tracked/tested/done when it isn't verified.
- Vanity metrics with no source, no trend, no action.
- Surfacing a problem with no proposed next step.

## 5. What Alex most often asks for (pre-empt these)
Ranked by how often they recur across meetings:
1. **Attribution** — "Where did it come from?" Every lead/result needs a verifiable source.
2. **Conversion rate + funnel math** — each step as a %. "Where's the bottleneck? Where's the leverage?"
3. **"Did you TEST it? Is it tracked?"** — verified, not estimated. State "tracking confirmed: Y/N + how."
4. **Trends** — "Send me numbers" with up/down vs last period.
5. **Conclusion first / what matters** — must-have vs nice-to-have.
6. **Unit economics** — "What conversion rate makes us break even?"
7. **Data → action** — "Why aren't they converting? What do we DO about it?"
8. **Strategic zoom-out** (occasionally) — "What are we trying to achieve? Where is TDP going?"

## Pre-send checklist (enforce before anything reaches Alex)
- [ ] Conclusion at the top
- [ ] Every number has a verified source (not estimated-as-tracked)
- [ ] Every metric has a trend (▲/▼ vs last period)
- [ ] Every finding has a proposed action
- [ ] Decisions flagged with a recommendation
- [ ] It's short

## Source & refresh
Evidence: `analysis/gtm-sync-analysis.md` (10-call study). To refresh, run the `/fireflies` keyword
search `GTM Sync` (retry on 408 timeout) to get transcript IDs, then fetch each by ID — direct ID
fetch bypasses the API's ~2-week list window — and re-extract Alex's lines.
