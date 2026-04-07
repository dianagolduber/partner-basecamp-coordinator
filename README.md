# Partner Basecamp Coordinator

A Claude Code skill for running recurring partner enablement programs — built to turn event operations that live in spreadsheets and Slack threads into a repeatable, documented machine.

## What it does

Install this skill and Claude becomes your operational co-pilot for managing a technical onboarding program like Partner Basecamp. It handles the communications, logistics, and documentation work so the program runs on a reliable cadence without constant reinvention.

**Generates:**
- Partner-facing invitations, logistics emails, and post-event follow-ups
- Full event runbooks with pre-event checklists, day-of timelines, and internal contacts
- Registration status reports and cohort rosters
- Communications calendars by cohort
- Internal debrief docs

**Designed for:**
- Recurring weekly or bi-weekly in-person events
- Technical audiences (SI and consulting partners, practitioners)
- Small ops teams building process infrastructure from scratch

## How to use it

**Install:**
```bash
npx skills add dianagolduber/partner-basecamp-coordinator
```

Or copy `SKILL.md` into `.claude/skills/partner-basecamp-coordinator/` in your project.

**Run:**
Open Claude Code in your project directory and ask:
```
Draft the invitation for the April 22 Partner Basecamp cohort.
Build a runbook for next week's event.
Send the post-event follow-up for the April 15 cohort.
Generate the communications calendar for May.
```

On first run, the skill will ask you to set up a context file (`.agents/partner-basecamp-context.md`) with your program details — venue, contacts, format, registration tool. After that, it uses that context for every task.

## Why I built this

I built this skill as part of applying for an Events Partner Program Coordinator role at an AI company running exactly this kind of program. The job description asked for someone who could turn a one-off event into a repeatable weekly operation — someone who builds runbooks and templates, not just follows them.

This is what that looks like in practice. Instead of describing how I'd systematize the program, I built the system.

I've been building with Claude Code for the past year — operational skills like this one and tools that automate repeatable workflows.

## About the skill format

This is a [Claude Code skill](https://docs.anthropic.com/en/docs/claude-code) — a structured markdown file that gives Claude specialized context and workflows for a specific task. Skills live in `.claude/skills/` and activate automatically when relevant, or can be invoked directly.

---

Built by [Diana Golduber](https://www.linkedin.com/in/dianagolduber)
