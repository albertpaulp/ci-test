# ci-test

Automate merging by typing `/shipit` on PRs.

- Merge PR with sqashed option.
- Change Jira ticket status to pending-release.

## Requirements

- Branch name should include Jira ticket id in following format, xxxx/\<ticket-id\>/xxxxx.
- Repository should have `GH_TOKEN` and `JIRA_AUTH` tokens set.

## Good to have features

- `/shipit` on release PRs could merge the PR using "merge commit" and trigger production deployment through Github Actions.
- `/rollback` or `/ohshit` for rolling back @alan.
