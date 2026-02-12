# Sales FAQ

## 0) Elevator pitch (what to say in one breath)

**ExoChat lets companies run AI chats that follow clear playbooks, stay on-brand and policy-safe, and show measurable results in sales and support, used by mid-market and enterprise teams who need predictable AI conversations for measurable ROI.**

Start with a focused **10-day pilot**, measure impact, scale if it works.

---

## 1) What is ExoChat?

- A tool to design **conversation playbooks** (step-by-step flows).
- The AI speaks naturally, but the **logic is yours** (you set steps, rules, and guardrails).
- Comes with **analytics by step**, **human handoff**, and **easy integrations** (CRM/help desk/calendars/chat).

**Not “just a chatbot.”** It’s controlled, measurable AI conversation.

---

## 2) What problems does it solve?

- Procurement & compliance delays → We provide quick security notes, NDA/DPA, and guardrails so InfoSec can approve faster
- Random, off-brand answers → replaced by **controlled flows** with safe fallbacks.
- Hard-to-prove impact → **per-step analytics** and clear KPIs.
- Endless pilots → **10-day pilot** that ends with a clear keep/kill decision.
- Messy handoff → **agent transfer with full context**.

---

## 3) Who is it for (ICP & personas)?

- **Support/CX leaders** (AHT/FCR/CSAT/deflection).
- **Sales/RevOps leaders** (qualified leads, demo bookings, speed-to-first-touch).
- **CPO/CTO** (control, safety, model choice, light integration).
- **VC Platform** (repeatable pilots across portfolio).

Best fit: ≥50 agents or ≥10 SDRs, 2k+ tickets/month or 500+ inbound leads/month.

---

## 4) What does ExoChat actually do (features in simple terms)?

- **Flow builder:** create the steps (branches like “if user says X → do Y”).
- **Guardrails:** tone rules, no-go topics, safe fallback, human handoff triggers.
- **Memory:** keep useful context during a session (and longer if agreed).
- **Integrations:** CRM, help desk, calendars, webhooks/API, RAG for docs.
- **Analytics:** see drop-offs and conversions **by step**; run quick A/Bs.
- **Channels:** website widget, in-app, email, Slack/Teams, WhatsApp/Telegram (via providers), API.

---

## 5) Where should clients start (top use cases)?

- **Pre-sales & lead qualification:** ask key questions, score, **auto-book meetings**, write to CRM.
- **Support triage & resolution:** identify intent, answer FAQs, collect info, and **hand off** neatly to agents.
- **Onboarding & success:** guided setup, renewals, upsell nudges.

Pick **one** use case first.

---

## 6) How does the 10-day pilot (trial) work?

**Goal:** prove value fast on 1 use case with 1–2 KPIs.

**Timeline (typical):**

- **Days 1–2:** agree on use case + KPI target (e.g., +30% demo bookings / −20% AHT), confirm tools to connect.
- **Days 3–5:** build the playbook; set guardrails; connect basics (calendar/CRM/help desk).
- **Days 6–8:** internal testing; add safe fallbacks and human handoff.
- **Days 9–10:** limited live run; measure against baseline; present results.

**How the trial is “counted”:**

- **Duration:** 10 calendar days from kickoff (Day 1).
- **Scope:** 1–2 playbooks, 1–2 channels, light integrations.
- **Traffic cap:** set together before kickoff to control cost and risk (e.g., throttle or restrict to a segment).
- **Success criteria:** written on Day 1 (KPI target + any guardrail requirements).
- **Deliverables:** pilot playbook(s), short analytics report (per-step results), transcript samples, and a keep/kill recommendation.
- **Decision meeting:** Day 10 (or first business day after).
- **If more time/traffic needed:** either extend the pilot (agreed scope) or proceed to paid rollout.

**What we need from the client:**

- A sponsor, a single use case, KPI targets, basic access to tools (calendar/CRM/help desk), any policy/tone rules, segment to run on.

