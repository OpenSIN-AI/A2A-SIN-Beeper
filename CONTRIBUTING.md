# Contributing to A2A-SIN-Beeper

## Scope first

Before changing code or docs, verify the change genuinely belongs to the **Beeper** surface.

Put the change here when it affects:
- Beeper integration, routing, or coordination workflows
- message evidence, recovery, sync, or delivery handling
- Beeper contracts tied to automation

Do **not** put the change here when it belongs to:
- other messaging surfaces or generic app automation
- browser/runtime infrastructure
- organization SSOT docs or architecture ownership

## Workflow

1. Branch from the latest `main`.
2. Make the smallest repo-scoped change possible.
3. Run validation command(s) relevant to the touched surface.
4. Include exact validation commands and evidence in the PR.

## Boundary checklist

- Does this change stay within Beeper ownership?
- Does another repo already own the adjacent messaging surface?
- Does this PR avoid redefining shared docs, runtime, or platform canon?

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.
