---
description: Convene the council of four (believer, skeptic, investor, judge) to debate an idea and deliver a verdict.
argument-hint: <the idea to debate>
---

Convene the council on this idea:

$ARGUMENTS

If no idea was given above, ask for one and stop.

Run the council in this order, using the Agent tool with each member's subagent type:

1. **believer**: give it the idea. Save its full output.
2. **skeptic**: give it the idea and the Believer's case, so it can rebut specific claims.
3. **investor**: give it the idea plus both the Believer's and the Skeptic's arguments.
4. **judge**: give it the idea and all three arguments in full, verbatim.

Steps 1–3 must each receive the complete prior outputs, not summaries. Do not add your own opinion to the debate.

When the Judge returns, present to the user:
- The Judge's verdict in full.
- Below it, each of the other three arguments, in order, under its own heading.
