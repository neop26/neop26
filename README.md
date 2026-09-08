<!--
  GitHub profile README for @neop26 (Aben Samuel).
-->

<h1 align="center">Aben Samuel</h1>

<p align="center">
  <b>Engineering Leadership · Cloud Strategy · AI Governance</b><br />
  Auckland, New Zealand
</p>

<p align="center">
  <a href="https://wellytonian.com" target="_blank">Blog</a> ·
  <a href="https://nz.linkedin.com/in/abensamuel" target="_blank">LinkedIn</a> ·
  <a href="https://twitter.com/neop26" target="_blank">@neop26</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Azure-0078D4?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Bicep-0078D4?logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
</p>

---

### About

I lead cloud and platform engineering in enterprises, where the hard part is rarely the technology — it’s governance, cost, reliability and people, all at once.

- **Technical governance** — engineering standards, SDLC guardrails, security by design
- **Engineering economics** — cloud cost governance, and making spend defensible to a board
- **Reliability** — incident management, observability, and uptime that survives an audit
- **Advisory** — translating architecture decisions for ExCo, SteerCo and board stakeholders

Most of my thinking this year has gone into what changes when AI agents enter that picture.

---

### Writing

I publish at **[wellytonian.com](https://wellytonian.com)**:

- **[Building an AI Operating Model](https://wellytonian.com/posts/ai/building-an-ai-operating-model/)** — model routing, prompt discipline, agent governance and ROI measurement
- **[The AI Governance Problem](https://wellytonian.com/posts/ai/the-ai-governance-problem/)** — why casual model usage stops working once billing and risk catch up
- **[The Concurrency Paradox](https://wellytonian.com/posts/ai/spec-driven-parallel-dev/)** — when agents outpace review, coordination becomes the bottleneck

Earlier posts cover Azure cost control, Bicep, GitHub Actions and Linux hardening.

---

### Building

Two tools, in stealth for now. Both come from the same conviction — that a platform can be efficient and compliant at the same time, rather than trading one against the other. One of them is deliberately outside my usual stack; building where I'm least comfortable is the whole point.

Most of my work lives in private repositories, though I hope to open more of it up before long. Learning is the constant — that part I'd never give up.

---

### Open Source

**[microsoft/apm](https://github.com/microsoft/apm)** — Agent Package Manager

[PR #443](https://github.com/microsoft/apm/pull/443) — `.claude/commands/` was being created on every install, even for projects targeting Copilot. Auditing the integration path showed one of thirteen integrator calls had neither an external gate nor a self-guard, so it built the directory tree from nothing. Fixed, covered with regression tests, and shipped in [v0.8.6](https://github.com/microsoft/apm/releases/tag/v0.8.6).

---

### How I Work

- **Outcomes over output** — cost curves, uptime and customer impact, not story points
- **Infrastructure as code** — versioned, repeatable, reviewable
- **Secure by default** — identity, boundaries and guardrails designed in, not bolted on
- **Hands-on** — I still read the diff

Easier to show than to claim: [ubupublic](https://github.com/neop26/ubupublic) opens the SSH port *before* enabling the firewall, names its sshd drop-in `01-` because sshd honours the first match, and dropped `curl | sudo sh` in favour of a signed repository.

---

### Connect

- **LinkedIn:** [nz.linkedin.com/in/abensamuel](https://nz.linkedin.com/in/abensamuel)
- **X:** [@neop26](https://twitter.com/neop26)
- **Blog:** [wellytonian.com](https://wellytonian.com)

If you’re working on cloud governance, AI adoption in the enterprise, or platform engineering, I’m always keen to swap notes.

---

<p align="center">
  <i>Cloud is easy. Doing it well at scale, with real constraints and real people, is the hard part.</i>
</p>