**Who does the work:**

We build and operate the pilot; the client reviews flows, provides access and feedback.

---

## 7) What metrics will we show?

- **Sales:** more qualified leads, more demos booked, faster first response, cleaner CRM data.
- **Support:** AHT ↓, FCR ↑, CSAT ↑, deflection ↑, cost/issue ↓.
- **Per-step analytics:** where users drop off, what wording/branch converts.
- **Attribution:** simple view of revenue/booking influence by playbook where applicable.
- **Report format:** quick summary + charts/tables + transcript examples + next steps.
- ROI snapshot vs baseline agreed on Day 1

---

## 8) Pricing & packaging (guidance)

- Pilot = scoped fee **or** success-based.
- Subscription = **platform license** + **usage (LLM traffic)**.
- Add-ons = integrations/custom flows.
- For enterprise: **support tier + SLA**.

---

## 9) Integrations (what’s possible, what’s typical)

- **CRMs:** HubSpot, Salesforce (API/webhooks).
- **Help desks:** Zendesk, Intercom, Freshdesk.
- **Calendars/booking:** Google/Microsoft; meeting links.
- **Data/knowledge:** REST/GraphQL, DBs, files; **RAG** for internal docs.
- **Comms:** Web widget, in-app, Slack/Teams, WhatsApp/Telegram via providers, email.

**Pilot rule:** keep it light—only the minimum needed to hit the KPI.

---

## 10) Security, privacy, compliance (plain talk)

- **Data use:** we only use data the client authorizes.
- **No training on your data by default:** model providers are configured so your prompts/outputs aren’t used to train public models (subject to provider settings; we’ll document the mode we use).
- **Logging & audit:** conversation logs, policy hits, version history; export on request.
- **Access control:** least-privilege for connectors; role-based access in the app.
- **Retention:** configurable with client (e.g., redact PII, define retention windows).
- **Hosting:** our cloud by default; VPC/private options can be discussed if required.
- **Compliance posture:** we follow industry best practices; we’ll complete security questionnaires and sign NDA/DPA/MSA as needed.
- We routinely complete vendor questionnaires (SOC, ISO checklists) and provide a short 1-page Security FAQ upfront

---

## 11) What AI models do you use?

- **Model-agnostic.** We can use different LLMs per flow and swap as needs change.
- **Selection:** we pick models based on quality, latency, cost, and data policy requirements.
- **Mitigations:** guardrails, retrieval (RAG) for facts, fallbacks, and human handoff reduce “hallucinations.”
- **Fine-tuning:** optional and only with explicit agreement; otherwise we do not train models on client data.

---

## 12) Reliability & performance

- **Uptime:** we rely on multiple vendors (channels, LLMs). We design flows with retries and fallbacks.
- **Degradation plan:** if a model/provider is slow, we route to a fallback, simplify responses, or hand off to human.
- **Latency:** depends on model and connectors; we tune playbooks for speed where it matters (e.g., lead-qual).

---

## 13) Human handoff (how it works)

- Clear triggers send the conversation to an agent queue with **full context** (transcript + collected fields).
- We can tag urgency or reason codes to help routing.
- Agents can return users to the AI when appropriate.

---

## 14) Languages & markets

- Multi-language conversations are supported.
- We recommend **one language per pilot** for clean measurement; add more post-pilot.
- Local timezones, formats, currencies can be configured per flow.

---

## 15) How is this different from other options?

- **Generic chat widget / unmanaged GPT:** fast but random, hard to measure. ExoChat gives **flows + guardrails + step analytics**.
- **Help desk “AI add-ons”:** convenient but often limited to one stack and shallow analytics. ExoChat is **stack-agnostic** with **flow-level control**.
- **Build your own (RPA/frameworks):** full control but slow and costly. ExoChat is **productized**: 10-day pilot to results.

---

## 16) What can’t ExoChat promise?

