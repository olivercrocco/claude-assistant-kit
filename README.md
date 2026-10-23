# Claude Code as Your Assistant: a guided setup and starter kit

A guide and a set of templates for academics, managers, and leaders who want to use Claude Code as an executive assistant and project manager: keeping the task list, drafting correspondence, preparing documents, tracking projects, and keeping files in order, inside their own folders and under rules they write.

Live page, with a walkthrough and a builder that writes your CLAUDE.md rules file: https://olivercrocco.com/claude-assistant

It comes from a setup I have run daily for about six months across research, teaching, editorial work, and program administration, and first wrote up for a friend who wanted to work the same way. None of it requires programming.

Two things before you start. Your organization's rules on AI tools govern everything here; find the policy first. And give Claude only what you have permission to share and would be comfortable seeing leaked. What other people entrusted to you (student records, participants' data, personnel files, client records, manuscripts under review) stays out unless you have that permission.

## What is here

- `GUIDE.md` and `GUIDE.docx`: the full guide in ten sections: what Claude Code is, what a day looks like, the first hour of setup, what goes where (CLAUDE.md, memory, skills, scheduled tasks), the hard rules to copy on day one, habits that make it work, a first-week plan, prompts to try, the templates, and what to do when things go wrong.
- `Templates/global-CLAUDE.md`: your standing instructions for every session. Fill in the brackets and save it as `~/.claude/CLAUDE.md`, or generate a finished one on the live page.
- `Templates/work-folder-CLAUDE.md`: a map of your work folder for Claude, with a filing procedure. Save it as `CLAUDE.md` at the top of the folder you open Claude in.
- `Templates/Projects-Master.xlsx`: a task workbook with a Task Queue in four bands (NOW, NEXT, WAITING, SOMEDAY), an Upcoming sheet with a live countdown, a Projects sheet, and the rules on a README sheet.
- `Templates/weekly-review/SKILL.md`: a complete Friday review skill. Save it as `~/.claude/skills/weekly-review/SKILL.md`.
- `Templates/morning-brief.md`: the prompt for a scheduled daily brief, with setup notes at the top.
- `Templates/memory-examples.md`: what good memory files look like, one of each kind, so you know what to ask for and what to prune.
- `Templates/voice-profile.md`: optional. A structure for describing how you write, with an interview prompt to fill it.

## The hard rules

The global template carries six rules that hold in every folder. Each one exists because the mistake it prevents is costly or cannot be undone.

1. Email is drafted and never sent or deleted. Claude writes the draft to a file; you send it.
2. Files are never deleted or overwritten. Redundant files go to a quarantine folder that only you empty.
3. Browser forms are filled and never submitted. Claude stops before the final button.
4. No passwords, payments, or account changes.
5. Confidential material is not opened unless you ask, naming the files. Write your employer's policy into the rule.
6. Nothing is made up. Read the full source, flag uncertainty, check names and figures before anything goes out under your name.

CLAUDE.md is strong guidance, and in daily use these rules hold well, but it is not a lock. The permission mode is the lock. For the actions that matter most, keep Claude asking before it acts.

## Where the files go

| Layer | What it holds | Where it lives |
|---|---|---|
| Global CLAUDE.md | Who you are, how you work, hard rules | `~/.claude/CLAUDE.md` |
| Folder CLAUDE.md | How a folder is organized and its conventions | `CLAUDE.md` at the top of the folder |
| Memory | Corrections, preferences, project status, pointers | `~/.claude/projects/<folder>/memory/` (Claude writes these) |
| Skills | Step-by-step procedures for repeated jobs | `~/.claude/skills/<name>/SKILL.md` |
| Scheduled tasks | Prompts that run on a timer | Set up from the Claude desktop app |

`~/.claude` is a hidden folder inside your home folder. In Finder, press Command, Shift, and G together and type `~/.claude`.

## Accuracy

The feature details (CLAUDE.md loading, memory, skills, permission modes, connectors, scheduled tasks) were checked against the Claude Code documentation at code.claude.com on 23 October 2026. The product changes often; if a menu or a mode has moved, the documentation is the place to look.

## License and citation

Released under a Creative Commons Attribution 4.0 International (CC BY 4.0) license. Use it, adapt it, and share it, including in your own teaching and workshops, with credit.

APA 7:

Crocco, O. S. (2026). *Claude Code as your assistant: A guided setup and starter kit* (Version 1.0) [Guide and templates]. GitHub. https://github.com/olivercrocco/claude-assistant-kit
