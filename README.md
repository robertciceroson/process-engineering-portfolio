# README Entry — AI Email Triage VSM

> Paste this block into your `process-engineering-portfolio` README under a new portfolio item entry. Adjust the item number to match your existing sequence.

---

## Item #XX — AI Email Triage & Workflow Automation: Value Stream Map

**Engagement:** Gateway AI Advisory (Aug 2025 – Present)
**Tool:** Microsoft Visio · VSM methodology (Lean)
**Files:** `Current State_versus_Future State Emails Triage Process_VSM.pdf` · `VSM_AI_Email_Triage.vsdx` · `vsm_ai_email_triage.png`

### Overview

Value stream map (VSM) for an AI-powered email triage and routing automation engagement. The map documents the current-state manual process and the future-state AI-automated process side-by-side, with quantified lead time, cycle time, and labor metrics at each step.

**Stack:** Make.com + LLM API (AI classification and routing layer)

### Current State — Manual Email Triage

| Metric | Value |
|---|---|
| FTEs | 4 |
| Weekly labor hours | 28 hrs/week (7 hrs × 4 FTEs) |
| Annual labor cost | $87,360 |
| Avg. response time | 4–6 hours |
| Misrouting rate | ~15% |
| Manual effort per email | 8–17 min |
| Volume visibility | None |

**Total lead time:** ~5.5 hours per email (dominated by wait time and rework queues)

Process steps: Email Inbox Review → Categorize & Triage → Manual Routing → Dept Receive & Process

Key waste identified: multi-hour wait queues between steps, ~15% misrouting requiring rework loops, zero volume-tracking visibility, multi-step handoffs.

### Future State — AI-Automated Triage (Make.com + LLM API)

| Metric | Value |
|---|---|
| FTEs | 1 (oversight only) |
| Annual labor cost | $13,104 (−85%) |
| Avg. response time | < 15 min (−97%) |
| Misrouting rate | ~0% |
| AI processing time per email | < 30 sec |
| Volume visibility | Full dashboard |

**Total lead time:** ~13 min per email (99% reduction vs. current state)

Process steps: Email Intake (automated trigger) → AI Classification (LLM API) → Automated Routing (rules-based + LLM) → Dept Queue & Dashboard

### ROI Summary

| | Value |
|---|---|
| Net annual benefit | $121,816 |
| Payback period | ~1 month |
| 3-Year ROI | 3,667% |

### Lead Time Timeline

The VSM timeline bar uses standard lean color coding:
- **Green** = Value-Added (VA) time: ~12 min total (~4% of current-state lead time)
- **Red** = Non-Value-Added (NVA) / waste: ~5.5 hrs total (~96% of current-state lead time)

Current-state breakdown: 2 hr wait → 10 min review → 5 min triage → 2 min routing → 1.5 hr wait + rework → 2 hr dept wait + rework/escalation

Future-state breakdown: AI classifies < 30 sec → Value-Added ~12 min → Dept processes & responds ~13 min

### Methodology Notes

- VSM follows standard lean notation: process boxes, data boxes (C/T, misrouting rate, FTEs), push arrows, inventory triangles, supplier/customer icons
- Current State and Future State mapped on a single canvas for direct comparison
- KPI summary boxes embedded in each state for executive readability
- Exported as PDF (grid off) and PNG for GitHub display

### Related Portfolio Item

See also: **AI Workflow ROI Analysis** (`github.com/robertciceroson/AI-workflow-ROI-analysis`) — the CBA/ROI Excel model that quantifies the same engagement's financial case, built to complement this VSM.
