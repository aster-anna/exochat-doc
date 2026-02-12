# ICP & Buyer Personas (Working Draft)

---

**Status:** Preliminary research for SalesOff enablement. Assumptions may change as we collect market feedback. We are open to discussion and updates.

**Version:** v0.1 — September 25, 2025

## 1) Ideal Customer Profile (ICP)

**Company types**

- B2B/B2C product companies (Series A+ to Growth) with meaningful traffic or ticket volume. We don’t target small companies
- Tech-enabled SMBs and mid-market+ teams running **sales** or **customer support** at scale.
- VC/PE funds looking to standardize fast AI pilots across portfolio companies.

**Signals they’re a fit**

- **Volume/budget:** ≥ **50** support agents **or** ≥ **10** SDRs; **>2,000** tickets/month **or** **>500** inbound leads/month.
- **Stack in place:** HubSpot/Salesforce; Zendesk/Intercom/Freshdesk on paid tiers; Google/Microsoft Calendar.
- **Bot fatigue:** experimenting with chatbots but seeing randomness/off-brand responses.
- **KPI pressure:** **more qualified demos**, **lower AHT**, **higher FCR/CSAT**, **deflection**.
- **Governance & compliance:** brand tone rules, no-go topics, audit trail, data residency.
- **Pilot posture:** willing to run a **10-day pilot** on 1–2 flows **with a traffic cap** and a single KPI.
- **Security trigger (bonus):** vendor questionnaire/DPA in motion; InfoSec contact identified.
- **Champion present:** someone who owns the KPI and can sponsor access.

**Verticals with strong pain**

- SaaS, Fintech, E-commerce & Marketplaces, Telecom, B2B services, Edu/Training.
- Any regulated or brand-sensitive environment where **controlled** AI responses matter.

**Company size (guidance, not strict)**

- 500+ employees **or** support tickets > 2,000/month **or** inbound leads > 500/month.
- Sales/Support leadership in place (RevOps, CX Ops) and budget for tooling.

**Anti-ICP (deprioritize)**

- Micro/low-volume teams without a measurable KPI or budget window.
- “Open-ended AI research” with no single KPI or traffic cap.
- On-prem only **and** no API/sandbox access (pilot not feasible).
- Expectation of a fully custom dev agency build (ExoChat is a productized framework).
- No identified champion or economic buyer after discovery.

---

## 2) Buyer Personas (Who we sell to)

### A) Head of Support / CX Lead (Primary Champion)

**Goals**

- Reduce **Average Handle Time (AHT)**, increase **First Contact Resolution (FCR)**, boost **CSAT**.
- Deflect repetitive tickets; keep agents for complex cases.
- Maintain brand-safe, policy-compliant answers.

**Pains**

- Current chatbots are inconsistent and hard to tune; analytics are shallow.
- Escalations happen too late; handoffs lack context.
- Compliance/tone drift creates risk.

**What they care about**

- Control over flows (“no surprises”).
- Step-by-step analytics to see drop-offs and fix them.
- Human handoff with full context.
- Fast pilot with clear “keep/kill” decision.

**Top objections & answers**

- *“We tried a chatbot; it didn’t work.”* → ExoChat uses **playbooks** (flows), not random chat; per-step analytics show what to fix.
- *“Compliance risk.”* → Guardrails, no-go topics, logging, audit trails, redaction options.

**Proof they want**

- Before/after AHT, FCR, CSAT; deflection rate and ticket mix.

---

### B) Head of Sales / RevOps (Primary Champion or Co-Champion)

**Goals**

- More **qualified** leads, more **demos booked**, faster **speed-to-first-touch**.
- Cleaner discovery data in CRM.

**Pains**

- Lead forms underperform; SDR time wasted on unqualified inbound.
- Chatbots don’t ask the right questions or book meetings reliably.

**What they care about**

- Conversational **lead-qual** that asks the right questions and scores reliably.
- Calendar integration + routing; CRM writeback.
- Per-step conversion data and quick A/B testing.

**Top objections & answers**

- *“Will this flood SDRs with noise?”* → We **score and route**; only qualified leads reach SDRs.
- *“Hard to measure impact.”* → Booked demos and conversion by **flow step** show lift clearly.

**Proof they want**

- Lift in demo bookings / qualified MQL→SQL rate; shorter time-to-first-touch.

---

### C) CPO / CTO (Economic Influencer / Technical Gatekeeper)

**Goals**

- Predictable behavior, low integration friction, security.
- Avoid vendor lock-in to a single LLM.

**Pains**

- Prompt spaghetti; hard to govern and version.
- Unknown model behavior in edge cases; brittle hacks.

**What they care about**

- **Flow logic** (FSM), versioning, rollbacks, traffic splitting.
- Model-agnostic orchestration; connectors via API/webhooks.
- Logs, observability, and policy enforcement.

**Top objections & answers**

