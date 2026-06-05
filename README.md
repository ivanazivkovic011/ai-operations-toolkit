# AI Operations Toolkit

A suite of AI agents and operational frameworks for Chief of Staff functions,
organizational intelligence, and executive operations.

Built and maintained by [Ivana Zivkovic](https://linkedin.com/in/ivanazivkovic011) —
Chief of Staff & AI Operations Strategist.

---

## Agents

| Agent | Purpose | File |
|---|---|---|
| **Alex — Elite Recruiter** | 12-step resume tailoring, ATS optimization, cover letter, salary strategy, and interview prep | [agents/elite-recruiter.md](./agents/elite-recruiter.md) |
| **Company Qualifier** | Deep company intelligence before applying: funding, culture, AI maturity, fit assessment, go/no-go | [agents/company-qualifier.md](./agents/company-qualifier.md) |
| **Job Scout** | Daily AI job intelligence report — matches roles against defined criteria and scores fit | [github.com/ivanazivkovic011/job_scout](https://github.com/ivanazivkovic011/job_scout) |
| **ATLAS Financial Intelligence System** | Autonomous daily market briefings via email — Python, Claude API, RSS aggregation | [github.com/ivanazivkovic011/atlas-financial-agent](https://github.com/ivanazivkovic011/atlas-financial-agent) |

---

## Resume Builder

A production-grade, ATS-optimized resume generator built with Node.js and the
`docx` package. Outputs a fully formatted, ATS-safe .docx file.

**Design system:** Calibri throughout, single column, standard bullets,
named competency pillars, 0.75" margins, 2-page maximum.

**ATS compliance:** 95%+ target score, keyword audit built in, no tables,
no images, no special characters.

[View template](./agents/resume-builder-template.js)

---

## Case Studies

### 60% Overhead Reduction — Diocese of California
Recruited as interim EA during a historic 20-year episcopal leadership transition.
Elevated to de facto Chief of Staff within 3 weeks. Delivered:
- 60% increase in executive strategic focus time through calendar architecture
  and anticipatory operations
- 40%+ increase in organizational engagement in 90 days using behavioral
  neuroscience frameworks, zero mandates
- 70% improvement in stakeholder satisfaction across city officials,
  nonprofit boards, and institutional partners
- 100% operational continuity through leadership transition with zero
  reputational disruptions

### 97% Retention — Wellness-Tech Platform (The Virtual Studio)
Co-founded and scaled a wellness-tech platform from zero over four years.
- Bootstrapped to 250+ clients and 5,000+ classes delivered
- 97% client satisfaction and retention across the full tenure
- 60% reduction in administrative overhead through AI-assisted automation
- $10,000+ raised for social causes in Year 1 through strategic event production

---

## Frameworks

- AI Operations Audit Framework *(coming soon)*
- Executive Onboarding Playbook *(coming soon)*

---

## Stack

Built using the Claude AI ecosystem. Agents are prompt-based and compatible
with Claude.ai, Claude API, and any LLM with instruction-following capability.

Resume Builder requires Node.js and the `docx` npm package.

```bash
npm install docx
node agents/resume-builder-template.js
```

---

## Usage

Each agent is self-contained with a setup section for client configuration.
Replace `[PLACEHOLDER]` values with client-specific information before running.

Recommended workflow for job applications:
1. Run **Job Scout** to surface matching roles
2. Run **Company Qualifier** on target company
3. Run **Elite Recruiter** to build the full application package

---

## Connect

[LinkedIn](https://linkedin.com/in/ivanazivkovic011) |
[Portfolio](https://ivanazivkovic.xyz/)
