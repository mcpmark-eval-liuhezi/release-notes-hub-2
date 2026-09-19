# go-github

Go library for accessing the GitHub v3 API.

- **Repository:** https://github.com/google/go-github
- **Latest release tag:** `v92.0.0`
- **Release URL:** https://github.com/google/go-github/releases/tag/v92.0.0
- **Published:** 2026-09-14

## Release notes (v92.0.0)

This release contains the following breaking API changes:

* refactor!: Pass the Codespaces body types by value and rename them to `...Request` (#4540)
* refactor!: Rename `DependencyGraphSnapshot` to `CreateDependencyGraphSnapshotRequest` and pass by value (#4519)
* feat!: Add pagination to Enterprise.ListBudgets and add GetUserStatesForBudget (#4501)
* refactor!: Split `RepositoryComment` request bodies and pass by value (#4496)

...and the following additional changes:

* chore: Bump version of go-github to v92.0.0 (#4554)
* fix: Re-add ldapdb for ghes team creation (#4553)
* feat: Add ImageGen to HostedRunner and UpdateHostedRunnerRequest (#4549)
* feat: Support the edited and dismissed actions on PullRequestReviewEvent (#4552)
* fix: Escape package names in UsersService methods (#4546)
* feat: Add simple CRUD endpoints for GitHub Copilot Spaces (#4379)
* feat: Add Agents secrets API (#4533)
* fix: Escape environment names in URL paths across 5 files (#4536)
* feat: Add Copilot user-teams daily metrics report endpoints (#4500)
* chore: Consolidate Dependabot PRs (#4542)
* chore: Remove alexandear from REVIEWERS (#4535)
* feat: Add stacked pull request endpoints (#4436)
* feat: Add GetOrganizationUsageSummary and GetUserUsageSummary to BillingService (#4521)
* fix: Escape branch names when listing rules (#4534)
* fix: Accept 202 when deleting app installation (#4529)
* docs: Deprecate singular assignee fields (#4528)
* chore: Update AUTHORS (#4522)
* feat: Add ThrottledAt field to HookDelivery (#4518)
* chore: Consolidate Dependabot PRs (#4515)
* feat: Add IsEnabled field to IssueType (#4504)
* feat: Add Copilot repository daily metrics report endpoints (#4498)
* chore: Bump go-github from v90 to v91 in /scrape (#4506)
