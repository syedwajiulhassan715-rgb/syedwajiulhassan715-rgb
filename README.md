<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Waji Ul Hassan Syed, BSc AI at JKU Linz, Agentic AI and Evaluation, Vienna"/>

<p>
  <a href="https://www.linkedin.com/in/waji-ul-hassan-syed-48832035a/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:syedwajiulhassan715@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-4F7CFF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://rental-law-navigator.vercel.app"><img src="https://img.shields.io/badge/Live_demo-Locus-2DD4BF?style=for-the-badge&logo=vercel&logoColor=white" alt="Locus live demo"/></a>
</p>

<img src="./assets/terminal.svg" width="100%" alt="Terminal: whoami, focus, principles, shipped projects, and current work"/>

🏆 **1st** Hack-Nation Global AI Hackathon, Linz hub &nbsp;·&nbsp; **1st** AIM Healthcare Hackathon Vienna, clinical documentation (IBM challenge)<br/>
**Winner** proximata Vienna &nbsp;·&nbsp; **Talona track winner** Building Better Worlds Hackathon 2026

</div>

<img src="./assets/divider.svg" width="100%" alt=""/>

## ✦ Featured project

<table>
<tr>
<td>

<a href="https://github.com/syedwajiulhassan715-rgb/vla-robustness-analysis">
  <img src="https://raw.githubusercontent.com/syedwajiulhassan715-rgb/vla-robustness-analysis/main/figures/fig2_confident_failure.png" width="100%" alt="OpenVLA confident failure figure"/>
</a>

### 🤖 VLA Robustness Analysis: does OpenVLA know when it is about to fail?

**1,200 LIBERO episodes under visual and language perturbations.**
Success drops from **81% to 12%** when the instruction's referent is removed, yet mean action confidence stays near **0.78** in every condition and barely separates success from failure. The model fails confidently, so a runtime monitor watching that signal would see nothing wrong.

`OpenVLA` `LIBERO` `robustness` `failure prediction` `research paper`

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white"/> <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white"/>

