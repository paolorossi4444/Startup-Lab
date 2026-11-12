---
name: financial-model
description: Builds a three-to-five year operating model in Excel — monthly, with quarterly and
  annual rollups — driven from volumes and prices rather than growth rates, with an engine that
  fits the business model, a hiring plan role by role, cash kept separate from revenue, a KPI
  tab, sensitivities on the levers that move runway, and checks that must tie. Reports burn,
  runway and the date to start raising. Use when someone asks for a financial model, a business
  plan, projections, a P&L forecast, burn and runway, or how long their money lasts.
---

# Financial model

## Purpose
Say how much cash this business consumes, how long it lasts, and what has to be true for the
plan to hold — in a model whose every number can be traced to an assumption someone can argue
with.

## Inputs
- **Required:** what is sold, to whom, at what price, and what exists today in cash and people.
- **Read first where they exist:** the business model for pricing, unit economics and the
  revenue model; the market sizing for the reachable population; the competition work for what
  acquisition costs in this market.
- **If there is history:** actuals override assumptions. Put them on the same timeline as the
  forecast, with the handover month marked.
- **Missing:** ask at most three questions — the ones without which the model cannot be built —
  then proceed with labelled assumptions.

## How to reason
A model is an argument about cause and effect, not a spreadsheet of hopeful numbers. Its value
is that someone can disagree with one input and see exactly what changes.

- **Drive revenue from volume and price**, never from a growth rate. "Twenty per cent a month"
  hides the question of who is buying and why.
- **Separate inputs from calculations.** No number lives inside a formula. Change one cell and
  the model moves.
- **Cash is the output that matters.** Profit on a slide has never paid a salary.
- **Every assumption carries a note** saying where it came from: a source, a comparable, a
  conversation, or openly the founder's guess.
- **Be pessimistic about time, not about ambition.** Hiring, sales cycles and product take
  longer than planned; that is the error that kills models, not the size of the market.
- **A model that cannot be wrong is useless.** The checks have to be able to fail.

## 1. Fit the engine to the business
Read the business model first, then choose the revenue engine and say why. Do not impose one
structure on every business:

- **Recurring**: customers acquired by cohort, each with its own retention curve; revenue is
  the sum of surviving cohorts. Churn is modelled by month since acquisition, not as a flat
  monthly rate, because early churn is always higher and a flat rate hides it.
- **Transactional or take rate**: volume of transactions, value per transaction, rate taken.
- **Project or services**: projects won, average size, delivery over months, people needed per
  project. Capacity is the constraint, so model it.
- **Hardware or physical**: units, bill of materials, production cost, inventory, and the cash
  tied up before a unit is sold.
- **Marketplace**: both sides modelled separately, with liquidity as the link.

Most businesses are a mixture. Model each line with its own engine and consolidate. State which
engine was used for which line and why.

## 2. Horizon and shape
Thirty-six to sixty months, monthly. Every P&L line also rolls up to quarterly and annual views
of the same numbers, never recalculated separately. Monthly is where decisions are made; annual
is what goes in a deck.

## 3. The assumptions tab
One tab holds every input, grouped: pricing, volumes, conversion, retention, salaries by role,
cost to serve, marketing by channel, overheads, payment terms, taxes. Where an assumption
changes over time, give it a value per year rather than burying a trend in a formula.

Beside each input: a short note on where it came from and how confident it is. Where it came
from a comparable company, name the company and the source. Where it is a guess, write that it
is a guess. An assumption tab with no notes is a list of numbers nobody can challenge.

## 4. Revenue
Build it bottom-up:

1. **Acquisition**: how many customers arrive each month, by channel, from the spend and the
   conversion rates of that channel — not from a target.
2. **Retention**: the cohort curve, with early months higher than later ones.
3. **Price and expansion**: price per customer, what grows it over time, discounting.
4. **Revenue** as the consequence of the three, split by product line and segment.

Never start from a revenue target and work backwards. If a target exists, model honestly and
then show what the target would require — that comparison is the useful part.

## 5. People
The largest cost in almost every early company, so model it as its own engine: one row per
role, with department, start month, fully-burdened cost including employer contributions, and
any change in cost over time.

**Apply a hiring lag.** A role budgeted for month six is filled in month eight or nine. Models
that hire on the planned date understate burn and overstate runway, which is the single most
common error in startup models. State the lag used.

