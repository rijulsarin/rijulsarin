# Rijul Sarin

**Senior Product Manager · AI/ML Systems · Seattle, WA**

[LinkedIn](https://linkedin.com/in/rijulsarin) · [rijul.sarin@gmail.com](mailto:rijul.sarin@gmail.com)

---

I build AI products that have to work at scale — not in demos. At Amazon, I own the ML pipeline that determines language compliance for millions of products tied to billion dollars in annual revenue. Before that, I was a software engineer and product lead at Cisco for seven years. That background shapes how I think: I care about what actually happens at inference time, not just what the model was supposed to do.

My current focus is on the systems side of AI product — pipeline observability, Human-in-the-Loop design, and the tricky middle ground between autonomous agents and accountable decision-making.

---

## What I'm building here

This is a working lab, not a portfolio showcase. Each project connects to a real problem I've faced as a PM and couldn't find a good off-the-shelf tool for.

| Repo | What it solves | PM skill it demonstrates |
|------|---------------|--------------------------|
| [`ml-pipeline-pm-toolkit`](#) | Design multi-stage ML systems with accuracy trade-off modeling and HITL sampling calculators | ML system design, observability frameworks |
| [`ai-eval-kit`](#) | Lightweight LLM evaluation for PMs — sensitivity testing, hallucination detection against source documents | Product quality, risk mitigation |
| [`pm-strategy-engine`](#) | Executable frameworks — North Star metric modeling, GTM scenario simulation | Product strategy, framework codification |
| [`mcp-product-intelligence`](#) | MCP server that lets PMs query product analytics (Amplitude/Mixpanel) in natural language | Technical leadership, PM-Eng gap bridging |
| [`habitlock-ai`](#) | Behavioral science + AI app for habit formation (long-term personal product bet) | Zero-to-one product development |

---

## Why these projects, not generic "AI PM tools"

The `ml-pipeline-pm-toolkit` exists because when I was designing a 4-stage ML observability framework at Amazon, there was nothing that helped a non-engineer PM reason about where accuracy was being lost across a pipeline. I built internal tooling; this is the generalized version.

The HITL sampling calculator inside it came from a real problem: how do you reduce manual review overhead on a million seller offers without losing statistical confidence? We went from full-population review to a 5% sample at 95% CI — that's a 95% reduction in overhead. The math isn't complicated, but no one had built a PM-facing tool for it.

The `ai-eval-kit` came from watching PMs at every company treat LLM quality as a binary pass/fail. Prompt sensitivity matters. Hallucination rates against known ground truth matter. This library gives a PM the instrumentation to find out before a feature ships.

---

## Background

**Amazon** (2024–present) — Senior PM, North America Language Experience. Running the ML compliance platform for Canada's bilingual packaging law. Pipeline covers millions of products, de-risks billions in annual revenue, and uses a multi-stage text classification system designed from scratch.

**Spectio** (2023) — PM at an AI-powered BI startup. Led customer discovery (interviews with CIOs/CTOs), built the GenAI product roadmap, and ran a build-vs-buy analysis across the BI AI tool landscape.

**Cisco** (2015–2022) — Started as a software engineer, ended as product lead for the Security Business Group. Shipped a cloud-native email security product that generated $22M over three years. Ran a 20-person UI/UX engineering team.

**Education** — MBA, UW Foster School of Business (Dean's Scholar) · MTech in Software Systems with Data Analytics specialization, BITS Pilani (top 1%) · BTech in Electronics & Communication, VIT

---

## Technical foundation

```
AI/ML:     LLMs, NLP & text classification, multi-stage ML pipelines, OCR,
           HITL system design, LLM evaluation, agentic workflows, MCP

PM craft:  Zero-to-one development, roadmap prioritization, A/B testing,
           North Star metrics, BRD/PRD authoring, GTM strategy, regulatory strategy

Engineering: Python, SQL, R, JavaScript (React/Angular), AWS, Tableau, GitHub
```

---

*I write occasionally about AI product design and ML system trade-offs. If something in these repos is useful or broken, open an issue — I'd genuinely like to know.*
