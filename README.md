# chronicle.md

> **Note:** This project is a work in progress and is under active refinement.

![Static Badge](https://img.shields.io/badge/mission-add%20narrative%20to%20your%20codebase%20for%20better%20human%20and%20ai%20context-brightgreen)
<br />
![GitHub top language](https://img.shields.io/github/languages/top/minimal-mind/chronicl)
![GitHub last commit](https://img.shields.io/github/last-commit/minimal-mind/chronicl)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

`chronicl.md` is a development practice to add narrative to your codebase for better human and ai context. 

## Problem

Much of the real decision-making for a project happens outside the IDE—in meetings, conversations and instant messages—so design choices are debated, revised or overturned without the whole team being aware. AI tools are only as good as the context fed to them in each short-lived session, and they still struggle with memory from one interaction to the next. Chronicle.md solves this by providing a single, evolving narrative: every decision—no matter how long ago—is logged and immediately available for AI (and any new team member) to consume.

What about when your in the IDE?

When you’re deep in the IDE, you’re making hundreds of tiny but crucial choices—how to name that function, whether to extract a helper method, which library to lean on, or how to structure that loop for readability and performance. Those in-the-moment decisions often happen so naturally that they never make it into meeting notes or commit messages, and unless every nuance is explicitly communicated, your colleagues—and more importantly your AI assistant—are operating in the dark.

An AI coding assistant that hasn’t seen your real-time reasoning can suggest patterns that clash with your design intent, recommend libraries you’ve deliberately avoided, or fail to respect performance trade-offs you’ve already addressed. Worse still, each new session forces you to rehearse the same explanations over and over. Chronicle.md solves this by giving you a live “developer diary” at the root of your project. Every time you tweak, refactor or experiment, you add a brief note of what you did and why. That running log means your AI agent—and anyone joining later—can instantly grasp the context of every IDE-level decision, so suggestions stay on-point and your code evolves coherently.

## Solution

Chronicl introduces a single, root-level Markdown file—`chronicl.md`—that captures the ongoing narrative of your codebase. It lives alongside your code, evolves with each branch and gives both humans and AI the context they need to understand project goals, decisions and discoveries.

## Contents of `chronicl.md`

- **Project Overview**  
  High-level goals, target audience and scope.

- **Tech Stack and Contributors**  
  Key libraries, services and team members.

- **Design Decisions**  
  Architectural choices, trade-offs and the reasons behind them.

- **Ad-hoc Notes**  
  Insights from meetings, peer discussions and coding sessions.

- **Journal Entries**  
  Dated log of pivots, findings, risks and next steps.

## How to Use

1. **Initial setup**  
   Copy `template/chronicl.md` into your project root.

2. **Branch-level updates**  
   Whenever you start or finish work on a feature or bug fix, append concise bullet points under the relevant section.

3. **Review before merge**  
   Ensure entries are clear and up to date before merging back into the main branch.

4. **Ongoing maintenance**  
   Treat `chronicl.md` as a living document—keep it accurate as your project evolves.
 
