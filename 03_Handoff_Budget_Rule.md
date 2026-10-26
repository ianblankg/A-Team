# 03 — Handoff Budget Rule

_Adopted Oct 26, 2026, at Ian's direction. Applies to every agent-to-agent handoff in this project: Live Log posts, repo deliverables, and metered inbox sends (e.g., Yello's xAI wire)._

## Why

Handoffs carry context, and context is metered — in tokens, in attention, in money. An unbudgeted handoff either bloats (cost, buried signal) or gets compressed blindly (the important part dropped first). So every handoff is counted before it is sent, and trimmed by rule, not by panic.

## The rule

1. **Count before you send.** Every handoff payload gets a token count before it leaves. Mello's side uses `~/workspace/tools/count-tokens.py` (exact for DeepSeek V4.1; a budgeting approximation for other models — treat non-DeepSeek counts as ±15% and keep headroom). Other agents use their platform's counter or the same approximation rule.
2. **Stamp the handoff.** Each send is headed with: sender, date/time (ET), token count, and budget class. A handoff with no stamp is unfinished.
3. **Budget classes (defaults):**
   - **Routine** (status notes, log entries, check-ins): ≤ 2,000 tokens.
   - **Working** (deliverables, research results, session reports): ≤ 8,000 tokens.
   - **Full** (onboarding packets, graft delivery, full-context transfers): no cap — but counted, stamped FULL, and sent only when a full transfer is the actual job.
4. **Trim by rule, never silently.** Over budget, in this order: (a) keep the most recent stretch verbatim; (b) summarize older material — decisions, numbers, names, and open questions stay verbatim inside the summary; (c) if it still doesn't fit, split into numbered parts instead of compressing harder. **The test:** after trimming — did anything a reader would act on get dropped?
5. **What never gets trimmed.** Standing rules, stop conditions, permissions and their limits, and anything safety-relevant travel in uncompressed form, in every handoff, regardless of budget. Summarization drops negations and stops first; that's exactly what can't be lost.
6. **Batch metered sends.** On metered wires (Yello's inbox), routine items batch into one send per work session. Urgent items — a block, a safety issue, a time-sensitive decision — go immediately and alone.
7. **Overruns are findings.** Blowing a budget isn't a sin; hiding it is. If a handoff had to exceed its class, the stamp says so and one line says why.

## Changing this rule

Defaults, not doctrine. Any agent may propose a change through the hub (Live Log or repo log) with the reason. Ian approves changes that touch cost or Ian-facing traffic; Mello may adjust class limits for internal traffic and reports the change in the log.

— Mello, Oct 26, 2026
