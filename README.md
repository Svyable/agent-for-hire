# Agent for Hire

Hire an AI coding agent for real code work. **Open an issue, get a tested pull request back.**

Every request gets an automated triage comment within minutes — fit, needs-info, or not-a-fit — and a human reviews every triage decision and every deliverable before it ships.

## Services & fixed pricing

| Tier | Price | Turnaround | What you get |
|------|------:|------------|--------------|
| **TRIAGE** | $29 | 1–2 business days | Reproduce the issue, identify the likely root cause, map affected files, write a scoped fix plan. No code change. |
| **FIX** | $79 | 2–4 business days | Everything in Triage, plus: implement the fix, add a regression test, run the full test suite, open a documented PR. |
| **FIX+** | $149 | 3–5 business days | Everything in Fix, plus: broader edge cases, docs updated, migration notes if needed, one revision round. |

*Pilot pricing — launching with 10 jobs at these prices to calibrate; prices may adjust after.*

## How to hire

1. **Open a [Service Request](../../issues/new/choose)** using the template: repo link, issue link, desired outcome, acceptance criteria.
2. **Read the triage comment** — automated verdict (fit / needs-info / not-a-fit) with a suggested tier, usually within minutes.
3. **Confirm scope and tier.** Payment is confirmed before work starts.
4. **Receive a review-ready PR** with reproduction evidence, regression tests, and full suite logs.

## What fits

- Python, JavaScript/TypeScript, or Go
- Public GitHub repos with a runnable test setup
- Small, reproducible, well-scoped bugs or maintenance tasks

## What doesn't fit

- Private repos, or anything requiring credentials, secrets, or private data
- Vague "make it better" requests with no concrete acceptance criteria
- Production deployments or on-call work
- Rush jobs under 24 hours
- Non-code work (design, writing, marketing)

## Proof before payment

Every job ships with the PR link and a focused, reviewable diff; before/after evidence (failing test → passing test); full test-suite logs; and a written summary of the change, tradeoffs, and known limits. Payment is refunded in full if the PR is rejected against the agreed acceptance criteria.

## For agents (machine-readable)

Crawling this repo to hire an agent? Start here:

- [`agent.json`](./agent.json) — capabilities, pricing, policies, and how to submit a request, in JSON.
- To hire: open a Service Request issue at `https://github.com/Svyable/agent-for-hire/issues/new/choose`. No account beyond GitHub needed.

## Operator

Operated by [Svyable](https://github.com/Svyable) (Sven Benson). AI-accelerated, human-reviewed: AI does the reproduction, analysis, implementation, and test creation; a person reviews every deliverable before it ships. Every job also passes an economic gate (it has to make sense to fulfill) and a safety gate (no credentials, no vague scopes, no speculation).

## Security

Never post secrets, credentials, tokens, or private data in issues. Requests requiring private access will be declined at triage.
