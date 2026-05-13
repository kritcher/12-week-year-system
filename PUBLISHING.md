# Publishing

Local repo path:

```bash
/Users/aiserver/Code/github.com/kritcher/12-week-year-system
```

The intended GitHub repo:

```text
kritcher/12-week-year-system
```

Published URL:

```text
https://github.com/kritcher/12-week-year-system
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

At creation time, the Codex shell inherited proxy/certificate environment variables that caused `gh` TLS validation to fail. The repo was created by running `gh` with those proxy/cert variables unset, then pushed over HTTPS using the GitHub CLI credential helper because the local SSH key was not authorized for GitHub.

For this repo, `origin` currently uses:

```text
https://github.com/kritcher/12-week-year-system.git
```
