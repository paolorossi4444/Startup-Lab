---
name: gtm
description: Works out how the first hundred customers are actually reached — whether the price
  can support the sales motion at all, which motion fits this buyer and this contract value,
  which two or three channels to run and in which order, the funnel arithmetic needed to hit the
  plan, and how to test a channel with a kill threshold set in advance. Covers reaching the
  first hundred customers, not scaling beyond them. Use when someone asks about go-to-market,
  how to find customers, which channels to use, a sales motion, or a launch plan.
---

# Go to market

## Purpose
Decide how customers are actually reached and whether the economics of reaching them work —
before spending a year finding out they do not.

## Scope
This covers getting to roughly the first hundred customers. Scaling a sales team, expansion
revenue, partner programmes and brand belong to a later stage and are deliberately out.

## Inputs
- **Required:** what is sold, to whom, and at what price.
- **Read first where they exist:** the ICP work for where this segment can be found and what
  triggers a purchase; the business model for price and unit economics; the competition analysis
  for how rivals acquire; the financial model for the customer numbers the plan assumes.
- **Missing:** ask at most two questions, then proceed with labelled assumptions.

## How to reason
Distribution is not what happens after the product is built. For most companies it is the
harder of the two problems, and it is decided by arithmetic before it is decided by creativity.

- **The price has to pay for the motion.** Every way of reaching a customer has a cost, and if
  that cost is not well below what a customer is worth, no amount of execution fixes it. This
  is the first thing to check and it can end the discussion.
- **Go where the buyer already is**, rather than where it is comfortable to be.
- **Two or three channels, done properly.** A plan with eight channels is a plan with none.
- **Decide the kill threshold before testing a channel**, for the same reason stop lines are set
  before experiments elsewhere.
- **Before product-market fit, a launch is mostly irrelevant.** What matters is the first
  conversations and whether anyone pays. Launch moments matter later.

## 1. Can the price carry the motion?
Do this first. Take the annual value of a customer from the business model, then set it against
what each way of reaching them costs:

- **Self-serve** costs almost nothing per customer but requires the buyer to find you, decide
  alone and pay without talking to anyone.
- **Founder-led sales** costs the founder's time: count the hours per closed deal honestly and
  price them.
- **Inside sales** costs a salary plus ramp, and that person must close enough to cover it
  several times over.
- **Field sales or long enterprise cycles** cost a salary, travel, months of pipeline and often
  a sales engineer.
- **Channel or partner** costs a share of revenue and the effort of enabling someone else.

As orientation, low contract values point to self-serve, middling ones to self-serve with
assistance, and high ones to direct selling — but treat the arithmetic as the rule and these
bands as a sanity check, since they vary by market and date quickly.

Then say plainly whether any motion works at this price. If the only motion that reaches this
buyer costs more than the customer is worth, the problem is the business model, not the
marketing, and the honest conclusion is to change the price, the segment or the product.

## 2. The motion
Choose one and say why the others do not fit:

| Motion | Fits when | The lever |
|---|---|---|
| Self-serve | The buyer can decide alone and value is obvious in minutes | Product and onboarding |
| Self-serve with sales assistance | Buyers start alone but need help to expand or approve | Triggered human contact |
| Direct sales | Few buyers, large contracts, committee decisions | Pipeline and relationships |
| Community | Practitioners congregate and recommend each other | Participation, over months |
| Partner or channel | Someone else already sells to this buyer with trust | Enablement and incentives |

Most companies run one motion first and add a second later. Name the first, and the condition
that would make the second worth starting.

## 3. Channels, in three kinds
Pick two or three in total, not two or three per kind.

- **Owned** — the list, the site, a community you run. Slow to build, cheap to use, and yours.
  Build these from the start even while using others.
- **Rented** — platforms where the audience is someone else's: search, social, marketplaces,
  app stores. Faster, and the terms can change under you, so use them to drive people into the
  owned ones.
- **Borrowed** — someone else's audience lent for a moment: a podcast, a guest piece, a
  community where you are a guest, a co-marketing partner. The fastest route to a specific
  audience and the hardest to repeat at will.

For each channel chosen, say why this buyer is there, with the evidence — from the ICP work,
from the competition analysis, or from interviews.

## 4. The funnel arithmetic
This is where optimistic plans break visibly. Work backwards from the customer numbers the
financial model assumes:

Customers needed, divided by close rate, gives qualified opportunities; divided by the
conversion from first contact, gives contacts; divided by the response rate of the channel,
gives the volume of outreach or traffic required. Do it per month.

Then ask whether that volume is possible with the people and the budget available. Where it is
not, say so and give the options: a different channel, a smaller plan, or a higher price per
customer. A plan that requires four hundred conversations a month from one founder is not a
plan.

Use real conversion figures where they exist; where they do not, use a range from comparable
businesses, cite it, and mark it as an assumption.

## 5. The first ten, then the first hundred
The first ten customers are for learning, not revenue, and they usually come from places that
do not scale: people already known, introductions, and direct approaches to the people who have
already hit the limits of whatever they use now.

Write the sequence: where the first ten come from by name or by list, what changes once the
pattern is clear, and which channel takes over for the next ninety. Say what would have to be
true for the unscalable route to be replaced.

## 6. Testing a channel
For each channel being tried, before starting:

- **The question it answers** — can this channel reach this buyer at a cost that works
- **The volume needed** for the result to mean anything, and the time it will take
- **The cost** of the test
- **The threshold** that counts as working, as a number
- **The kill line** that ends it, decided now so it cannot move later

Run one channel test at a time where possible. Two at once with small volumes tells you
nothing about either.

## 7. What a launch is worth here
Say honestly whether a launch moment helps this business at this stage. Before there is
evidence that customers stay, attention is mostly wasted: it brings people to something that is
not ready to keep them, and the attention cannot be spent twice.

Where a staged release does make sense — a small internal group, then a handful of friendly
users, then a wider early access — set what each stage must show before the next begins, and
plan what happens in the thirty days after rather than on the day itself.

## Output
Under 1500 words.

1. **Can the price carry the motion** — the arithmetic, and the verdict.
2. **The motion chosen**, and why the others do not fit.
3. **The two or three channels**, with the evidence that this buyer is there and the order to
   run them in.
4. **The funnel**, working back from the plan to the volume required, and whether that volume
   is achievable.
5. **The first ten and the first hundred** — the sequence and the handover.
6. **The tests** — for each channel, the threshold and the kill line.
7. **What this means for the plan** — including where the financial model's customer numbers
   are not reachable by the channels available.

## Deliverable
A Word document (.docx), built with the docx skill, named
`<company-slug>-gtm-<YYYY-MM-DD>.docx`. In the chat: whether the price carries the motion, the
motion and first channel, and the volume of outreach the plan requires per month.

## Rules
- Check that the price can carry the motion before anything else, and say plainly when it
  cannot.
- Two or three channels in total. Reject a plan that lists more.
- Always do the funnel arithmetic back to the plan's customer numbers, and say when the required
  volume is not achievable by the people available.
- Set the kill line for every channel test before the test starts.
- Count the founder's time as a real cost in any motion that uses it.
- Use real conversion rates where they exist; where they do not, cite a comparable range and
  mark it as an assumption. Never state a conversion rate without saying where it came from.
- Say when a launch would not help. Attention before retention is spent attention.
- Do not plan beyond the first hundred customers here.
