# Contributing to IntraShip repositories

Interns have **read-only** access to track repositories. All contributions go through **fork + pull request**.

## 1. Fork and clone
1. Open the track repository (for example `ai-assignments`) and click **Fork**. Keep the fork under your personal account.
2. Clone your fork: `git clone https://github.com/<your-username>/<repo>.git`
3. Add the original as `upstream`: `git remote add upstream https://github.com/intraship-2026/<repo>.git`

## 2. Branch
Create one branch per task, named after the Jira ticket:
```
git checkout -b AI-12-assignment-01-resubmission
```

## 3. Commit
- Use the Jira key at the start of every commit message: `AI-12: add architecture diagram`.
- Small, focused commits. No generated binaries, secrets, `.env` files or large datasets.

## 4. Keep your fork up to date
```
git fetch upstream
git rebase upstream/main
```

## 5. Open a pull request
- Base: `intraship-2026/<repo>` → `main`. Compare: your branch.
- Title: `<JIRA-KEY>: <short summary>`.
- Fill in the pull request template checklist.
- Move your Jira ticket to **Submitted** (or **Resubmitted**) and paste the PR link in a comment.

## 6. Review
A mentor reviews, comments or requests changes. Push fixes to the same branch; the PR updates automatically. Do not open a new PR for the same task.

## Rules
- Work only on your own files and folder.
- Never commit credentials, API keys or personal data.
- Follow the Code of Conduct and the responsible-AI guidance in the handbook.
