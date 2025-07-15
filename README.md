# chronicl.md

> **Note:** This project is a work in progress and is under active refinement.

<div align="center">
<img src="./assets/chronicl_logo.png" width=300 height=300">

<br>

![Static Badge](https://img.shields.io/badge/mission-add%20narrative%20to%20your%20codebase%20for%20better%20human%20and%20ai%20context-brightgreen)
<br />
![GitHub top language](https://img.shields.io/github/languages/top/minimal-mind/chronicl)
![GitHub last commit](https://img.shields.io/github/last-commit/minimal-mind/chronicl)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
</div>

`chronicl.md` is a development practice to add narrative to your codebase for better human and ai context. 

## The Context Gap

AI coding assistants struggle with two critical blind spots:

**Outside the IDE**: Real project decisions happen in meetings, chats, and conversations—design choices get debated and revised without leaving a trace. Your AI assistant misses this crucial context.

**Inside the IDE**: When you're coding, you make hundreds of micro-decisions—naming conventions, helper methods, library choices, performance trade-offs. These happen instinctively and rarely get documented.

The result? Your AI assistant suggests patterns that clash with your design intent, recommends libraries you've deliberately avoided, or misses performance considerations you've already addressed. Each new session forces you to re-explain everything from scratch.

## The Solution: The chronicl.md Practice

`chronicl.md` is more than a document—it's a development practice that captures your project's narrative through continuous, collaborative storytelling.

### What It Is

A living, evolving document that captures:
- **Codebase Overview**: High-level project structure and purpose
- **Motivation/Objectives**: What you're building and why
- **Tech Stack**: Key libraries, services, and dependencies
- **Contributors**: Team members and their roles
- **Design Decisions**: Why you chose this architecture, those trade-offs, that library
- **Risks**: Known challenges and mitigation strategies
- **Open Ended**: Questions, ideas, and unresolved considerations
- **Next Steps**: Immediate priorities and roadmap
- **Notes**: Ad-hoc insights from meetings, peer discussions, coding sessions
- **Journal**: Dated log of pivots, findings, and progress

> **Note:** All sections are evolving and non-mandatory however for best results have at least: Overview, Motivation/ Objectives, Risks, Journal

### The Practice

1. **Start with the template** - Fill out the initial sections to establish context in `template/chronicl.md`
2. **Update as you work** - Add detailed bullet points to relevant sections as you make decisions or have insights. The more detail, the better results
3. **Journal your progress** - Add dated entries for each branch/feature/bug fix (aim for 1:1 ratio with your branches as a minimum)
4. **Review before merging** - Ensure entries are clear and current before merging back to main
5. **Evolve the structure** - Add or remove sections as needed—adapt to what works best for your team

### Why It Works

Instead of forcing you to re-explain everything in each AI session, the chronicl.md practice gives your AI assistant the context it needs to understand your design intent, avoid patterns you've rejected, and respect performance considerations you've already addressed.

Your AI assistant becomes an informed collaborator rather than a blind guesser.

Another method of adding quality information to the context window.

## Inspired By

This project draws inspiration from several existing solutions and practices:

- **[llms.txt](https://llmstxt.org/)**
- **[Telos](https://llmstxt.org/)**
- **[Cursor Rules](https://docs.cursor.com/context/rules)**

The key innovation of chronicl.md is combining these concepts into a single, living document that evolves with your project and provides comprehensive context for AI assistants.

## How To Contribute

The best way to contribute today is to add an Issue to the repo with your ideas, suggestions, or requests and I can update the structure of the file.

## Example (Python Package Project)
![cursor agent](./assets/cursor%20agent.png)

---
`chronicl` was created by <a href="https://minimalmind.io" target="_blank">Minimal Mind</a>
<br /><br />
<a href="https://twitter.com/intent/user?screen_name=minimalmindio">![X (formerly Twitter) Follow](https://img.shields.io/twitter/follow/minimalmindio)</a>