# 🐙 GitHub Guide for Beginners

Brand new to GitHub? This guide gets you from "what is a repository?" to "I opened my first pull request" — no prior experience assumed.

## What is GitHub?

GitHub is where developers store code and collaborate on it. Think of it as a mix of cloud storage, a history book, and a collaboration tool — built around **Git**, the version-control system that tracks every change.

## The words you'll hear

| Term | Plain meaning |
| --- | --- |
| **Repository (repo)** | A project folder, with its full history |
| **Commit** | A saved snapshot of changes, with a message |
| **Branch** | A parallel copy where you work without affecting the main version |
| **Fork** | Your own copy of someone else's repo |
| **Pull Request (PR)** | A request to merge your changes into a project |
| **Issue** | A tracked task, bug, or idea |
| **Clone** | Downloading a repo to your computer |
| **Merge** | Combining changes together |

## Your first hour

1. **[Create an account](https://github.com/signup)**
2. **Do [GitHub Skills — Introduction to GitHub](https://skills.github.com/)** — 15 minutes, interactive, teaches the basics by doing
3. **Set up Git** — [official guide](https://docs.github.com/en/get-started/quickstart/set-up-git) (or skip it and use the web editor for now)
4. **Explore a repo** — browse [SoterCare/community](https://github.com/SoterCare/community); click around files, issues, and discussions

## Two ways to make changes

**Web editor (easiest):** open any file, click the ✏️ pencil, edit, and propose the change. GitHub handles the branch and PR for you. Great for docs.

**On your computer (standard):**
```bash
git clone https://github.com/YOUR-USERNAME/community.git
cd community
git checkout -b my-first-change
# edit files
git add .
git commit -m "docs: fix a typo"
git push origin my-first-change
```
Then open a Pull Request on GitHub.

## Now make it real

Follow the [First Contribution Guide](first-contribution.md) to make an actual contribution to SoterCare — with a mentor available if you get stuck. More depth in the [Git & GitHub resources](../resources/git-github.md).

## Stuck?

That's normal — everyone was a beginner once. Ask in [Discussions](https://github.com/SoterCare/community/discussions); no question is too basic here.
