### Monorepo flow

This example provides one of many ways to integrate [our action](https://github.com/GlobalAppTesting/gat-actions-request-test) with monorepos.

Given many different components and/or platforms sitting in one monorepo, one would have to figure out which issues are reported for which components. Of course, we do link issues to Pull Requests, but there still might be many PRs for same component(say - many iOS components' features) at the same time and then filtering by platform comes handy.

Basing on PR title is only one of many possible ways. You can (ab)use `github` and `github.event` contexts to explore many other angles for `issue_prefix` option. To see what's inside `github` context please refer to [github docs](https://docs.github.com/en/actions/reference/context-and-expression-syntax-for-github-actions#github-context). To explore `github.event` data we advise to use ["Debug action" action](https://github.com/marketplace/actions/debug-action).

Happy exploring!
