# QPT — Business Plan

> Multiparadigm AI Compiler & Bridge Company
> "CUDA for Heterogeneous Computing Paradigms"

---

## Table of Contents

1. [Executive Summary](#1-executive-summary)
2. [The Market](#2-the-market)
3. [The Product](#3-the-product)
4. [Business Model](#4-business-model)
5. [Moat & Competitive Advantage](#5-moat--competitive-advantage)
6. [Revenue Model & Pricing](#6-revenue-model--pricing)
7. [Unit Economics](#7-unit-economics)
8. [12-Month Roadmap](#8-12-month-roadmap)
9. [Growth Projections](#9-growth-projections)
10. [Risk Analysis](#10-risk-analysis)
11. [Legal & IP Strategy](#11-legal--ip-strategy)
12. [Team & Resources](#12-team--resources)

---

## 1. Executive Summary

**QPT** builds the software layer that routes LLM computation across classical, quantum, photonic, and thermodynamic computing substrates. We answer one question: *which parts of a language model actually benefit from non-classical computing, and by how much?*

**The analogy:** NVIDIA did not build AI models. They built CUDA — the software layer that made GPUs the standard for AI compute. That made NVIDIA a $3T company. QPT aims to be the CUDA for multiparadigm AI: a compiler/runtime that decides *where* each computation should run.

**Current stage:** Pre-revenue, bootstrapping, 4-person team. No hardware owned. Research-phase company building toward Phase 3 (simulated hybrid LLM) with intent to sell consulting services from day one.

**12-month goal:** Reach Phase 3 (simulated hybrid LLM mixing Q+P+T), generate $30–60k run-rate from consulting, and file first patent on the multiparadigm routing algorithm.

---

## 2. The Market

### 2.1 TAM / SAM / SOM

| Layer | Definition | Size | Growth (CAGR) |
|---|---|---|---|
| **TAM** | Global AI infrastructure (compute + energy + services) | **$500B+ by 2030** | 20–25% |
| **SAM** | Non-classical computing for AI (quantum + photonic + thermodynamic hardware + software) | **$30–80B by 2030** | 30%+ (emerging) |
| **SOM (Year 1–3)** | Consulting + benchmarking + licensing for hardware-AI integration | **$5–20M addressable** | N/A (emerging) |

**Key insight:** The SOM is small today because the market doesn't exist yet. QPT's strategy is to **create the market** (multiparadigm AI) rather than capture share in an existing one. This eliminates the TAM ceiling risk — if multiparadigm computing becomes standard, QPT owns the routing layer.

### 2.2 Market Signals

- **Energy is the binding constraint:** Training a single frontier LLM costs $100M+ in compute. Data centers consume 1–2% of global electricity and growing. Every efficiency gain has immediate commercial value.
- **Hardware diversification is inevitable:** Quantum (IBM, Google), photonic (Lightmatter, PsiQuantum), thermodynamic (Extropic), biological (Qubit Neuroscience) — these are not competing, they are fragmenting the compute substrate. Someone needs to bridge them.
- **Current market gap:** No company or tool currently provides LLM-level routing across heterogeneous compute paradigms. The gap is in the "compiler" layer between AI models and physical hardware.

### 2.3 Penetration Strategy

| Phase | Geography | Penetration Method |
|---|---|---|
| Year 1 | Colombia (MinCiencias, tax incentives, local clients) | Direct consulting, grants |
| Year 1–2 | Germany (EXIST, DFG, SPRIND) | University partnerships, research grants |
| Year 2–3 | USA (C-Corp, EIC, NVIDIA Inception, IBM Quantum) | Licensing, VC preparation |

---

## 3. The Product

### 3.1 Roadmap (aligned with Product.md phases)

| Phase | What | Timeline | Revenue Impact |
|---|---|---|---|
| **Phase 1** | Classical LLMs (nanoGPT → GPT-2 → professional) | Months 1–4 | Proof-of-competence; open-source distribution |
| **Phase 2** | Individual paradigm simulations (Q, P, T separately) | Months 3–6 | Benchmark data; consulting insights |
| **Phase 3** | **Hybrid mixing Q+P+T in each step** | **Months 6–9** | **First sellable product (hybrid LLM demo + benchmark service)** |
| Phase 4 | Performance optimization | Months 9–12 | Improved benchmarks; sellable performance audits |
| Phase 5 | Own hybrid algorithms (patentable) | Months 10–15 | IP asset; licensing potential |
| Phase 6 | Train with hybrid algorithms + simulation | Year 2 | Efficiency gains; publishable results |
| Phase 7 | Rent quantum/photonic/thermo hardware | Year 2–3 | Hardware validation; premium benchmarking |
| Phase 8 | Own hardware | Year 3–5 | Vertical integration (long-term) |

### 3.2 Open Source Components (distribution + ecosystem)

| Component | License | Purpose |
|---|---|---|
| `qpt-llm` (classical nano models) | MIT | Lead generation; community |
| `qpt-sim` (paradigm simulators) | MIT | Research adoption; benchmark standard |
| `qpt-bench` (benchmark framework) | MIT | Industry standard; consulting funnel |
| `thermo-computer` (open-source thermal computer) | Hardware license | Brand; ecosystem; validation |
| `qpt-random` (true random number generator) | MIT | Niche utility; brand awareness |

### 3.3 Proprietary Core (moat)

| Component | Protection | Revenue Source |
|---|---|---|
| **QPT Compiler/Runtime** | Patent + trade secret | Licensing to hardware makers |
| **Paradigm routing algorithm** | Patent | Licensing; competitive advantage |
| **Heuristics & calibration data** | Trade secret | Consulting premium |
| **Benchmark dataset (QPT-Bench)** | Database rights + copyright | Certification service |

---

## 4. Business Model

### 4.1 Open Core Structure

```
OPEN SOURCE (ecosystem & distribution)    PROPRIETARY (revenue)
─────────────────────────────────────    ─────────────────────────
LLM base models (nano-gpt, GPT-2)       QPT Compiler/Runtime (patents)
Paradigm simulators                      Routing algorithm (patents)
Benchmark framework                      Heuristics & calibration data
Open thermal computer design             Hardware verification service
True random number generator             Enterprise benchmark suite
```

### 4.2 Three Horizons

**Horizon 1 (Months 0–12): Consulting & Grants — Survival Revenue**

| Revenue Stream | Price | Target | Margin |
|---|---|---|---|
| Efficiency audit (fixed project) | $5–15k | AI labs, hardware startups | 80% |
| R&D tax advisory retainer | $1–3k/month | Colombian/EU companies | 85% |
| Technical workshop | $500–2k/session | Universities, companies | 90% |
| Non-dilutive grants | Variable | MinCiencias, EIC, EXIST, DFG | N/A |
| **Year 1 target** | | **$30–60k run-rate** | |

**Horizon 2 (Months 12–36): Licensing & Certification — Recurring Revenue**

| Revenue Stream | Price | Target | Margin |
|---|---|---|---|
| QPT Runtime license (per chip deployed) | Royalty model | Extropic, Lightmatter, PsiQuantum | 90%+ |
| QPT-Bench certification | $20–50k per certification | Hardware manufacturers | 85% |
| Enterprise benchmark suite (SaaS) | $5–15k/year | AI labs, cloud providers | 80% |
| Premium consulting (retainer) | $10–30k/month | OpenAI, Anthropic, Google | 75% |
| **Year 3 target** | | **$500k–2M ARR** | |

**Horizon 3 (Months 36–84): Standard & Platform — Multiplicative Revenue**

| Revenue Stream | Model | Potential |
|---|---|---|
| QPT Runtime as industry standard | Per-deployment licensing (CUDA model) | $10M–100M+ |
| Hardware-verified LLM training | Training-as-a-service with own hardware | $5M–50M |
| IP licensing portfolio | Patent royalties | $2M–20M |
| **Year 5–7 target** | | **$10M–100M ARR** |

### 4.3 Why This Model Works

- **Open source creates the market:** By distributing simulators and benchmarks freely, QPT defines *how* multiparadigm AI is measured. This makes QPT the authority.
- **Proprietary compiler captures value:** The routing algorithm that decides "this attention head runs quantum, this MLP runs thermodynamic" is the high-value IP. It's the "CUDA" — not the model, not the hardware.
- **Switching costs are structural:** Once a hardware maker's chip is integrated into the QPT Runtime, switching requires rebuilding the integration layer. This creates lock-in without aggressive sales tactics.

---

## 5. Moat & Competitive Advantage

### 5.1 Moat Assessment (Current vs. Year 3)

| Moat Type | Today (Month 0) | Year 3 Target |
|---|---|---|
| **Network effects** | None | Indirect: every hardware maker on QPT Runtime makes it more valuable for AI labs and vice versa |
| **Switching costs** | None | High: QPT Runtime embedded in AI training pipelines |
| **IP/Patents** | None (vision only) | 1–3 patents on routing algorithm; trade secrets on heuristics |
| **Data advantage** | None | QPT-Bench dataset: largest cross-paradigm LLM benchmark in existence |
| **Brand/authority** | None | "QPT" = standard name for multiparadigm AI measurement |
| **Economies of scale** | None | Marginal cost of licensing ≈ $0; marginal cost of consulting ≈ labor |

### 5.2 Competitive Landscape

| Competitor | What They Do | Relationship to QPT |
|---|---|---|
| **Extropic** | Thermodynamic computing hardware | Potential QPT customer (need bridge to LLMs) |
| **Lightmatter** | Photonic computing hardware | Potential QPT customer |
| **PsiQuantum** | Photonic quantum computing | Potential QPT customer |
| **IBM Quantum** | Superconducting quantum | Potential customer + platform partner |
| **NVIDIA** | GPU + CUDA (classical only) | Complementary (QPT extends CUDA to new paradigms) |
| **Normal Computing** | Quantum + classical LLM research | Partial overlap; QPT broader (includes P + T) |
| **PennyLane / Qiskit** | Quantum ML frameworks | QPT builds *on top* of these; they are tools, not competitors |

**Key insight:** QPT does not compete with hardware makers. QPT **sells to them** by being the bridge to LLM developers. No hardware company has an incentive to build the bridge themselves — they want to focus on their substrate.

---

## 6. Revenue Model & Pricing

### 6.1 Year 1 — Consulting (detailed)

| Service | Deliverable | Price Range | Payment Terms |
|---|---|---|---|
| **Hybrid Architecture Audit** | Written report identifying which LLM components benefit from Q/P/T; quantitative trade-off analysis; implementation roadmap | $5,000–$15,000 | 50% upfront, 50% on delivery |
| **R&D Tax Advisory** | Identification of qualifying R&D activities; documentation for tax credit claims (Colombia CTeI, Germany DFG, US CHIPS Act) | $1,000–$3,000/month retainer | Monthly in advance |
| **Technical Workshop** | Half-day or full-day training on hybrid computing paradigms for LLM practitioners | $500–$2,000/session | 100% upfront |
| **Benchmark Report** | Custom benchmark of client's LLM across paradigms with wall-clock vs. hardware-adjusted metrics | $3,000–$8,000 | 100% on delivery |

### 6.2 Year 2–3 — Licensing (preliminary)

| License Type | Model | Estimated Revenue/Year |
|---|---|---|
| **Hardware maker integration** | Per-chip royalty (e.g., $0.01–$0.10 per device deployed with QPT Runtime) | $100k–$1M per partner |
| **Enterprise benchmark** | Annual SaaS license for QPT-Bench suite | $5–15k per customer |
| **Academic/research license** | Free for published research; commercial use requires license | Revenue from commercial users only |

### 6.3 Year 5+ — Standard (if QPT Runtime becomes industry default)

| Revenue Stream | CUDA Analogy | Estimated Revenue |
|---|---|---|
| Runtime licensing | NVIDIA charges per GPU license | $10M–$100M+ |
| Training service | Custom hybrid-optimized model training | $5M–$50M |
| IP portfolio | Patent royalties from ecosystem | $2M–$20M |

---

## 7. Unit Economics

### 7.1 Year 1 (bootstrapping, no employees on payroll)

| Metric | Value | Notes |
|---|---|---|
| **CAC** | ~$0 | Acquired via open-source, grants, direct outreach |
| **Average deal size** | $8,000 | Blend of audits + retainers + workshops |
| **Gross margin (consulting)** | 80%+ | Solo/founder delivery; near-zero overhead |
| **LTV** | $24,000 | Assumption: 3 engagements per client over 12 months |
| **LTV / CAC** | ∞ (effectively) | No CAC → every dollar of revenue is margin |
| **Payback period** | Immediate | No upfront investment to recover |
| **NRR target** | >120% | Client grows: audit → retainer → license |
| **Net revenue target** | $30–60k/year | 4–6 clients at $8k average |

### 7.2 Year 3 (post-seed, 3–5 employees)

| Metric | Target | Notes |
|---|---|---|
| **CAC** | $2,000–$5,000 | Content marketing + conference presence |
| **Average deal size** | $25,000 | Mix of licensing + enterprise consulting |
| **Gross margin** | 75% | Blended consulting + licensing |
| **LTV** | $100,000+ | Multi-year contracts |
| **LTV / CAC** | >20x | Extremely efficient |
| **NRR** | >120% | Cross-sell: audit → retainer → license → certification |
| **ARR target** | $500k–$2M | 20–80 customers at $25k average |
| **Rule of 40** | >40% | 60% growth + 15% margin = 75% ✅ |

---

## 8. 12-Month Roadmap

### Quarter 1 (Months 1–3): Foundation

| Task | Owner | Deliverable | KPI |
|---|---|---|---|
| Train nano-GPT classical (Phase 1.1–1.2) | Technical | `qpt-llm` repo, runnable | Model achieves baseline perplexity |
| Set up NVIDIA Inception + IBM Quantum Credits | Ops | Free compute access | Access confirmed |
| Draft consulting contract (EN + ES) | Legal/Biz | Signed template | Ready to send |
| Register for ColombIA Inteligente (MinCiencias) | Biz | Application submitted | Deadline met |
| Create `qpt-random` (random number generator) | Technical | Open-source repo | 50+ stars in 90 days |
| Target 1 Colombian client (tax advisory) | Biz | Signed contract | First $ received |

### Quarter 2 (Months 4–6): First Hybrid

| Task | Owner | Deliverable | KPI |
|---|---|---|---|
| Simulate individual paradigms (Q, P, T) on GPT layers (Phase 2) | Technical | `qpt-sim` repo | Each paradigm measurable |
| Implement wall-clock vs. hardware-adjusted metrics (Database.md schema) | Technical | Benchmark data for first models | First benchmark report published |
| Close 1–2 consulting clients | Biz | Signed contracts | $10–20k revenue |
| Submit EXIST application (via university partner) | Biz | Application | Deadline met |
| Prepare EIC Pathfinder application | Biz | Draft ready | May 2026 deadline |
| Publish first benchmark paper/blog post | Technical | Public document | 100+ reads |

### Quarter 3 (Months 7–9): Phase 3 — Hybrid Ready

| Task | Owner | Deliverable | KPI |
|---|---|---|---|
| Complete hybrid simulation: Q+P+T mixing in GPT-2 (Phase 3.3) | Technical | `qpt-hybrid` repo, runnable | >10% simulated efficiency vs. classical |
| Publish hybrid benchmark paper | Technical | Paper (arXiv or workshop) | 200+ reads |
| Activate 3 consulting offerings (audit, retainer, workshop) | Biz | Active sales | 3+ active clients |
| Submit SPRIND or EIC Accelerator application | Biz | Applications | Deadlines met |
| Begin C-Corp formation (USA) | Legal | Entity registered | Legal entity active |
| Run-rate calculation | Biz | Revenue run-rate | $30k+/year projected |

### Quarter 4 (Months 10–12): Recurrent + Moat

| Task | Owner | Deliverable | KPI |
|---|---|---|---|
| Phase 4: Improve hybrid performance | Technical | Optimized hybrid models | Measurable improvement |
| Prior-art search + patent attorney consultation | Legal/IP | Patentability opinion filed | Candidate identified |
| Begin patent filing process | Legal/IP | Provisional patent filed | Application submitted |
| 3–4 recurring clients | Biz | Active contracts | NRR >100% (early signal) |
| Year 1 financial review | Biz | Revenue, costs, projections | Year 2 plan ready |

---

## 9. Growth Projections

### 9.1 Bottom-Up Model (12 months)

```
Quarter 1:  1 client × $5k avg   = $5,000
Quarter 2:  2 clients × $8k avg  = $16,000
Quarter 3:  3 clients × $10k avg = $30,000
Quarter 4:  4 clients × $10k avg = $40,000
─────────────────────────────────────────────
Year 1 Total Revenue:            $91,000
Year 1 Costs (bootstrapping):    $5,000–$10,000
Year 1 Net Income:               $81,000–$86,000
```

### 9.2 Top-Down Model (5 years)

```
Year 1: $30–60k    (consulting, bootstrapping)
Year 2: $200–500k  (first licensing deals, grants)
Year 3: $500k–2M   (recurring licensing + enterprise)
Year 4: $2–10M     (standard adoption, multiple hardware partners)
Year 5: $10–50M    (QPT Runtime as industry default)
```

### 9.3 Valuation Proxy

| Milestone | Estimated Valuation | Basis |
|---|---|---|
| Phase 3 hybrid demo + 1 patent filed | $1–3M | Pre-seed deep-tech |
| 3+ hardware partners + $500k ARR | $10–25M | Seed round |
| QPT Runtime adopted by 2+ chip makers | $50–100M | Series A |
| Industry standard position | $500M+ | Series B/C |

---

## 10. Risk Analysis

### 10.1 Critical Risks

| Risk | Likelihood | Impact | Mitigation |
|---|---|---|---|
| **No market demand** (multiparadigm never takes off) | Medium | Fatal | Hedge: consulting revenue regardless of paradigm; open-source builds community even if market is small |
| **Patent rejection** (routing algorithm not novel enough) | Medium | High | Trade secrets as fallback; file before publish; hire IP attorney early |
| **Talent dependency** (single founder = bus factor 1) | High | High | Document everything; open-source forces clean architecture; recruit advisors early |
| **Grant dependency** (>60% of revenue) | Medium | High | Set hard cap: max 50% grants; diversify to 3+ consulting clients by month 6 |
| **Hardware makers build in-house** | Low | Medium | They have no incentive (want to focus on their substrate); QPT is neutral bridge |
| **Big tech builds bridge layer** | Low | High | Timing advantage: 12–18 months head start; open-source community lock-in |

### 10.2 Anti-Patterns to Avoid

1. **Do NOT buy hardware** in year 1–2 (fases 7–8). Use simulators and free cloud credits.
2. **Do NOT build enterprise LLM** before consulting revenue. The LLM is the demo, not the business.
3. **Do NOT depend on grants >50%.** Consulting is oxygen; grants accelerate.
4. **Do NOT publish full architecture before patent filing.** Follow the IP workflow in `legal.md`.
5. **Do NOT raise VC money too early.** Bootstrap to Phase 3, prove demand, then raise.

---

## 11. Legal & IP Strategy

### 11.1 Entity Structure

| Entity | Jurisdiction | Purpose | Timeline |
|---|---|---|---|
| **QPT Inc** (C-Corp) | Delaware, USA | Holding company; IP owner; fundraising vehicle | Month 9–12 |
| **QPT Colombia SAS** | Colombia | Local operations; tax incentives (CTeI); consulting | Month 1–3 |
| **QPT Foundation** (optional) | TBD | Open research, grants, education (not before Year 2) | Year 2+ |

### 11.2 IP Protection Timeline

```
Month 0–3:   Document all inventions in inventor log (dated)
Month 3–6:   Prior-art search on routing algorithm
Month 6–9:   Patent attorney consultation
Month 9–12:  File provisional patent on multiparadigm routing
Month 12+:   Full patent application (USPTO + PCT for EU/DE)
```

### 11.3 Protection Matrix

| Asset | Protection Method |
|---|---|
| QPT brand/name | Trademark (US + Colombia + EU) |
| Source code | Copyright |
| Routing algorithm | Patent |
| Heuristics & calibration | Trade secret |
| Benchmark dataset | Database rights + copyright |
| Training techniques | Trade secret (evaluate for patent) |

### 11.4 Open Source License Strategy

| Component | License | Rationale |
|---|---|---|
| LLM base models | MIT | Maximum adoption; not core IP |
| Simulators | MIT | Research adoption; benchmark standard |
| Benchmark framework | MIT | Industry standard creation |
| Compiler/Runtime | **Proprietary** | Core revenue + moat |
| Routing algorithm | **Patent** | Core IP |

---

## 12. Team & Resources

### 12.1 Current Team (from CREDITS)

| Name | Role | Location |
|---|---|---|
| Daniel Arango Sohm | Original Inventor, Founder | Colombia |
| Karina Villegas Uribe | Legal Assistant | Colombia |
| Jerónimo Hoyos Botero | LLM Specialist | Colombia |
| Simón Escobar Díaz | Quantum Contribution | Colombia |

### 12.2 Hiring Roadmap

| Phase | Team Size | Key Hires |
|---|---|---|
| Month 0–6 | 4 (current) | No new hires; advisors only |
| Month 6–12 | 4–5 | 1 part-time IP attorney (essential) |
| Year 2 | 5–8 | 1 systems engineer, 1 business development |
| Year 3 | 8–15 | Hardware integration team, sales |

### 12.3 Grant Funding Targets (from Grants.md)

| Grant | Geography | Amount | Timeline |
|---|---|---|---|
| ColombIA Inteligente (MinCiencias) | Colombia | Up to COP $2B | Mar–Apr 2026 |
| EXIST-Gründungsstipendium | Germany | Up to €3k/month + €35k | Via university |
| EIC Pathfinder Open | EU | Up to €4M | 12 May 2026 |
| SPRIND Next Frontier AI | Germany | Up to €26.5M/team | 2026 |
| NVIDIA Inception | Global | Cloud credits (not cash) | Ongoing |
| IBM Quantum Credits | Global | Quantum compute credits | Ongoing |
| Extropic Research Grant | Global | Unknown | Rolling |
| ERC Starting Grant | EU | ~€1.5M | Jul–Oct 2026 |

### 12.4 Immediate Next Steps (This Week)

1. [ ] Register for NVIDIA Inception (https://www.nvidia.com/en-us/startups/)
2. [ ] Register for IBM Quantum Credits (https://quantum.ibm.com/programs/educators)
3. [ ] Begin training nano-GPT on available compute
4. [ ] Set up consulting contract template
5. [ ] Identify and reach out to 1 potential Colombian client

---

## Appendix: Key Metrics Dashboard

Track every 90 days:

| Metric | Month 0 | Month 3 | Month 6 | Month 9 | Month 12 |
|---|---|---|---|---|---|
| Revenue (cumulative) | $0 | $5k | $21k | $51k | $91k |
| Active clients | 0 | 1 | 2 | 3 | 4 |
| Grant applications submitted | 0 | 1 | 3 | 4 | 5 |
| Papers published | 0 | 0 | 1 | 2 | 3 |
| Patents filed | 0 | 0 | 0 | 0 | 1 |
| Open-source repos | 0 | 2 | 4 | 5 | 5 |
| GitHub stars (total) | 0 | 100 | 500 | 1,000 | 2,000 |
| Revenue from grants (%) | 0% | 50% | 40% | 35% | 30% |
| Gross margin | 0% | 80% | 82% | 83% | 85% |

---

*Document created: August 2026*
*Review cycle: Every 90 days*
*Owner: Daniel Arango Sohm*
