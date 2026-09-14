<div align="center">

# Waji Ul Hassan Syed

**I build AI systems that reason over real workflows, automate useful work, and expose enough evidence to understand when they fail.**

`AI Engineering` · `Agentic Workflows` · `Data Analysis` · `VLA / Robotics` · `Applied ML`


</div>

---

## Selected Work

###  Seiconductor Process Control
**Statistical process control and root-cause screening on 1,567 production runs of real fab data**

An analysis of where the obvious approach goes wrong. The conclusion is that this line needs a monitoring scheme, not a prediction model and the project is built to demonstrate that.

* Standard p-chart misses a real threefold yield improvement (12.92% → 4.11%, Fisher p = 2×10⁻⁹); a CUSUM catches it
* 16 of 17 apparent root causes turn out to be a time confound, not a cause
* The published failure-prediction baseline does not survive an honest train/test split
* Deterministic 23s pipeline, 87 passing tests, decision log (D1–D24), Power BI star schema

**Stack:** Python · SciPy · Statistical Process Control · Power BI · UCI SECOM

[View project →](https://github.com/syedwajiulhassan715-rgb/semiconductor-process-control)

---

### ECHO
**A longitudinal clinical-AI ward command center built for the Corti Hackathon**

ECHO turns isolated observations into replayable patient trajectories, waits for persistent or corroborated change, and prepares evidence-backed next actions for human approval.

* Event-sourced longitudinal patient memory
* Deterministic deterioration and prioritization engine
* Corti transcription, facts, coding, and generation integrations
* Human-in-the-loop action proposals
* Deterministic replay and auditability
* 390 automated tests

**Stack:** TypeScript · Next.js · React · Node.js · Corti APIs · Event Sourcing

[View project →](https://github.com/syedwajiulhassan715-rgb/Corti-Hackathon)

---

### VLA Robustness Analysis
**Empirical robustness evaluation of OpenVLA on LIBERO**

Studied how a Vision-Language-Action model behaves under controlled visual and instruction perturbations — and whether its own action confidence predicts failure.

* Evaluated visual corruption and instruction perturbation conditions across repeatable LIBERO episodes
* Built an evaluation and analysis pipeline for OpenVLA
* Found that action confidence can stay almost unchanged while task success collapses
* Produced reproducible results, figures, analysis, and a research paper

**Stack:** Python · OpenVLA · LIBERO · PyTorch · CUDA · Experimentation

[View project →](https://github.com/syedwajiulhassan715-rgb/vla-robustness-analysis)

---

###  Fonio Refill Agent
**AI voice automation for filling cancelled appointment slots**

A cancellation triggers an explainable wait-list ranking, calls the strongest candidate through Fonio, processes the result, and continues until the appointment is recovered.

* Explainable candidate scoring
* Idempotent workflow orchestration
* Fonio outbound calling + post-call webhooks
* Deterministic offline demo provider
* Persistent attempt ledger
* Receptionist and owner dashboards

**Stack:** Next.js · TypeScript · React · Prisma · SQLite · Fonio

[View project →](https://github.com/syedwajiulhassan715-rgb/fonio-hack)

---

### U.S. Macroeconomic Indicators
**A visual analysis of eight FRED series, 2000–2026**

Traces four relationships across the dot-com bust, 2008, and COVID — including why unemployment lags Fed rate peaks by nearly three years.

* Rate peaks lead unemployment peaks by ~32–35 months, confirmed across both completed rate cycles
* Every monetary-cycle recession in the window was preceded by a yield-curve inversion (COVID the sole external-shock exception)
* Rate-to-unemployment transmission is markedly faster post-COVID (+0.44 by lag 6 vs near-zero pre-2008)
* Findings hedged to their evidence — asymmetric sentiment effect reported as suggestive, not firm

**Stack:** Python · pandas · Matplotlib · Plotly · SciPy · FRED API

[View project →](https://github.com/syedwajiulhassan715-rgb/U.S-Macroeconomic-Indicators)

---

### AI Signal Feed
**An automated daily intelligence feed for AI builders**

Collects research and industry signals from Arxiv, Hacker News, and newsletters, ranks them with an LLM, and delivers a concise morning briefing automatically.

**Stack:** Python · Groq · Arxiv API · Hacker News API · RSS · Automation

[View project →](https://github.com/syedwajiulhassan715-rgb/signal-feed)

---

## Engineering Focus

```text
AI Systems    → agents, LLM integrations, evaluation, workflow automation
Applied ML    → robustness experiments, VLA evaluation, empirical analysis
Backend       → APIs, event-driven systems, state machines, persistence
Product       → Next.js, React, TypeScript, human-in-the-loop interfaces
Automation    → Python pipelines, scheduled workflows, data aggregation
```

## Tools I Work With

<p>
  <img src="https://skillicons.dev/icons?i=python,typescript,javascript,nextjs,react,nodejs,pytorch,git,github,docker" />
</p>

## Currently Exploring

* Vision-Language-Action models and embodied AI
* Reliable and auditable AI agents
* Evaluation methods for AI systems
* AI-native workflow automation

---

<div align="center">

### Build useful systems. Measure whether they actually work.

[GitHub](https://github.com/syedwajiulhassan715-rgb) · Email: **[syedwajiulhassan715@gmail.com](mailto:syedwajiulhassan715@gmail.com)**

</div>
