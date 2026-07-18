# ❤️ Open Source Contribution Guide

The fuller picture of contributing to open source — in SoterCare and beyond. If you haven't made your first contribution yet, start with the [First Contribution Guide](first-contribution.md).

## The contribution lifecycle

```
Find → Discuss → Build → Submit → Review → Merge → Repeat
```

The mistake beginners make is skipping **Discuss**. Comment on the issue before building — it saves you from building the wrong thing, and maintainers from reviewing it.

## Reading a project before contributing

Every serious project tells you how it wants contributions. Check, in order:

1. `README.md` — what the project is and its status
2. `CONTRIBUTING.md` — the workflow, style, and expectations
3. `CODE_OF_CONDUCT.md` — behavior standards
4. Recent merged PRs — the *actual* accepted style, which sometimes drifts from the docs

## Writing good issues

- **Bugs:** what you did, what you expected, what happened instead, environment. A reproducible bug report is a gift.
- **Proposals:** the problem before the solution. "Attendees can't find past slides" beats "add a slides index page".

## Writing good pull requests

- One purpose per PR — reviewers can hold one idea in their head, not five
- A title that summarizes the change: `docs: add Solana workshop report`
- Description says *why*, the diff says *what*
- Link the issue (`Closes #N`)
- Small PRs get reviewed in days; huge PRs get reviewed never

## Commit message convention

We loosely follow [Conventional Commits](https://www.conventionalcommits.org/):

```
docs: fix broken links in workshop guide
feat: add hackathon judging rubric template
fix: correct event date in VisioNEX report
chore: compress oversized photos
```

## Reviewing others (yes, you!)

Reviewing is contributing. Read an open PR, check the links work, and comment kindly and specifically. "This link 404s" is a valuable review. Approving with "tested all the links, works" is too.

## Etiquette that makes maintainers love you

- Patience: maintainers are students with exams too
- Update your PR when asked, or say you're stuck rather than going silent
- If you claim an issue and life happens — no shame, just un-claim it
- Assume good intent in every comment; add a 🙂 when tone could be read two ways

## Beyond SoterCare

The skills transfer directly: [GirlScript Summer of Code](https://gssoc.girlscript.tech/), Hacktoberfest, Google Summer of Code. Our repos are your training ground — see the [resources](../resources/beginner-resources.md) for more.
