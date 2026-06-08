# Timeback

A quiet AI workflow coach for busy people. It helps you get your time back, one workflow at a time.

Timeback doesn't teach with courses or videos (the ones that pile up unwatched). It watches the work you're already doing, notices the chore that eats your hours, and at a calm moment offers a 5-minute hands-on drill. You walk away with a reusable playbook you can run again by name.

## Who it's for

People already using Claude (or Codex/Gemini) for work, but only at the surface, who want to get better without carving out extra time after a long day. If you keep meaning to "learn to use AI properly" and never do, this is for you.

## How it works

- **It learns your time-sinks quietly.** A one-line-per-session tally plus noticing where you struggle. No scanning your chat history, no burning your usage quota.
- **It only speaks up at a calm moment.** Never mid-task. One optional nudge, easy to wave off, no guilt.
- **It teaches by doing.** A tiny drill on safe, fake data, then it hands you the real recipe: numbered steps and the exact prompts to paste.
- **It builds you a library.** Every playbook is saved by name. Over time you get a personal archive of recipes tuned to your work. Just say "run my cold-email playbook" and skip to doing it.
- **It only counts a win if it sticks.** If you go back to the old way, the lesson failed, and it learns to teach you better next time. Clicking "yes" isn't the metric. Actually keeping the habit is.

Ships with one ready-to-run playbook (cold emails) so there's something real on day one. More slot in from there.

## Install (about 2 minutes)

**With Claude (recommended):**
1. Create a Claude Project for your work (or use one you already have).
2. Add the contents of `SKILL.md` to the project's instructions. That's it. It's now automatically on in every chat in that project, with nothing to remember.
3. Let it set up on first use (it asks two quick questions, then gets out of your way).

**With Claude Code or other AI tools:** drop the `timeback/` folder into wherever your tool reads skills from, or paste `SKILL.md` into your system prompt / project instructions.

## Your data stays yours

Everything Timeback remembers (how you like to learn, what eats your time, your saved playbooks) lives in your own account, in your AI tool's memory or a notes file in your project. Nothing leaves. Practice drills always use fake data, never your real work.

## What's inside

- `SKILL.md`: the coach itself.
- `references/MEMORY.md`: what it remembers and where.
- `references/PLAYBOOK-ENGINE.md`: how it turns any time-sink into a saved playbook.
- `references/COLD-EMAIL-PLAYBOOK.md`: the first ready-to-run drill and recipe.

## Status

Early. Built to be dogfooded. Feedback on what actually changed your habits (and what didn't) is the most useful thing you can send.

## License

MIT. Use it, fork it, make it yours.
