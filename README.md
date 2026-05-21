# Code Health Risk Report
### by Dev4x — dev4x.in

> Tired of explaining codebase problems to leadership every quarter? Run this. Forward the report. Let the tool have the conversation for you.

## What It Does

Code Health Risk Report analyses your entire codebase and produces a structured, jargon-free risk report written for leadership — not engineers. It identifies what is slowing your team down, what is creating hidden risk, and what will become expensive if left unaddressed. The output is a professional document a Tech Lead can share upward with confidence, and a CTO can act on the same day.

## Who This Is For

**Primary user — Tech Lead / Senior Developer**
You already know what the problems are. The hard part is communicating them to people who do not read code. This tool translates what you know into language that gets budget approved, priorities shifted, and decisions made — without you writing a single word of the report yourself.

**Report audience — Engineering Manager / CTO**
The output gives leadership a clear picture of where the codebase is now, what the business consequences of inaction are, and what decisions they need to make. No technical jargon. No scores to interpret. Just clear findings and a recommended order of action.

## Prerequisites

- [Claude Code](https://claude.ai/code) installed
- A Claude subscription (Pro, Max, or API key)
- Your project open in a terminal

## How To Use

### Option 1 — Global install (recommended)
One command. Works in every project you open, forever.

```bash
mkdir -p ~/.claude/commands
curl -o ~/.claude/commands/code-health-risk.md \
  https://raw.githubusercontent.com/dev4x-ai/code-health-risk-report/main/command.md
```

Then in any project:
1. Open Claude Code: `claude`
2. Type: `/code-health-risk`
3. Report ready in 60 seconds

### Option 2 — Team install
One person sets it up. Every developer on the team gets it automatically.

```bash
mkdir -p .claude/commands
curl -o .claude/commands/code-health-risk.md \
  https://raw.githubusercontent.com/dev4x-ai/code-health-risk-report/main/command.md
git add .claude/commands/code-health-risk.md
git commit -m "Add Dev4x code health risk command"
```

Then anyone on the team:
1. Opens Claude Code: `claude`
2. Types: `/code-health-risk`
3. Report ready in 60 seconds

### Option 3 — No setup
1. Open [command.md](command.md) → click **Raw** → copy everything
2. Open Claude Code in your project: `claude`
3. Paste and run
4. Report ready in 60 seconds

## What You Get

- Plain English summary of overall codebase health
- Critical risks that need immediate attention — framed as business consequences
- Medium-priority findings to address this quarter
- Early warning signals to monitor before they become urgent
- A clear, prioritised action order written for decision-makers
- Honest effort estimates in days and weeks — not story points

## Example Output

See [example-output.md](example-output.md) for a real sample.

## Privacy

Your codebase never leaves your machine.
Analysis happens between Claude Code and Anthropic's API only.
Nothing is sent to Dev4x servers.

[anthropic.com/privacy](https://anthropic.com/privacy)

## Part of the Full Stack Claude Kit

20 free tools for Tech Leads and Senior Developers. See them all:
[github.com/dev4x-ai/fullstack-claude-kit](https://github.com/dev4x-ai/fullstack-claude-kit)

## Talk to Dev4x

If this report surfaces something you want to discuss — we offer a free 30 minute consultation.

[hello.dev4x@gmail.com](mailto:hello.dev4x@gmail.com) | [dev4x.in](https://dev4x.in)

---
Built by Dev4x | Powered by Claude AI
If this helped — star it ⭐
[github.com/dev4x-ai/code-health-risk-report](https://github.com/dev4x-ai/code-health-risk-report)