- *“Model lock-in?”* → Model-agnostic by design; swap models without rebuilding flows.
- *“Who maintains it?”* → We handle pilot build; light ongoing ops; your team controls flows.

**Proof they want**

- Architecture diagram, security notes, minimal integration checklist.

---

### D) VC Platform / Operating Partner (Portfolio Enabler)

**Goals**

- Standardize quick pilots across portfolio; show real KPI lift.
- Share playbooks across similar portfolio companies.

**Pains**

- Pilots take months; results are anecdotal.
- Founders lack bandwidth to design flows.

**What they care about**

- **10-day pilot** with crisp KPI definition and reusable playbooks.
- Simple procurement, fast onboarding, minimal founder time.

**Proof they want**

- Pilot outcomes (e.g., +30% demo bookings in 10 days) and rollout plans.

---

## 3) Problems We Solve (Pain → Outcome)

- **Random chatbot answers → Controlled flows:** predictable steps with safe fallbacks.
- **No measurable impact → Per-step analytics:** see what converts and fix drop-offs.
- **Slow, messy handoffs → Clean agent transfers:** full chat context to human.
- **Compliance concerns → Guardrails & audit:** tone rules, no-go topics, logging.
- **Stalled pilots → 10-day framework:** ship something real and decide with data.

---

## 4) Triggers & Timing (When to reach out)

- Launching a new product/pricing and support is overwhelmed.
- SDR team is swamped; marketing wants better lead qualification.
- Leadership sets targets on AHT, FCR, CSAT, or demo booking rate.
- They’re hiring “AI lead” / “Automation” roles or posting about AI experiments.
- Recent migration to or consolidation in CRM/help desk stack.

---

## 5) Discovery Questions (Use in first calls)

**Support/CX**

- Which tickets are repetitive and safe to automate today?
- Current AHT, FCR, CSAT? What’s the target for the quarter?
- Where do handoffs fail now? What must be logged for audit?

**Sales/RevOps**

- What defines a **qualified** lead for you (must-have fields/criteria)?
- How do you book meetings today? Conversion baseline from visit → demo?
- Which channels bring the most inbound and where do they drop?

**Technical**

- Which tools do we need to connect (CRM/help desk/calendar)?
- Any data residency or redaction rules?
- Who signs off on security and PII handling?

---

## 6) Pilot Design Cheatsheet (10-Day)

- Pick **one** use case (Lead-Qual **or** Support Triage).
- **1 KPI** (max 2): e.g., +30% demo bookings / −20% AHT / +15% FCR.
- **Traffic cap** (e.g., 1,000 sessions) to control risk/cost.
- Minimal integrations: **calendar + CRM** (sales) or **help desk** (support).
- Guardrails: tone, no-go topics, fallback + human handoff triggers.
- **Decision rule:** keep if KPI ≥ target and error rate < threshold; otherwise iterate/kill.
- **Artifacts required:** link to **Stakeholder Map** and **Mutual Action Plan**.

---

## 7) Messaging by Persona (Short value lines)

- **Support/CX:** “Cut AHT and raise CSAT with controlled AI flows—not random chat.”
- **Sales/RevOps:** “Ask the right questions, auto-book meetings, and feed clean data to CRM.”
- **CPO/CTO:** “Deterministic flows, model-agnostic orchestration, logs, and guardrails.”
- **VC Platform:** “Repeatable 10-day pilots with reusable playbooks for portfolio.”

---

## 8) Common Objections (and how we answer)

- **“We already have a chatbot.”**
    
    Great—ExoChat can govern the flow, add guardrails, and show per-step analytics your bot can’t.
    
- **“We’re worried about brand/compliance.”**
    
    We enforce tone, block no-go topics, keep logs, support redaction, and hand off to humans safely.
    
- **“We don’t have bandwidth.”**
    
    The pilot is scoped: 1–2 flows, light integrations, and we do the heavy lifting.
    
- **“Will this lock us into one model?”**
    
    No—ExoChat is model-agnostic; switch models without rebuilding your business logic.
    

## 9) Required Artifacts by Stage

- **Post-Discovery:** **Stakeholder & Negotiation Map** (internal) — EB, Champion, Influencers, risks, KPI/baseline.
- **Pre-Pilot:** **Mutual Action Plan** (shared) — KPI, baseline, traffic cap, timeline, owners, decision rule.
- **Post-Pilot:** 1-page results (KPI vs baseline, top drop-offs, transcript samples, recommendation).

### 10) Procurement & Security (Enterprise quick notes)

- **Data & models:** prompts/outputs are **not** used to train public models by default; optional redaction; configurable retention.
- **Least-privilege integrations:** service accounts only; CRM/help desk/calendar scoped to create/update.
- **Auditability:** conversation logs, policy hits, versioning/rollback, export.
- **Compliance:** NDA/DPA/MSA; data residency honored; VPC/private deployment available on Scale/Enterprise.
- **Owner map:** identify **InfoSec owner** and **Economic Buyer** during discovery.