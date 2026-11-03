# AGENTS.md

Guidance for automated agents (dsh-superagent) working in this repository.

## Scope

- This is a sandbox repository for exercising the agent workflow. Keep every change small and reviewable.
- Never push to `master` directly. Work on an `agent/*` branch and open a pull request; a person merges every pull request.

## What to change

- Change only what the request asks for. Do not refactor, reformat or "improve" unrelated code or files.
- If a request is ambiguous or needs a design decision, stop with one concrete question instead of guessing.

## Validation

- There is no build or test pipeline yet. Before opening a pull request, re-read your full diff and confirm it is minimal, correct and matches the request.
- State honestly in the pull request description what you verified and what you did not.

## Style

- One-line commit messages, imperative mood (e.g. `Add testing note to README`).
- Plain Markdown. No generated files, no binary artifacts, no dependency changes unless explicitly requested.
