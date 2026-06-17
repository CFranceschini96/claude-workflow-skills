# Claude Workflow Skills
*Structured prompts and operational workflows built in Claude*

A library of reusable workflows I've built to automate repeatable operational tasks. Each skill is a structured prompt with defined inputs, a consistent output format, and context that doesn't need to be re-explained every time.

---

## AI Tool Evaluation Framework

**The problem:** Evaluating a new AI tool from scratch — compliance questionnaire, use case assessment, risk scoring, investment recommendation — was taking half a day. I do this regularly across a 10+ partner ecosystem.

**What it does:** From a tool name and website URL, produces:
- Completed Havas AI compliance questionnaire responses
- Use case fit scoring against defined community needs
- Risk and scalability assessment
- A one-paragraph investment recommendation for senior leadership

**Time saved:** ~3–4 hours per tool evaluation → under 30 minutes.

---

## Partner Onboarding Workflow

**The problem:** Every new tool partner follows the same onboarding sequence — IT review, legal sign-off, comms to global markets, training materials, rollout tracking. The steps are consistent but the coordination was manual and error-prone.

**What it does:** From a partner name and key details, generates:
- Full onboarding checklist with owners and deadlines
- Draft stakeholder communications for each stage (IT, legal, market leads)
- Rollout tracking template
- FAQ document for market-level queries

**Time saved:** ~2 hours of setup per partner → under 20 minutes.

---

## Strategic Deck Generator

**The problem:** First drafts of strategic presentations — partner briefings, community updates, capability reviews — were taking too long given how frequently they're needed.

**What it does:** From a brief (topic, audience, key messages, tone), produces:
- Slide-by-slide structure with titles and content direction
- Speaker notes or narrative thread
- Executive summary for email distribution

**Time saved:** 2-hour first draft → under 20 minutes.

---

## Community Comms Workflow

**The problem:** Regular communications to a 600+ member global community need consistent tone, structure, and brand standards. Drafting from scratch every time introduced inconsistency and took longer than necessary.

**What it does:** From a topic and key updates, produces:
- Bi-monthly newsletter draft in house style
- Webinar invitation and reminder copy
- Partner spotlight write-ups
- SharePoint content updates

---

## What I've learned about building with Claude

Prompt engineering for operational workflows is a design problem, not a writing problem. The most useful skills share three things:

1. **Fixed output format** — the structure of the output is defined, not left to the model. This makes the output immediately usable rather than something that still needs reformatting.
2. **Minimal inputs** — the skill should require as little from me as possible to produce something useful. If I have to write a lot to get the output, I might as well write the output.
3. **Embedded context** — the information that doesn't change (brand standards, stakeholder preferences, process steps) lives in the skill itself, not in my head.