**[Repository and paper](https://github.com/syedwajiulhassan715-rgb/vla-robustness-analysis)**

</td>
</tr>
</table>

## ✦ Selected work

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/syedwajiulhassan715-rgb/Corti-Hackathon">
  <img src="https://raw.githubusercontent.com/syedwajiulhassan715-rgb/Corti-Hackathon/main/docs/assets/readme/hero-live-pipeline.png" width="100%" alt="ECHO live clinical pipeline"/>
</a>

### 🩺 ECHO
**Longitudinal clinical-AI ward command center**

Turns routine observations into replayable patient trajectories. It escalates only on persistent or corroborated change, then prepares evidence-backed actions for a human to approve.

`event sourcing` `deterministic replay` `human-in-the-loop` `390 tests`

<sub>TypeScript · Next.js · Node.js · Corti APIs &nbsp;|&nbsp; Corti Hackathon</sub>

</td>
<td width="50%" valign="top">

<a href="https://rental-law-navigator.vercel.app">
  <img src="https://raw.githubusercontent.com/syedwajiulhassan715-rgb/Locus/main/assets/screens/02-building-orbit-v2.jpg" width="100%" alt="Locus: 3D view of a Los Angeles building with the rules that apply to it"/>
</a>

### 📍 Locus
**Rental housing law, traced to the sentence**

Pick any building and see which housing laws apply. Every quote the LLM extracts is checked verbatim against the statute before it is stored, and a missing fact gives `unknown` instead of a guess. **[▶ Live demo](https://rental-law-navigator.vercel.app)**

`cited to the sentence` `CA · NJ · MA` `EN / ES` `no live LLM at answer time`

<sub>Python · FastAPI · TypeScript · Vercel &nbsp;|&nbsp; Hack-Nation · RealPage challenge</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/syedwajiulhassan715-rgb/semiconductor-process-control">
  <img src="https://raw.githubusercontent.com/syedwajiulhassan715-rgb/semiconductor-process-control/main/reports/figures/fig02_cusum.png" width="100%" alt="CUSUM chart catching a yield shift"/>
</a>

### 🏭 Semiconductor Process Control
**SPC and root-cause screening on 1,567 real fab runs**

A standard p-chart misses a real 3× yield improvement (12.92% → 4.11%, p = 2×10⁻⁹) that a CUSUM catches. 16 of 17 "root causes" turn out to be a time confound, and the published prediction baseline fails an honest split.

`423 tests` `CI` `decision log D1–D45` `live demo`

<sub>Python · SciPy · Power BI star schema · UCI SECOM</sub>

</td>
<td width="50%" valign="top">

<a href="https://github.com/syedwajiulhassan715-rgb/fonio-hack">
  <img src="https://raw.githubusercontent.com/syedwajiulhassan715-rgb/fonio-hack/main/docs/architecture-flow.png" width="100%" alt="Fonio refill agent flow"/>
</a>

### 🦷 Fonio Refill Agent
**Voice AI that refills cancelled appointments in about a minute**

When a patient cancels, the agent ranks the waitlist with explainable scores, calls the best candidate through Fonio, and keeps looping until the slot is booked, with no one at the desk picking up a phone.

`idempotent orchestration` `webhooks` `attempt ledger`

<sub>Next.js · TypeScript · Prisma · SQLite &nbsp;|&nbsp; START Hack Vienna '26</sub>

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br/>

| Project | What it does | Stack |
| :-- | :-- | :-- |
| 📈 [**U.S. Macroeconomic Indicators**](https://github.com/syedwajiulhassan715-rgb/U.S-Macroeconomic-Indicators) | Eight FRED series, 2000–2026. Fed rate peaks lead unemployment peaks by ~32–35 months, and rate transmission is much faster post-COVID | pandas · Plotly · SciPy |
| 🔎 [**TraceCause**](https://github.com/syedwajiulhassan715-rgb/Trace-Cause) *(WIP)* | Injects faults into a microservice system and ranks the root-cause service from OpenTelemetry traces. The LLM only explains; it never decides | Java · OpenTelemetry · Postgres · React |
| 📰 [**AI Signal Feed**](https://github.com/syedwajiulhassan715-rgb/signal-feed) | Daily briefing from arXiv, Hacker News and newsletters, ranked by an LLM and emailed every morning | Python · Groq · RSS |
| ⚖️ [**GitHub Comparator**](https://github.com/syedwajiulhassan715-rgb/github-comparator) | Paste up to 5 repos and get an AI side-by-side comparison | Python · GitHub API · Groq |
| 📚 [**arXiv Digest**](https://github.com/syedwajiulhassan715-rgb/arxiv-digest) | Topic-based paper digest delivered by email | Python · arXiv API |

</details>

<img src="./assets/divider.svg" width="100%" alt=""/>

## ✦ How I build

<table>
<tr>
<td width="50%" valign="top">

**🧠 AI Systems:** agents, LLM integrations, evaluation, workflow automation<br/>
**🔬 Applied ML:** robustness experiments, VLA evaluation, empirical analysis<br/>
**⚙️ Backend:** APIs, event-driven systems, state machines, persistence

</td>
<td width="50%" valign="top">

**🖥️ Product:** Next.js and React human-in-the-loop interfaces<br/>
**📊 Data:** statistical testing, SPC, BI modelling, visual analysis<br/>
**🔁 Automation:** Python pipelines, scheduled jobs, data aggregation

</td>
</tr>
</table>

## ✦ Tech stack

<div align="center">

**Languages & ML**<br/>
<img src="https://skillicons.dev/icons?i=python,typescript,javascript,java,pytorch,sklearn&theme=dark" alt="Languages and ML"/>

**Web & Backend**<br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,nodejs,fastapi,tailwind,prisma&theme=dark" alt="Web and backend"/>

**Data & Infra**<br/>
<img src="https://skillicons.dev/icons?i=postgres,sqlite,docker,git,github,vercel&theme=dark" alt="Data and infra"/>

</div>

## ✦ Currently

- 🦾 Vision-Language-Action models and embodied AI, at JKU's Institute of Pervasive Computing and on the TU Wien Robotics Club VLA team
- 🧾 Reliable, auditable AI agents
- 📏 Evaluation methods for AI systems
- 🔁 AI-native workflow automation
- 💼 Open to AI/ML internships and working-student roles in Vienna / Austria

<img src="./assets/divider.svg" width="100%" alt=""/>

---

<div align="center">

### Build useful systems. Measure whether they actually work.

<a href="https://www.linkedin.com/in/waji-ul-hassan-syed-48832035a/"><img src="https://img.shields.io/badge/LinkedIn-Waji_Ul_Hassan_Syed-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:syedwajiulhassan715@gmail.com"><img src="https://img.shields.io/badge/Gmail-syedwajiulhassan715@gmail.com-4F7CFF?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4F7CFF,45:1e3a8a,100:0f172a&height=110&section=footer" width="100%" alt=""/>

</div>
