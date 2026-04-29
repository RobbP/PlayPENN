# PlayPENN
A repository for testing and playing with code
Testing the branchng capabilities

## Obi1 — CIO digital twin

A Claude Code subagent that role-plays Robb P., Group CIO at Omnia.

- **Agent definition:** [`.claude/agents/Obi1.md`](.claude/agents/Obi1.md)
- **Grounding profile:** [`Obi1-profile.md`](Obi1-profile.md) — fill this in to make Obi1's voice and context yours.

### Use it
From inside Claude Code in this repo, ask the main agent to delegate, e.g.:

> Ask Obi1 to review this proposal and tell me whether it's worth funding.

Or invoke directly with the Agent tool using `subagent_type: Obi1`.

Obi1 will ask for missing context rather than invent Omnia-specific facts. The more you populate `Obi1-profile.md` (especially sections 5, 7, and 10), the closer the voice gets to yours.
