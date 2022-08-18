# Dependabot automation
Automation script that automatically merges dependabot PRs

[Dependabot auto merge workflow](https://raw.githubusercontent.com/kkocel/dependabot-automation/main/.github/workflows/auto-merge-dependabot.yml)

Above script requires repo to have:
1. `Allow squash merging` option enabled
2. `Allow auto-merge ` option enabled
3. Optional: Branch protection rule with `Require status checks to pass before merging` option enabled.
