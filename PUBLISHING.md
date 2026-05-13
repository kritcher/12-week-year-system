# Publishing

Local repo path:

```bash
/Users/aiserver/Code/github.com/kritcher/12-week-year-system
```

The intended GitHub repo:

```text
kritcher/12-week-year-system
```

## Publish With GitHub CLI

The local machine must have a valid `gh` login first.

```bash
gh auth login -h github.com
cd /Users/aiserver/Code/github.com/kritcher/12-week-year-system
gh repo create kritcher/12-week-year-system --public --source=. --remote=origin --push
```

Use `--private` instead of `--public` if the repo should be reviewed before sharing.

## If The Repo Already Exists

```bash
cd /Users/aiserver/Code/github.com/kritcher/12-week-year-system
git remote add origin git@github.com:kritcher/12-week-year-system.git
git push -u origin main
```

## Current Auth Note

At creation time, `gh auth status` on this machine reported an invalid keyring token for the active `kritcher` GitHub account. Re-authentication is required before publishing from this machine.
