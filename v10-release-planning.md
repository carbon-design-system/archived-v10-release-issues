# v10 Release Planning

## Release Goals

1. All Carbon design and development assets (getting started, guidelines, components, patterns) reflect the new IBM Design Language (IDL)
1. Quality of release deliverables should at minimum match v9 release deliverables

## Release Definition of Done

* All GitHub (GH) issues and pull requests (PRs) for the release are completed and accepted
* All known fixes that require v9 breaking changes are done (while striving to minimize breaking changes)
* All packages released to NPM
* All design assets published to respective places
* All new and changed functionality (especially breaking changes) is included in migration and changelog documentation
* Component definition of done exclusions
  * Not all cross-browser (namely IE11) bugs need fixed prior to release as long as the expected fixes won't require breaking changes

## Release Schedule

TODO

# Process

[GH milestones, labels, process](https://github.com/carbon-design-system/private-issues/blob/master/README.md)

* Make sure GH issues to track:
  * Design: determine Sketch theme structure
  * Design: what to expect with migration, symbol/library swapping, etc.
  * Design: getting started updates
  * Dev: changes to component APIs, Sass, Sass API documentation, markup changes?

# Component Definition of Done

* Design
  * Follows IBM Design Language
  * Considers accessibility inclusiveness
  * Validated by real users
  * Works with realistic data
  * Works on supported platforms/resolutions
  * Includes empty and loading states
  * Includes usage guidelines
* Development
  * Has accompanying design
  * Passes visual review
  * Passes acceptance criteria (e.g. usage guidelines)
  * TODO browsers
  * TODO accessibility
  * TODO test coverage
