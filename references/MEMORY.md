# Memory: what Timeback remembers, and where

Timeback can't remember anything on its own. A skill reads the conversation it's in and nothing else. So memory is a small store the coach reads at the start of a session and updates as it goes.

## Where it lives

Two layers, simplest first:

1. **The AI tool's built-in memory**, if it's on (Claude memory, for example). Best, because it carries across chats with zero setup.
2. **A notes file in the project** as the backup, named `timeback-memory.md`. The coach reads it first and appends to it. Use this when built-in memory isn't available.

Keep it small. This is field notes, not a database. Everything stays in the user's own account. Nothing leaves.

## What it holds

### 1. Mission (the WHY)
The person's bigger goal, the reason saving time matters at all. One or two lines.
```
Mission: get my evenings back. I want to stop doing outreach after dinner.
```
Everything else ladders up to this. When you pick what to coach, prefer what moves the mission most. Borrowed from Matt Pocock's teach skill.

### 2. Learner profile
A few lines about how this person learns and works.
- Preferred way to learn: checklist, or do-it-together
- Their role or kind of work, if known
- Anything they told you about how they like to be coached

### 3. Field log (the tally)
One dated line per session of what they worked on. This is how time-sinks surface, cheaply, over time.
```
mon  drafted 3 cold emails, formatted a weekly report
tue  cold emails again, researched two companies
wed  cold emails (struggled, lots of rewrites)
```
After a week, the pattern is obvious without ever re-reading old chats.

### 4. Playbook archive
The named recipes the person can re-run. Each one: a name, the numbered steps, and the exact prompts to paste. See [PLAYBOOK-ENGINE.md](PLAYBOOK-ENGINE.md) for the format. This archive is the real asset. It grows with the person.

### 5. Mastery record
For each playbook or skill, how far it has actually landed. More than a yes/no: it's the floor that tells you what NOT to re-teach.
```
cold-email     status: mastered    evidence: used unprompted on a real lead, twice
report-format  status: reverted    why: drill felt too generic
queue-triage   status: learning    last drill mon, not used for real yet
```
- **Mastered** (used unprompted on real work) is a floor. Never re-drill it. Build past it, toward the mission.
- **Reverted** means the teaching failed. The why-bucket (presentation / drill / fit) tells you what to fix.
- Use this to aim the next drill just past their current level, not at something they already own. The mastery-floor and just-beyond ideas are borrowed from Matt Pocock's teach skill (learning records and the zone of proximal development).

## How the coach uses it

- **Start of session:** read the mission, the profile, and the recent field log so you know who you're with, what they're aiming at, and what's been eating their time.
- **During:** append one field-log line. Note any friction.
- **After a drill:** save the new playbook to the archive, add a mastery-record entry (start it at "learning").
- **Later:** when a known task reappears, check the mastery record. Did they use the playbook? Update its status. If they used it unprompted, mark it mastered and stop drilling it. That check is the whole feedback loop, and it's what tells you the next thing to teach.
