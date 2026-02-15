# From Model-Level Explanations to Legal Evidence
## Auditing Bias and Explainability in GDPR-Compliant Automated Decision Systems
##  Video Walkthroughs (YouTube)

I share walkthroughs explaining AI governance, explainability, fairness audits, and GDPR-aligned evidence packs on my YouTube channel:

https://www.youtube.com/@suelook9562

**Start here:** [Read the full paper (PDF)](publications/ssrn-5783263.pdf)

SSRN abstract:[View abstract page](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5783263)

> **This repo is a preview. The PDF is the playbook** - it contains the full method, interpretation guidance, and audit-ready evidence structure (not just charts).
**Written as an evidence pack - not a blog post.**
## Quick navigation
---

## Article 2 (Now Live): Including or Excluding Protected Attributes in AI Models

This paper examines the legal, ethical, and technical trade-offs involved in using protected attributes (e.g., sex, race, age, disability) in AI systems. It introduces a governance-led decision framework to support fairness testing while remaining compliant with GDPR and aligned to the EU AI Act.

Who this is for:

AI governance and assurance teams

GDPR Article 22 reviews and special category data governance

EU AI Act high-risk system assessments

Fairness, bias, and explainability audit teams

 YouTube walkthrough (now live):
https://youtu.be/hgwjOPxe5P4

 SSRN paper (now live):
https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6020234

- Figures: [visuals/](visuals/)
- Evidence pack: [publications/](publications/)

If you work in **AI governance, Model Risk Management, Compliance, Risk & Controls, Data Protection, Supplier Assurance, or Responsible AI**, the README visuals are only the preview.

The **PDF is the full evidence playbook**: it shows how to take *model outputs* (explainability + fairness results) and turn them into **audit-ready, governance-ready documentation** that supports review, challenge, and accountability in real operational settings.

### Why this PDF matters for day-to-day governance
Because “we have SHAP” is not the same as “we can defend this decision process.”

In practice, governance teams need:
- a clear explanation of **what drives outcomes** at model level,
- a way to spot and communicate **potential disparities** across groups,
- language and structure that can survive **internal scrutiny, audit, and regulatory questioning**,
- a repeatable approach to documenting risk and safeguards where automated decisions have significant impact.

This paper is written to help you do exactly that.

### What you get when you open the PDF (usable takeaways)
- **A repeatable audit logic**: how to structure your evidence trail so it’s reviewable and defensible.
- **Model-level explainability** (SHAP global): how to interpret key drivers and communicate them clearly.
- **Fairness testing evidence** (sex and age group): how to read selection-rate patterns and flag potential disparity signals.
- **Interpretation that leads to action**: what to do next (monitoring, thresholds, escalation, documentation updates) when signals appear.
- **Governance framing**: how to connect technical results to accountability, transparency, and meaningful oversight in practice.

### Recommended reading path (if you’re busy)
- **2 minutes:** open PDF → scan headings and figures to understand the flow.
- **10 minutes:** read the explainability and fairness interpretation sections.
- **30 minutes:** follow the full evidence chain and reuse the structure for your own model review pack.

### Bottom line
If you want the *real value* - the logic, the interpretation, and the evidence structure you can reuse at work - **open the PDF**.
The README shows the highlights; the paper gives you the full governance method.


### Recruiter summary (30 seconds)
This repository is a **Responsible AI audit evidence pack** showing how to translate:
- **Explainability** (SHAP = global patterns and case-level explanations)
- **Fairness testing** (group metrics and disparity interpretation)
into **GDPR-ready documentation** for automated decision systems (Article 22-relevant contexts).

## What you can open immediately
- **Working paper (SSRN):** https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5783263
- **Key visuals:** `visuals/` (SHAP + fairness outputs)
- **Evidence pack / publication files:** `publications/`
- **GitHub Pages preview:** https://22ifeoma22.github.io/responsible-ai-portfolio-preview/

## Open the PDF (this is where the value is)

If you work in **AI governance, Model Risk, Compliance, Risk & Controls, Data Protection, Supplier Assurance, or Responsible AI** - don’t stop at the charts.

**Open the PDF first:** [publications/ssrn-5783263.pdf](publications/ssrn-5783263.pdf)
This repo is a *preview evidence pack* - but the **PDF is the playbook**: how to document, interpret, escalate, and explain results to stakeholders.

### Why open it
- **Charts don’t pass audits.** The PDF shows how SHAP + fairness outputs become **audit-ready evidence**.
- **Governance = documentation.** You get **reusable structure + wording** for review packs and sign-off.
- **It answers “what next?”** It includes interpretation guidance + actions when disparities appear.

### Quick skim path
- **60 seconds:** scan the Key Figures in this README (teaser only)
- **5 minutes:** PDF → figures + interpretation
- **15 minutes:** evidence framing + recommended actions

**Bottom line:** the README visuals are the hook - the **PDF is the toolkit** 

**Best starting point:** Open the PDF - the README is a preview, the PDF contains the full method and interpretation + evidence template.

---
### 5-minute skim path (PDF)
1) **Explainability (SHAP):** what drives outcomes at model level  
2) **Fairness (sex + age):** selection-rate disparities + what they mean  
3) **Evidence mapping:** how to package outputs into audit-ready documentation  
If you do model reviews / governance sign-off, this is the reusable workflow.

## Key figures (preview)

![SHAP global explanation (beeswarm)](visuals/SHAP%20global%20explanation%20(beeswarm).png)
![Fairness — Selection rate by sex (male vs female)](visuals/Fairness%20-%20Selection%20rate%20by%20sex%20(male%20vs%20female).png)
![Fairness — Selection rate by age group](visuals/Fairness%20-%20Selection%20rate%20by%20age%20group.png)

---

## Evidence → governance question mapping
| Evidence artifact | What it shows | Governance question answered |
|---|---|---|
| SHAP (global) | Main drivers across population | “Can we explain outcomes at model level?” |
| LIME (local) | Why one person got an outcome | “Can we support review/challenge for individuals?” |
| Fairness metrics | Group disparities | “Are outcomes disproportionately adverse?” |
| Audit narrative | limits + safeguards | “What controls reduce risk and enable rights?” |

---
If you want the extended evidence pack (more artefacts + templates), open an Issue titled **“Request: extended pack”**.

## Working paper (SSRN)
**Title:** *From Model-Level Explanations to Legal Evidence: Auditing Bias and Explainability in GDPR-Compliant Automated Decision Systems*  
Read on SSRN: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=5783263
---

## Article 3 (Now Live): Ethics Becomes Enforceable Governance When Harm is Foreseeable and Preventable

This paper establishes the operational boundary between ethical intention and enforceable governance. Using a healthcare wearable fall monitoring use case, it demonstrates how foreseeable harm becomes measurable audit evidence through structured monitoring, explainability (SHAP, LIME), logging, escalation, and lifecycle governance.

Aligned with:

- EU AI Act (risk management, monitoring, accountability)
- GDPR (Article 22, fairness, accountability, auditability)
- ISO/IEC 42001 (AI management system lifecycle governance)
- ISO/IEC 27001 and 27701 (security and privacy controls)

Start here: [Read the full paper (PDF)](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=6128487)

SSRN abstract: Add your SSRN link here

---