## 6. Other costs
- **Sales and marketing**: bottom-up by channel — spend, cost per lead, conversion — with a
  backup block per channel showing how the numbers were built. Not a percentage of revenue.
- **Cost to serve**: infrastructure, third-party fees, support, implementation. This is what
  makes gross margin real.
- **Overheads**: rent, tools, legal, accounting, insurance, and the things founders forget.

## 7. Cash
Revenue is not collection. Model them separately:

- **Payment terms**: when invoices are actually paid, upfront or in arrears, annual or monthly.
- **Working capital** where it exists: inventory, receivables, payables. For a pure software
  business with upfront billing this is almost nothing; for anything physical it decides
  whether the company survives.
- **The cash statement**: opening cash, operating cash flow, any funding received, closing cash,
  month by month.

Then the two numbers that matter: **runway in months and the date cash reaches zero**, and
**the date to start raising**, which is roughly six months earlier. Put both at the top of the
output, because a founder who starts raising late negotiates without alternatives.

## 8. KPI tab
Computed from the model, not entered by hand. Include what applies: MRR and ARR, growth,
customer and revenue churn, gross and net revenue retention, customer acquisition cost by
channel, payback period, lifetime value, the ratio of lifetime value to acquisition cost, the
magic number, burn multiple, gross margin, and revenue per employee.

Two rules for this tab, because metrics mislead more than they inform when misread:

- **Each metric carries its definition**, written next to it. Lifetime value and the magic
  number are each calculated several ways, and two people reading the same cell must mean the
  same thing.
- **Each metric is marked observed or assumption-driven.** In the first year, retention-based
  figures come from the founder's own churn assumption, not from data. Where there is not
  enough history for a metric to mean anything, the cell says so rather than producing a
  number.

## 9. Sensitivity, and the question in reverse
A single honest case, built properly, which the founder then edits. Alongside it:

- **One-variable sensitivity** on the two or three inputs that move runway most, shown as a
  small table: how many months of cash each one costs or buys.
- **A named downside** in one line rather than a separate scenario: what happens if hiring
  slips three months and first revenue slips six.
- **The reverse question**: what the main lever would have to be for the cash to last
  twenty-four months. A target is more useful than an optimistic case, which nobody uses to
  decide anything.

## 10. Checks
A tab of tests that can fail, reported whether they pass or not:

- Closing cash equals opening cash plus the period's flows, every month
- Headcount cost in the P&L equals the hiring plan
- Annual and quarterly rollups equal the sum of their months
- No negative cash balance left unexplained
- Every assumption cell is referenced by something, and no formula contains a typed number

If a check fails, say so in the chat reply rather than leaving it in the file.

## Output in the chat
Five lines, no tables:

- Monthly burn now and at the end of the horizon
- Runway in months and the date cash reaches zero
- The date to start raising
- The lever that moves runway most, and by how much
- What the plan implies must be proven before the next round

Plus any failed check, and any assumption with no evidence behind it.

## Deliverable
**The model (.xlsx)**, built with the xlsx skill: a cover with subject and date; the assumptions
tab with its notes; the calculation tabs, one per engine; outputs for the P&L monthly with
quarterly and annual rollups, the cash statement, and the KPI tab; the sensitivity block; the
checks tab; and the backup blocks showing how each marketing channel and each built-up figure
was derived. Inputs are visually distinct from calculations.

**The summary (.docx)**, built with the docx skill, named
`<company-slug>-financial-model-<YYYY-MM-DD>.docx`, short: the headline numbers, the main
assumptions with where each came from, what the model does and does not include, which input to
change first, and the caveats.

## Rules
- Never drive revenue from a growth rate. Volumes and prices, always.
- Never put a number inside a formula. Every input lives in the assumptions tab.
- Apply and state a hiring lag.
- Keep revenue and cash collection separate.
- Never produce a valuation, a discounted cash flow or a terminal value here. Runway and funding
  need belong in this model; what the company is worth does not.
- Mark every metric as observed or assumption-driven, and refuse to compute one that the history
  cannot support.
- Every assumption carries a note on its origin, including when the origin is a guess.
- Report failed checks in the reply, not only in the file.
- Be pessimistic on timing and honest on ambition, never the reverse.