- 100% accuracy in all edge cases (no AI can).
- Full agent replacement (we focus on the repetitive slice and clean handoffs).
- Results without a clear KPI and minimum data/access.
- Heavy custom dev on a pilot timeline (we keep scope tight).

---

## 17) Contracts & procurement

- **Usual docs:** NDA, DPA, MSA, Order Form/SOW.
- **Security review:** we’ll complete vendor/infosec questionnaires.
- **Data processing:** documented data flows, retention, and deletion on request.
- **IP:** client keeps their data and brand assets; we keep platform IP and generic playbook logic (client-specific content can be licensed as needed).

---

## 18) Support & SLAs

- **During pilot:** direct channel with our team, quick turnarounds.
- **Post-pilot:** support tiers available (response targets by severity).
- **Training:** short enablement session for client admins to tweak playbooks safely.

---

## 19) Analytics & reporting details

- **Dashboards:** conversions by step, drop-offs, handoff quality, A/B results.
- **Exports:** CSV/JSON on request; light BI hooks possible.
- **Reviews:** weekly during pilot; monthly post-pilot (or as agreed).

---

## 20) Roadmap (non-binding)

- More **plug-and-play templates** for common flows (lead-qual, triage, onboarding).
- Deeper **analytics** (multi-touch attribution, cohort views).
- Additional **connectors** and RBAC enhancements.
    
    Roadmap order is shaped by client demand.
    

---

## 21) What does a good pilot candidate look like? (qualification)

- Clear KPI (e.g., “+30% demo bookings” or “−20% AHT”).
- One channel we can activate fast (site chat, help desk, Slack/Teams).
- Agreed guardrails (tone/no-go) and human handoff rules.
- A sponsor who can approve a “keep/kill” decision.

---

## 22) What discovery questions should sales ask?

- **Support:** Which tickets are repetitive and safe to automate today? Current AHT/FCR/CSAT and targets?
- **Sales:** What makes a lead qualified? Current visit→demo conversion and booking flow?
- **Tech:** Which tools must we connect? Any PII/redaction rules or data residency needs?

---

## 23) Objections & quick answers (cheat sheet)

- **“We already have a chatbot.”**
    
    Great—ExoChat can **govern** it with flows/guardrails and show **per-step analytics** it likely lacks.
    
- **“We’re worried about brand/compliance.”**
    
    Set **guardrails**, block no-go topics, keep **logs/audit**, and hand off safely.
    
- **“We don’t have bandwidth.”**
    
    The pilot is **small and fast**; we do the heavy lifting. You provide KPI + access.
    
- **“Model lock-in?”**
    
    ExoChat is **model-agnostic**; swap models without rebuilding your flows.
    
- **“Hard to measure impact.”**
    
    We track results **by step** and against **baseline** with a 10-day decision.
    

---

## 24) What happens after a successful pilot?

- Convert the pilot playbook to **production**, expand to more flows/channels.
- Confirm **pricing & support** tier, finalize contracts.
- Set a 60-day plan for scaling (additional use cases, languages, markets).

---

## 25) What if the pilot underperforms?

- Review where users dropped; adjust wording/steps and retry **once** (if agreed).
- If still below target, we recommend **stop** or re-scope with clear reasons.

---

## 26) Who owns the content from the pilot?

- Client owns their data and brand content.
- We share the pilot assets (flows/configs) for internal review; ongoing use is via the subscription.

---

## 27) How do we handle sensitive data (PII)?

- Use the **minimum needed**; redact where possible; avoid storing secrets in prompts.
- Retention windows are agreed up front; logs can be exported or deleted on request.
- We configure model providers to **not** train on your data by default (documented per provider).

---

## 28) How do we reduce “AI mistakes”?

- Keep the playbook tight; use RAG for facts; set safe fallbacks; define handoff triggers.
- Start with a narrow use case; expand after results are proven.

---

## 29) Can clients edit flows themselves?

- Yes—after a short enablement, client admins can safely tweak steps, wording, and rules.
- Versioning and rollbacks are available.