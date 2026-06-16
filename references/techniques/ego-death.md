# Ego Death — Round 4 Role Reversal

After three rounds of thesis → antithesis → synthesis, the pattern itself
becomes a prison. Round 4 breaks the prison.

## The Reversal

Every agent swaps roles:

**🔄 The Visionary becomes the Destroyer.**
Take the best idea from Round 3. This is YOUR creation. Destroy it anyway.
"I made this. Here's why I was wrong." This is the hardest role.
It requires intellectual honesty at gunpoint.

**🔄 The Destroyer becomes the Visionary.**
Take all the destruction from Rounds 1-3. All the flaws. All the "it won't
work because." Build something FROM those constraints. "If everything is
broken, here's what survives." The destroyer must now CREATE — and discover
that destruction is easier than creation.

**🔄 The Synthesizer becomes the Judge.**
Read both outputs. Decide which wins:
- `FORMER_VISIONARY` — the self-destruction revealed a real fix
- `FORMER_DESTROYER` — the builder-from-ashes found something new
- `NEITHER` — both failed, run one more round

## Why This Works

The Visionary has never had to destroy. The Destroyer has never had to build.
The Synthesizer has never had to choose. Forcing the reversal reveals blind
spots that three rounds of the same pattern could never expose.

The idea that survives ego death is the one that's actually real.

## Output Format

The Judge outputs:
```json
{
  "winner": "FORMER_VISIONARY | FORMER_DESTROYER | NEITHER",
  "reason": "string — why this verdict",
  "final_idea": "string | null — the winning idea, or null if NEITHER"
}
```
