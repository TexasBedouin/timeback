# Memory: what Timeback remembers, and where

Timeback can't remember anything on its own. A skill reads the conversation it's in and nothing else. So memory is a small store the coach reads at the start of a session and updates as it goes.

## Where it lives

Two layers, simplest first:

1. **The AI tool's built-in memory**, if it's on (Claude memory, for example). Best, because it carries across chats with zero setup.
2. **A notes file in the project** as the backup, named `timeback-memory.md`. The coach reads it first and appends to it. Use this when built-in memory isn't available.

Keep it small. This is field notes, not a database. Everything stays in the user's own account. Nothing leaves.

## What it holds

### 1. Learner profile
A few lines about how this person learns and works.
- Preferred way to learn: checklist, or do-it-together
- Their role or kind of work, if known
- Anything they told you about how they like to be coached

### 2. Field log (the tally)
One dated line per session of what they worked on. This is how time-sinks surface, cheaply, over time.
```
2026-06-08  drafted 3 cold emails, formatted a weekly report
2026-06-09  cold emails again, researched two companies
2026-06-10  cold emails (struggled, lots of rewrites)
```
After a week, the pattern is obvious without ever re-reading old chats.

### 3. Playbook archive
The named recipes the person can re-run. Each one: a name, the numbered steps, and the exact prompts to paste. See [PLAYBOOK-ENGINE.md](PLAYBOOK-ENGINE.md) for the format. This archive is the real asset. It grows with the person.

### 4. Adoption log
For each playbook, whether it actually stuck.
```
cold-email-playbook   taught 2026-06-10   adopted? yes (used 2026-06-12)
report-formatting     taught 2026-06-15   reverted   why: drill felt too generic
```
"Reverted" is the signal that the teaching failed. The why-bucket (presentation / drill / fit) tells you what to fix next time.

## How the coach uses it

- **Start of session:** read the profile and recent field log so you know who you're with and what's been eating their time.
- **During:** append one field-log line. Note any friction.
- **After a drill:** save the new playbook to the archive, add an adoption-log entry.
- **Later:** when a known task reappears, check the adoption log. Did they use the playbook? Update it. That check is the whole feedback loop.
