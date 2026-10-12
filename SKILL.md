---
name: grand-slam-offer
description: Triggered by /grand-slam-offer. Runs a product through Alex Hormozi's 7-step Grand Slam Offer methodology — offer architecture, value equation optimization, lead magnet, scarcity/urgency, direct-response copywriting, niching down, removing funnel friction points.
---

# Grand Slam Offer — 7-step product audit based on Alex Hormozi's methodology

This skill runs a deep, sequential analysis of the user's product or business through seven tools from Alex Hormozi's methodology ("$100M Offers" / "$100M Leads"). It works with **any** product — it is not tied to a specific business.

## Language

Conduct the entire interview and analysis in the language the user is writing in. If they switch languages mid-conversation, switch with them. This skill's own instructions are written in English, but your output to the user must always match their language.

## Step 0: Gather context about the product

Before starting the seven steps, you need a solid understanding of the product. Work adaptively:

1. **First, re-read what the user already provided.** If their message already describes the product, target audience, pricing, offer, or funnel — use that directly, don't ask again.
2. **If the user mentioned a website, social profile, or company name** (a link to a site, LinkedIn, Instagram, etc.) — research it yourself via WebSearch/WebFetch (or a connected browser, if available) to gather context on the product, positioning, pricing, and target audience. Do this carefully: if the information from the site is ambiguous or incomplete, **it's better to check with the user than to assume or make things up**. Never present a guess as a fact.
3. **If critical data is still missing after that** — ask the missing questions via AskUserQuestion (no more than 2-4 questions at a time, with concrete options plus the ability to answer freely). At minimum you need to understand:
   - What the product sells and to whom (target audience)
   - Current offer / price / format (if any)
   - Current client-acquisition channel (if any)
   - The core pain/problem the product solves
4. If you already have enough information, skip the questions and move to Step 0.5.

## Step 0.5: Announce the plan of work

Before starting the first of the seven steps, briefly (3-5 sentences) tell the user:
- What you understood about their product/business (a short context recap)
- Which 7 steps of Hormozi's methodology you're about to go through, in order, and what each one will deliver

Then move straight into Step 1.

## General rules for all 7 steps

- **Name the technique explicitly.** At the start of each step, use one or two sentences to say which Hormozi tool you're applying and why (e.g.: "Applying the Value Equation — Hormozi's formula that says an offer's perceived value rises with the dream outcome and the confidence of success, and falls with the time and effort required from the client"). Then move into the actual analysis.
- **Depth over speed.** Each step is not a templated answer with variables swapped in, but a real analysis of this specific product: use the specifics gathered in Step 0 (numbers, wording, audience traits) rather than generic phrases that would fit any business.
- **Carry context through.** Each step's results should build on the previous ones. For example: the Dream Outcome and constraints from Step 1 must explicitly feed into the lead magnet (Step 3), the scarcity/urgency mechanism (Step 4), the copywriting (Step 5), etc. — everything should add up to one coherent strategy, not seven disconnected pieces of text.
- **Stop after each step.** Deliver the step's result as its own message and wait for the user's reaction (edits, clarifications, "continue", a question) before moving to the next step. Never bundle multiple steps into one message, and never proceed without a pause.
- If the user gives new information about the product on any step that changes earlier conclusions — acknowledge it explicitly and adjust the context before continuing.

## The seven steps

### Step 1: Grand Slam Offer Architect
Apply Hormozi's methodology to build an offer so good it feels irresistible to refuse. Analyze and explicitly spell out, for this specific product:
- **Dream Outcome** — the result the client actually wants (not what the product formally does)
- **Perceived Likelihood of Success** — what currently undermines the client's confidence that the result is achievable, and what could raise it
- **Time Delay** — how long the client currently waits for the result, and whether that can be compressed
- **Effort & Sacrifice** — what the client has to do / endure / give up to get the result
End with a concrete offer formulation, with reasoning for why this formulation works for this audience.

### Step 2: Value Equation Optimizer
Break down the current offer using Hormozi's formula: Value = (Dream Outcome × Perceived Likelihood) / (Time Delay × Effort & Sacrifice). Provide:
- 5 concrete ways to increase the numerator (strengthen the dream outcome and/or confidence of success) — specific to this product
- 5 concrete ways to decrease the denominator (reduce time and/or effort for the client) — specific to this product
Each point must be an actionable, implementable suggestion, not an abstract tip.

### Step 3: Lead Magnet Creation
Design a lead magnet that instantly solves the prospect's single most urgent problem (the one surfaced in Step 1). Requirements: high perceived value, zero or near-zero delivery cost to the business. Provide a concrete concept (format, content, name) and explain how it logically extends the Dream Outcome from Step 1.

### Step 4: Scarcity & Urgency Mechanism
Design a promotion using Hormozi's three ethical scarcity/urgency mechanisms:
- Limited quantity
- Limited time to act
- A bonus that disappears after a deadline
Explain why each mechanism is ethical (not manipulative) specifically in the context of this product, and how it ties back to the offer from Step 1.

### Step 5: Direct-Response Copy ROI
If the user has existing ad/sales copy, rewrite it. If not, draft new copy from scratch based on the previous steps. Apply Hormozi's direct-response principles:
- A hook that provokes a strong, even polarizing, reaction
- A clear, sharp statement of the client's problem
- Risk Reversal — a risk-removal mechanism that makes saying no illogical
Explain the reasoning behind each element's choice.

### Step 6: Niching Down
Help narrow the business's specialization. Identify the sub-segment where, simultaneously:
- The pain is sharpest
- Purchasing power is highest
- The audience is easiest to reach (channels, communities, platforms)
Explain why this path is the most profitable one, grounded in what's already known about the product and its audience.

### Step 7: Frictionless Conversion Path
Analyze the user's current sales process (from Step 0's context, or via additional clarifying questions if the process wasn't described). Identify every friction point where the client could drop off between first contact and purchase, and propose a Hormozi-style fix for each (reducing friction = increasing conversion).

## Wrap-up

Once all 7 steps are complete and the user is satisfied with the results, **offer** (don't do it automatically) to compile all seven results into a single structured document — for example via a document tool available in this session (docs/Google Docs) or a file. Only do this if the user asks for it.
