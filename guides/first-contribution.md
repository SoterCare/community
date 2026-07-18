# 🌱 Your First Contribution

Never contributed to open source before? Perfect — this guide is for you, and this repository is a safe place to start. Your first contribution can be as small as fixing a typo. Small is good. Small is how everyone starts.

## What you need

- A [GitHub account](https://github.com/signup)
- [Git installed](https://git-scm.com/downloads) (or just use the GitHub web editor — genuinely fine for docs!)
- 30 minutes

## The 7 steps

### 1. Find something to work on

Look for issues labeled [`good first issue`](https://github.com/SoterCare/community/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) in this repo, or [across the whole org](https://github.com/search?q=org%3ASoterCare+label%3A%22good+first+issue%22+state%3Aopen&type=issues). Spotted a typo or broken link on your own? That works too — open an issue first.

### 2. Claim it

Comment on the issue: *"I'd like to work on this!"* A maintainer will assign it to you. This avoids two people doing the same work.

### 3. Fork the repository

Click **Fork** (top right of the repo page). This creates your own copy where you can make changes freely.

### 4. Make your change

**Easy mode (docs):** press `.` on your fork's page to open the web editor, or click the ✏️ pencil icon on any file.

**Standard mode:**

```bash
git clone https://github.com/YOUR-USERNAME/community.git
cd community
git checkout -b fix/my-first-contribution
# make your edits
git add .
git commit -m "docs: fix broken link in FAQ"
git push origin fix/my-first-contribution
```

### 5. Open a Pull Request

GitHub will show a **"Compare & pull request"** button on your fork. Click it, fill in the template, and mention the issue: `Closes #123`.

### 6. Respond to review

A maintainer may request changes. This is normal and happens to everyone at every level — it's collaboration, not criticism. Push new commits to the same branch; the PR updates automatically.

### 7. Celebrate 🎉

Once merged, you're officially an open-source contributor and part of our [Contributor Recognition](../docs/recognition.md). Tell people! Put it on LinkedIn! Then maybe grab a second issue…

## Stuck?

Comment on your issue, open a [Discussion](https://github.com/SoterCare/community/discussions), or ask a [mentor](become-a-mentor.md#getting-a-mentor). No question is too basic — every maintainer here once didn't know what a fork was.

**Next step:** the [Open Source Contribution Guide](open-source-contribution-guide.md) for the fuller picture.
