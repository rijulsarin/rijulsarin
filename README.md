# Rijul Sarin

**Senior Product Manager · AI/ML Systems · Seattle, WA**  
[LinkedIn](https://linkedin.com/in/rijulsarin) · [rijul.sarin@gmail.com](mailto:rijul.sarin@gmail.com)

---

I'm a Senior PM with 10+ years across e-commerce, enterprise security, and AI-native SaaS. I have a software engineering background — I spent seven years at Cisco as an engineer before moving into product — and it shapes how I think about ML systems, accuracy trade-offs, and the gap between what a model is supposed to do and what it actually does in production.

My current focus is on the systems side of AI product: pipeline observability, Human-in-the-Loop design, agentic workflows, and the product decisions that sit between "technically possible" and "ships responsibly."

This GitHub is a working lab. Everything here is something I built because I couldn't find a good existing tool for the problem — not to demonstrate PM skills in the abstract, but because the problem was real and worth solving.

---

## Projects

### [`habitlock-ai`](#) — Behavioral science + AI for habit formation
A long-term personal product bet. The hypothesis: habit failure is almost never a motivation problem — it's a feedback loop problem. Most habit apps optimize for streaks, which is the wrong variable. This one is built around implementation intentions, identity-based reinforcement, and contextual nudges powered by a small LLM layer.

This is the project I care most about. The README is structured as a living PRD — problem statement, assumptions, what I've learned from early users, and where the current model falls short.

`zero-to-one` `behavioral-science` `LLM-product` `multi-agent architecture` `mobile`

---

### [`ai-pm-eval-kit`](#) — LLM quality testing for non-engineers
A lightweight Python library for PMs who ship LLM features but don't have the engineering bandwidth to build proper eval infrastructure. It does two things: runs sensitivity tests on a prompt across a set of input variations to surface instability, and checks model outputs for hallucinations against a provided source document.

The goal is that a PM can run this in a notebook — no ML background required. The library handles the test harness; you bring the prompts and the ground truth.

`LLM-evaluation` `RAG` `hallucination-detection` `prompt-testing` `python`

---

### [`pm-decision-engine`](#) — Executable PM frameworks
A Python module built around the PM frameworks I actually use, not the ones that look good in a presentation. Currently includes: opportunity sizing with confidence intervals, North Star metric decomposition, and a RICE scorer that forces you to document your assumptions rather than just entering numbers.

The README for each framework explains not just how to use it but where it breaks — what the inputs are likely to get wrong and what that does to the output. I find that more useful than a clean demo.

`product-strategy` `decision-frameworks` `python`

---

### [`finops-for-ai`](#) — Token cost and model selection calculator
A tool for PMs and engineering leads who need to make model selection decisions with cost in mind. You input expected MAU, average prompt length, and task complexity tier — it outputs projected monthly spend across model options (GPT-4o, Claude Sonnet, Claude Haiku, Gemini Flash, etc.) and flags where a smaller model is likely sufficient.

The framing is deliberate: this isn't about finding the cheapest model, it's about matching model capability to task requirements. The most expensive model is the one you're using where a smaller one would have done the job.

`LLM-cost` `model-selection` `unit-economics` `python`

---

### [`mcp-personal-lab`](#) — MCP server for personal workflow
A local MCP server that connects to tools I actually use — currently Notion for notes and a personal reading list, with a calendar integration in progress. The point is hands-on fluency with MCP architecture: how tools get exposed, how context flows between a host and a server, and where the current protocol creates friction.

The repo includes a short walkthrough of using it inside Claude and Cursor. Less about the implementation, more about what MCP unlocks and where its current limitations are from a product perspective.

`model-context-protocol` `MCP` `agentic-workflows` `claude`

---

## Background

**Amazon** (2024–present) — Senior PM, North America Language Experience. Building and scaling an AI-powered language compliance system across Amazon's Canada marketplace.

**Spectio** (2023) — PM at an AI-powered BI startup. Led customer discovery across 40+ interviews with CIOs and CTOs, built the GenAI product roadmap, and ran the build-vs-buy analysis that shaped the company's core go-to-market strategy.

**Cisco** (2015–2022) — Started as a software engineer, ended as product lead for the Security Business Group. Spent seven years shipping enterprise security products, running cross-functional teams, and learning what it means to own a product that 300K+ enterprise customers depend on.

**Education** — MBA, UW Foster School of Business (Dean's Scholar, 2022–2024) · MTech in Software Systems with Data Analytics, BITS Pilani (top 1%) · BTech in Electronics & Communication, VIT

---

## Stack

```
AI/ML       LLMs · RAG & Retrieval systems · multi-agent architectures · NLP & text classification
            · multi-stage ML pipelines · OCR · HITL system design · LLM evaluation · agentic workflows · MCP

PM          Zero-to-one development · roadmap prioritization · A/B testing
            North Star metrics · PRD authoring · GTM strategy · regulatory product

Engineering Python · SQL · R · JavaScript (React/Angular) · AWS · Tableau · GitHub
```

---

*If something here is useful or broken, open an issue. I'd genuinely like to know.*
