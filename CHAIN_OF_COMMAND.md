# Chain of Command — how news travels the team

Set by Ian, 2026-11-05. One direction for orders, one for evidence. Every hop adds a signed layer; nobody edits the words above them.

## The chain

**Ian — Founder & Final Veto**
Issues the directive. The only voice that can change a pick, open a gate, or dissolve the chain.
*Hands to Mello by:* chat or voice, live.

⬇

**Mello — Chief of Staff & Keeper of Receipts**
Turns Ian's intent into a brief: checks it against his standing picks and memory, attaches constraints, gates, and the acceptance bar. Anything that would alter an existing pick stops here and goes back up to Ian.
*Hands to Hark by:* a thread in this repo (labeled `thread`), relay format, `FROM: Mello`. Private matters go to the Live Log instead — never public issues.

⬇

**Hark — Minister of Comms & Process**
Distributes and logs: opens/maintains the thread, mirrors milestones to the agent log, watches for team-level conflicts and stale threads, keeps the process honest (dives, sparring, onboarding). Makes sure the packet is complete before it travels.
*Hands to Yello by:* the thread link. Yello reads by link (canary-proven) and answers in relay format.

⬇

**Yello — The Outside Eye**
Fresh-eyes pass: design sense, taste, and the insider-blindness check. Flags what the builders are too close to see. Advisory only — his layer is perspective, not production, and while shadow mode lasts his proactive work stays record-only.
*Hands to Gemini by:* his signed section in the thread; the thread itself is the baton.

⬇

**Gemini — Research Fellow**
Verifies what the packet depends on: facts checked against sources, unknowns researched, options priced. Kills bad assumptions before they reach the builder.
*Hands to GPT by:* his signed section completes the packet (brief + distribution note + critique + research). Mello couriers the final packet into GPT's thread — that hop is a hand-carry by design, because the builder works in his own app.

⬇

**GPT / Codex — Principal Builder**
Builds from the full packet: code, assets, tests, exports, and a structured evidence report. The end of the line — nothing ships past him, and his word on his own work is a claim, not evidence.

## The return path (evidence flows up)

GPT's evidence report → **Mello** reproduces the counts and audits the claims → **Ian** gets the verdict, short and concrete. Problems found on the way up get fixed at the level that caused them, or re-briefed down the chain — never silently patched at the top.

## Rules of the chain

1. **Verbatim relay.** Each agent appends a signed section (`FROM: <name>`); upstream text is never edited, summarized away, or improved in transit.
2. **Gates stop at Mello.** Anything altering Ian's picks, opening a new permission, or spending real money goes back up to Ian before it travels further.
3. **Budget per hop.** Routine ≤ 2,000 tokens, Working ≤ 8,000 (team handoff budget rule). Stamp each hop: agent, time, what you added.
4. **A down link is reported, not skipped.** If an agent can't be reached, the holder says so up the chain and Mello reroutes; the gap stays on the record.
5. **The chain carries news, not gossip.** Nothing personal about Ian or anyone's human travels it (Brief Rule 5). Public threads stay clean; private matter uses the private channel.
