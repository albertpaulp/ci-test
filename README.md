# ci-test

- Merge PR with sqashed option.
- Change Jira ticket status to pending-release.

## Requirements

- Branch name should include Jira ticket id in following format, xxxx/<ticket-id>/xxxxx.
- Repository should have `GH_TOKEN` and `JIRA_AUTH` tokens set.

## Feature requests

- "/shipit" on release PRs could merge the PR  and trigger production deployment Github Actions. 
