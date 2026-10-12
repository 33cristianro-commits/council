---
description: Convene the council of four (believer, skeptic, investor, judge) to debate an idea and deliver a verdict.
argument-hint: <the idea to debate>
---

Convene the council on this idea:

$ARGUMENTS

If no idea was given above, ask for one and stop.

Run the council in this order, one at a time, using the Agent tool with each member's subagent type:

1. **believer**: give it the idea and ask for the strongest honest case for it.
2. **skeptic**: give it the idea and the Believer's case, and ask it to attack the idea and rebut the Believer's specific claims.
3. **investor**: give it the idea plus the Believer's and Skeptic's arguments, and ask it to weigh return, risk and timing: whether now is the right moment, how long until a meaningful milestone, and what waiting would cost or gain.
4. **judge**: give it the idea and all three arguments, and ask for a verdict. Its answer must include:
   - the verdict (GO / GO WITH CONDITIONS / PIVOT / NO GO),
   - a concrete **Recommendation**: what to do next,
   - the **Main unresolved question**: the single open question that most affects whether the verdict holds, and how to answer it.

Each member must receive the complete prior arguments, word for word, not summaries. Do not add your own opinion to the debate.

When the Judge returns, present to the user:
- The Judge's verdict in full, including the recommendation and the main unresolved question.
- Below it, each of the other three arguments, in order, under its own heading.
