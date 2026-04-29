# PlayPENN
A repository for testing and playing with code
Testing the branchng capabilities

## CIO digital twin

A Claude Code subagent that role-plays Robb P., Group CIO at Omnia.

- **Agent definition:** [`.claude/agents/cio-twin.md`](.claude/agents/cio-twin.md)
- **Grounding profile:** [`cio-twin-profile.md`](cio-twin-profile.md) — fill this in to make the twin's voice and context yours.

### Use it
From inside Claude Code in this repo, ask the main agent to delegate, e.g.:

> Ask the cio-twin to review this proposal and tell me whether it's worth funding.

Or invoke directly with the Agent tool using `subagent_type: cio-twin`.

The twin will ask for missing context rather than invent Omnia-specific facts. The more you populate `cio-twin-profile.md` (especially sections 5, 7, and 10), the closer the voice gets to yours.
