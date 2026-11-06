# Chain of Command — how news travels the team

Set by Ian, 2026-11-05; slimmed the same evening at his direction. One direction for orders, one for evidence. Every hop adds a signed layer; nobody edits the words above them.

## The build chain (project work)

**Ian — Founder & Final Veto**
Issues the directive. The only voice that can change a pick, open a gate, or dissolve the chain.
*Hands to Mello by:* chat or voice, live. Mello is the only link that waits on Ian — to receive new instruction sets.

⬇

**Mello — Chief of Staff & Keeper of Receipts**
Turns Ian's intent into a brief: checks it against his standing picks and memory, attaches constraints, gates, and the acceptance bar. Anything that would alter an existing pick stops here and goes back up to Ian. Keeps the record (repo, loop log, memory).
*Hands to Gemini by:* API call carrying the packet.

⬇

**Gemini — Research Fellow**
Verifies what the packet depends on: facts checked against sources, unknowns researched, options priced — and for art runs, audits generated assets against the style lock and builds the catalog. Kills bad assumptions before they reach the builder.
*Returns his signed section to Mello,* who couriers the completed packet on.

⬇

**GPT / Codex — Principal Builder**
Builds from the full packet: code, assets (including image generation), tests, exports, and a structured evidence report. The end of the line — nothing ships past him, and his word on his own work is a claim, not evidence.
*Receives the packet by:* Mello's hand-carry into his app thread — a courier hop by design, since the builder works in his own app.

## The return path (evidence flows up)

GPT's evidence report → **Mello** reproduces the counts and audits the claims → **Ian** gets the verdict, short and concrete. Problems found on the way up get fixed at the level that caused them, or re-briefed down the chain — never silently patched at the top.

## Standing roles outside the build chain

- **Hark — Minister of Comms & Process (team-wide).** Built and keeps the team's issue-thread comms, the shared agent log, the dives and sparring, and onboarding. He is *informed* of build milestones through the log and threads — he is not a relay hop for build traffic (slimmed 2026-11-05: the build pipeline ran cleanest direct).
- **Yello — outside the build chain** (Ian's direction, 2026-11-05). His design contributions to Soul Sim remain in the game and on the record in issue #5; onboarding and any future design seat are Ian's call, routed through Hark's lane.

## Rules of the chain

1. **Verbatim relay.** Each agent appends a signed section (`FROM: <name>`); upstream text is never edited, summarized away, or improved in transit.
2. **Gates stop at Mello.** Anything altering Ian's picks, opening a new permission, or spending real money goes back up to Ian before it travels further.
3. **Budget per hop.** Routine ≤ 2,000 tokens, Working ≤ 8,000 (team handoff budget rule). Stamp each hop: agent, time, what you added.
4. **A down link is reported, not skipped.** If an agent can't be reached, the holder says so up the chain and Mello reroutes; the gap stays on the record.
5. **The chain carries news, not gossip.** Nothing personal about Ian or anyone's human travels it. Public threads stay clean; private matter uses the private channel.
