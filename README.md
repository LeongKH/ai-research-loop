# AI Research Loop Template

A lightweight framework for running **small AI experiments** with asymmetric upside.  
Built for people who want clarity without overcomplication.

---

## Why
Most AI experiments fail because they’re too big, too vague, or never written down.  
This template forces you to define:
- Hypothesis (what you believe will happen)  
- Setup (tools/models you’ll use)  
- Steps (≤3)  
- Result (pass/fail + notes)  
- Next (iterate / kill / scale)

It works like a **barbell strategy**: tiny capped downside, open-ended upside.

---

## How to Use
1. Clone/download this repo.  
2. Copy the `ai_experiment_template.md` file.  
3. Fill it in before you start any new AI test.  
4. Keep each experiment to ≤60 minutes or ≤$20 cost.  
5. Track results over time → patterns emerge.

---

## Example
```markdown
# AI Experiment
Hypothesis: If I use GPT-4 to summarize call transcripts, I’ll save 30 min per meeting.
Setup: GPT-4 API + Zoom transcript
Steps:
1. Export transcript
2. Prompt GPT-4 with "3 key decisions, 2 risks"
3. Paste result into meeting notes
Result: Saved 25 min, but missed 1 risk.
Next: Refine prompt to include "financial risk".