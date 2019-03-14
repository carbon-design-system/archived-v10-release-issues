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
  * IE11 and Mobile Safari is not a priority in this release, although exploratory testing is recommended to help identify major issues (that could require breaking changes)
  * IDL motion (because its replacing existing animations, and not a breaking change for when it's ready)
  * AVT level 1 is good enough
  
Questions:

* Should we have consistent versioning (e.g. all upped to 10)? What's this mean for Vue and Angular?

## Release Schedule

Use ZenHub to view all GH issues and PRs for the [v10.0-rc1 milestone](https://github.com/carbon-design-system/issue-tracking#workspaces/carbon-design-system-593830641344b813db10934d/boards?milestones=v10.0-rc1%23&filterLogic=any&repos=85987501,84835535,92527058,86360855,103418444,85728567,144656871,148382570,145154713,148800113,113475983,166278929) across all repositories. `v10-update` milestone is for stories that are high priority but are not in scope for v10.0-rc1.

**3/15/19** - v10.0-rc1 backlog freeze, subsequent changes need approval by **Robin Cannon**

**v10 RC1 [Date]** - code freeze 3 days before GA (excludes final documentation changes that had been missed)

**v10 [Date]** - we generally available!

TODO: make sure GH issues to track
  * Design: determine Sketch theme structure
  * Design: what to expect with migration, symbol/library swapping, etc.
  * Design: getting started updates
  * Dev: changes to component APIs, Sass, Sass API documentation, markup changes

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
    * Mobile Safari
  * 80% test coverage
