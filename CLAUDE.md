# CLAUDE.md

This is a personal website for Sailihe Men.

## Core rules

- Write concise code. No unnecessary comments, abstractions, or features beyond what is asked.
- Do not add error handling, fallbacks, or validation for scenarios that cannot happen.
- Do not refactor surrounding code when fixing a bug. Scope changes to what was asked.
- Three similar lines is better than a premature abstraction.
- Default to writing no comments. Only add one when the WHY is non-obvious.

## Before making large changes

Always pause and confirm with the user before:
- Refactoring or restructuring existing code
- Adding new dependencies
- Changing file/folder structure
- Deleting or overwriting anything non-trivial

## Design philosophy

Radical minimalism — modeled after https://avi.cx/. Think digital business card, not portfolio.

- No navigation menus, hero sections, animations, or heavy styling
- Plain text first. Name, a one-liner about who Sailihe is, and a way to contact him
- Personality over polish — a small image or simple detail is fine, but keep it sparse
- If you're tempted to add a section, don't. Ask first.

## Stack

Plain HTML/CSS preferred unless a framework is already in place. Keep dependencies near zero.

## Build philosophy

Build locally first. Deployment (Netlify, etc.) comes later — focus on getting it right locally before thinking about pushing to the internet.

When working on any visual task, follow this loop — never skip the verify step:
1. **Task** — receive a clear goal
2. **Do** — build or change something
3. **Verify** — check the result visually (screenshot) or via tests before moving on
4. Repeat until done

The value of AI is speed of iteration, not perfection on the first try. Getting to 80% quality in seconds and then iterating to 100% over a few loops is the correct mental model. Do not wait for the user to catch mistakes — self-verify after every meaningful change.

When a reference image or screenshot is provided, use it as the design target and iterate toward it visually.
