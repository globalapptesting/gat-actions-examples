### Workflow examples for using gat-actions-request-test

This repository contains few examples on how to use [our test request action](https://github.com/GlobalAppTesting/gat-actions-request-test) in the wild.

Test it yourself:
- fork this repo
- sign up for your API KEY [here](https://go.globalapptesting.com/compare?hs_preview=rCyvmukc-45752713128)
- set your API key as a `GAT_API_KEY` secret in your repo

You should also change the description in `.gat.json` to include your webpage URL. Otherwise our testers will be checking [if Cyberpunk's website is any better than the game is.](https://www.cyberpunk.net).

---

Included examples are:

- [Request testing each night on the workdays(so you have the results when you start your work next day)](https://github.com/GlobalAppTesting/gat-actions-examples/blob/main/workflows/nightly-tests.yml)
- [Request testing over the weekend](https://github.com/GlobalAppTesting/gat-actions-examples/blob/main/workflows/tests-on-the-weekend.yml)
- [Request testing when new pull request is created](https://github.com/GlobalAppTesting/gat-actions-examples/blob/main/workflows/tests-on-new-pull-request.yml)
- [Request testing when new release is published](https://github.com/GlobalAppTesting/gat-actions-examples/blob/main/workflows/tests-on-the-release.yml)
