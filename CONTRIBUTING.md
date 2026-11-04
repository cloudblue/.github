# Contributing to CloudBlue projects

Thank you for taking the time to help. This guide applies to every repository in the [cloudblue](https://github.com/cloudblue) organization that doesn't have its own; if a repository has one, follow that one.

## Before you start

- **Small fixes** (typos, docs, clear bugs with an obvious fix): open a pull request straight away.
- **Bigger changes** (new features, behaviour changes, new dependencies): open an issue first, so we can agree on the approach before you spend time on it.
- **Security issues**: don't open an issue or pull request. Follow the [security policy](SECURITY.md).
- Archived repositories are read-only and don't accept changes.

## Making a pull request

1. Fork the repository and create a branch from the default branch.
2. Make your change, with tests for any behaviour you add or fix.
3. Run the same checks as CI (see the repository's README and `.github/workflows/`). Most of our Python projects use Poetry, flake8 and pytest:

   ```sh
   poetry install
   poetry run flake8
   poetry run pytest
   ```

4. Keep the pull request to one change, and say **what** it does and **why**. If it fixes an issue, link it.
5. Open the pull request against the default branch.

## Contributor License Agreement

The first time you open a pull request, a bot asks you to sign our Contributor License Agreement (CLA) with CloudBlue LLC. It takes one click with your GitHub account, and you only do it once. We can only merge pull requests whose authors have signed it.

## What to expect from us

- We aim to reply to new issues and pull requests within a few working days.
- Every pull request needs one approving review and passing checks before it is merged.
- If we can't take a change, we explain why. If a good pull request stalls, we may finish it ourselves and keep you as co-author.
- If a week goes by without a reply, add a comment to nudge us.

## Code of Conduct

Everyone who takes part follows our [Code of Conduct](CODE_OF_CONDUCT.md).
