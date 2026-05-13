# Shaping Approach

> **For AI assistants:** This directory is your source of truth for how this project is being built. Start by reading this file in full, then read the shaping documents in the order they are numbered below: `idea.md` → `design-priorities.md` → `stack.md` → `the-plan.md`. When working, `the-plan.md` is your operating document; the others are the context that shaped it.

This folder serves to describe the shape of the product to be built.

- [The Idea](idea.md)
- [Design Priorities](design-priorities.md)
- [Stack](stack.md)
- [The Plan](the-plan.md)

## Other Important Directories

- `reports/` — Any time we request a report from an agent, it will write a date-stamped file `YYYY-MM-DD-{specialty}-{title}.md` describing its findings. Filenames are kebab-case (e.g. `2026-04-28-security-auth-flow-review.md`). Any time we create a report, we will add it to  `reports/README.md` with a link to the document.

- `docs/` — Any time we create documentation for this application, it will live here and we will add to `docs/README.md` with a link to the document. `shaping/` and `docs/` are distinct: `shaping/` is how we are going to build it (pre-decision context for planning); `docs/` is how the built application works (post-decision reference for users and operators). Architecture decisions belong in `shaping/`, not `docs/`.
