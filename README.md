# Hot TODOs

* **Triage**
  * Things that are not absolute `v10` stop-ship should be moved to `v10-update` milestone. Current `v10` stop-ship criteria is:
    * Ones designers think absolute `v10` show stopper
    * Fixes that require breaking change of `v10` API (Note that we are striving to avoid breaking changes, though)
  * Visual review comments in PR needs to be triaged as well. Action items on this is:
    * Designers to determine what absolute no-go design review items of each PRs are
    * Remainders of the design review items will be tracked as separate issues. Each of them will be triaged
  * As we defer issues and fix issues, issues in `v10-rc1` milestone should be *zero* before we ship `v10`
* Clean up open visual/code reviews - You can utilize some of below links
* Get all open questions answered - You can utilize some of below links
* Do the following when you create PRs:
  * Assign `v10-rc` milestone to all new `v10` ship stopper issues/PRs
  * Add WIP label to all new draft PRs
  * Assigned designer for component should be set as the reviewer for any PRs that require design reviews (In addition to adding `visual review` label)
* Talk! (Designers/devs talking each other is one of the biggest treasures in Carbon team! 😉)

# Hot links

## `v10` ship stopper issues

* https://github.com/IBM/carbon-components/issues?q=is%3Aopen+is%3Aissue+milestone%3Av10.0-rc1
* https://github.com/IBM/carbon-components-react/issues?q=is%3Aopen+is%3Aissue+milestone%3Av10.0-rc1

## PRs associated with `v10` ship stoppers

* https://github.com/IBM/carbon-components/pulls?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+milestone%3Av10.0-rc1+-label%3A%22status%3A+WIP+%F0%9F%91%A9%E2%80%8D%F0%9F%92%BB%22+-label%3A%22status%3A+blocked+%F0%9F%99%85%E2%80%8D%E2%99%80%EF%B8%8F%22
* https://github.com/IBM/carbon-components-react/pulls?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+milestone%3Av10.0-rc1+-label%3A%22status%3A+WIP+%F0%9F%91%A9%E2%80%8D%F0%9F%92%BB%22+-label%3A%22status%3A+blocked+%F0%9F%99%85%E2%80%8D%E2%99%80%EF%B8%8F%22

## PRs that need visual review associated with `v10` ship stoppers

* https://github.com/IBM/carbon-components/pulls?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+milestone%3Av10.0-rc1+label%3A%22status%3A+visual+review+%3Aeyes%3A%22+-label%3A%22status%3A+WIP+%F0%9F%91%A9%E2%80%8D%F0%9F%92%BB%22+-label%3A%22status%3A+blocked+%F0%9F%99%85%E2%80%8D%E2%99%80%EF%B8%8F%22
* https://github.com/IBM/carbon-components-react/pulls?utf8=%E2%9C%93&q=is%3Aopen+is%3Apr+milestone%3Av10.0-rc1+label%3A%22status%3A+visual+review+%3Aeyes%3A%22+-label%3A%22status%3A+WIP+%F0%9F%91%A9%E2%80%8D%F0%9F%92%BB%22+-label%3A%22status%3A+blocked+%F0%9F%99%85%E2%80%8D%E2%99%80%EF%B8%8F%22

## `v10` ship stopper issues/PRs with open questions

* https://github.com/IBM/carbon-components/issues?q=is%3Aopen+label%3A%22type%3A+question+%3Aquestion%3A%22+milestone%3Av10.0-rc1
* https://github.com/IBM/carbon-components-react/issues?q=is%3Aopen+label%3A%22type%3A+question+%3Aquestion%3A%22+milestone%3Av10.0-rc1
