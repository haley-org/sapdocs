# Merge Chain Test

This repository is the internal source of the external version:

* Branch `next` allows to work separately on the next release version
* Branch `main` is kept in sync with the counterpart repo on github.com for external collaboration

Main flow (overview):

* Changes in branch `main` in this repository lead to PRs in counterpart repo on github.com and vice versa.
* Authors work in separate branches for next release, and merge it to `next` for final review.
* After the release decision, `next` is merged with `main`, which leads to a PR on `github.com:main`.


  
