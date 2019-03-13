# v10 Release Planning

## Release Goals

1. All Carbon design and development assets (getting started, guidelines, components, patterns) reflect the new IBM Design Language (IDL)
1. Quality of release deliverables should at minimum match v9 release deliverables

## Release Definition of Done

* All GitHub (GH) issues and pull requests (PRs) for the release are completed and accepted
* All known fixes that require v9 breaking changes are done (while striving to minimize breaking changes)
* All packages (elements, vanilla, react) released to NPM
* All design assets (kit) published to respective places
* All deprecated repos are archived, packages deprecated
* All documentation (website) is deployed
* All new and changed functionality (especially breaking changes) is included in migration and changelog documentation
* Component definition of done exclusions
  * IE11 is not a priority in this release, although exploratory testing is recommended to help identify major issues (that could require breaking changes)
  * IDL motion (because its replacing existing animations, and not a breaking change for when it's ready)
  * AVT level 1 is good enough
  
Questions:

* Should we have consistent versioning (e.g. all upped to 10)? What's this mean for Vue and Angular?

## Release Schedule

**v10 RC1 [Date]** - code freeze 3 days before GA (excludes final documentation changes that had been missed)

**v10 [Date]** - we generally available!

# Process

**Release Backlog Gatekeeper: [Person]**

TODO: how are we using GH milestones? [GH milestones, labels, process](https://github.com/carbon-design-system/private-issues/blob/master/README.md)

TODO: release backlog should be "frozen" by **[date]**

* Make sure GH issues to track:
  * Design: determine Sketch theme structure
  * Design: what to expect with migration, symbol/library swapping, etc.
  * Design: getting started updates
  * Dev: changes to component APIs, Sass, Sass API documentation, markup changes?

# Component Definition of Done

* Design
  * Follows IBM Design Language (color, theme, type, layout, spacing, motion)
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
  * Passes AVT level 3 for accessibility
  * Works in browsers
    * Chrome latest
    * Firefox latest
    * Safari latest
    * Microsoft Edge latest
    * IE11
  * 80% test coverage
