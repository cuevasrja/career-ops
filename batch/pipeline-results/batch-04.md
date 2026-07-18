# Batch 04 — Pipeline Results
**Date:** 2026-06-04
**Reports:** 030–038 (9 offers)
**Companies:** N26 (5), SumUp (4)

---

## Summary Table

| # | Company | Role | Score | Location | Rec |
|---|---------|------|-------|----------|-----|
| 030 | N26 | Backend Engineer - Customer Risk Lifecycle | 2.8/5 | Barcelona/Berlin | SKIP |
| 031 | N26 | Backend Engineer - Subscriptions | 2.8/5 | Barcelona | SKIP |
| 032 | N26 | Senior Backend Engineer - Customer Risk Lifecycle | 2.2/5 | Berlin/Barcelona | SKIP |
| 033 | N26 | Senior Backend Engineer - Security Automation | 2.5/5 | Berlin | SKIP |
| 034 | N26 | Lead Backend Engineer - Assistance | 2.4/5 | Barcelona/Berlin | SKIP (bookmark AI team) |
| 035 | SumUp | Backend Engineer (Global Bank Tribe) | 3.6/5 | Florianópolis, Brazil | Apply |
| 036 | SumUp | Backend Engineer (Go) - Payments Experience | 3.8/5 | Sofia, Bulgaria | Strong Apply |
| 037 | SumUp | Backend Engineer - POS | 2.6/5 | Berlin | SKIP |
| 038 | SumUp | Backend Engineer - Transfers | **3.9/5** | Vilnius, Lithuania | **Top Apply** |

---

## Key Findings

### N26 (5 roles — all SKIP)
N26's backend engineering is **uniformly Kotlin/Spring Boot**. Every role in this batch — from mid-level to Lead — requires JVM language production experience as a hard filter. Juan's Python/Go/TypeScript stack does not map. The one exception worth noting is **034 (Lead Backend - Assistance)** which is the only N26 role with explicit AI/LLM/RAG content and mentions Python as a bonus, plus references AI coding agents (Claude Code) as team tools. This team is worth re-targeting once Juan accumulates JVM experience.

### SumUp (4 roles — 3 apply-worthy)
SumUp is more polyglot than N26. The **Go-primary roles (036, 038) are the best fits in the entire batch** because Juan has genuine Go production experience from Market Street Labs. Key distinctions:

- **038 (Transfers, Vilnius)** — Top pick: explicit mid-level framing, published compensation (€3,500–5,200/month), Go primary stack, EU relocation. Apply first.
- **036 (Go Payments, Sofia)** — Second pick: explicit Go requirement, growth-oriented JD language, Ruby legacy = greenfield Go opportunity. Apply.
- **035 (Global Bank, Florianópolis)** — Third pick: polyglot tribe includes Go, Brazil relocation, but Kafka/K8s gap is larger than in 036/038.
- **037 (POS, Berlin)** — SKIP: Kotlin/Spring Boot 3yr requirement, same JVM blocker as all N26 roles.

---

## Pattern Note for Juan

**JVM (Kotlin/Java/Spring Boot) is a systematic blocker** across both N26 and a significant portion of Berlin/European fintech backend roles. The 3 Go-friendly roles all happen to be in Eastern Europe or Brazil rather than the flagship Berlin/Barcelona offices. Options:
1. Build a Kotlin/Spring Boot side project (3-6 months) to open up the Berlin fintech market
2. Focus applications on Go-primary companies (SumUp Go tribe, Cloudflare, HashiCorp, Temporal, other Go fintechs) where Juan's stack is a genuine match
3. Apply immediately to 036 and 038 as the highest-probability opportunities in this batch

---

## Next Actions

1. Run `node merge-tracker.mjs` to merge 030–038 TSVs into applications.md
2. Generate PDFs for roles 036 and 038 (Go-primary, apply-recommended)
3. Consider adding 036 and 038 to active application queue
4. Bookmark N26 034 (Assistance/AI team) for re-targeting after JVM exposure accumulates
