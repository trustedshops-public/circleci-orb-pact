circleci-orb-pact
===
[![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://github.com/trustedshops-public/pact/blob/main/LICENSE)
[![pre-commit](https://img.shields.io/badge/%E2%9A%93%20%20pre--commit-enabled-success)](https://pre-commit.com/)
[![CircleCI Build Status](https://circleci.com/gh/trustedshops-public/circleci-orb-pact.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/trustedshops-public/circleci-orb-pact)
[![CircleCI Orb Version](https://badges.circleci.com/orbs/trustedshops-public/pact.svg)](https://circleci.com/orbs/registry/orb/trustedshops-public/pact)

Circleci Orb to run pact tests in your pipelines and verify results to make sure your deployments adhere to the contract

## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/trustedshops-public/pact) - The official registry page of this
orb for all versions, executors, commands, and jobs described.

[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating
CircleCI Orbs.

### How to Contribute

We welcome [issues](https://github.com/trustedshops-public/circleci-orb-pact/issues) to
and [pull requests](https://github.com/trustedshops-public/circleci-orb-pact/pulls) against this repository!

### Commit Message Convention

This repository follows [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

#### Format

`<type>(optional scope): <description>`
Example: `feat(pre-event): Add speakers section`

#### 1. Type

Available types are:

- feat → Changes about addition or removal of a feature. Ex: `feat: Add table on landing page`
  , `feat: Remove table from landing page`
- fix → Bug fixing, followed by the bug. Ex: `fix: Illustration overflows in mobile view`
- docs → Update documentation (README.md)
- style → Updating style, and not changing any logic in the code (reorder imports, fix whitespace, remove comments)
- chore → Installing new dependencies, or bumping deps
- refactor → Changes in code, same output, but different approach
- ci → Update github workflows, husky
- test → Update testing suite, cypress files
- revert → when reverting commits
- perf → Fixing something regarding performance (deriving state, using memo, callback)
- vercel → Blank commit to trigger vercel deployment. Ex: `vercel: Trigger deployment`

#### 2. Optional Scope

Labels per page Ex: `feat(pre-event): Add date label`

*If there is no scope needed, you don't need to write it*

#### 3. Description

Description must fully explain what is being done.

Add BREAKING CHANGE in the description if there is a significant change.

**If there are multiple changes, then commit one by one**

- After colon, there are a single space Ex: `feat: Add something`
- When using `fix` type, state the issue Ex: `fix: File size limiter not working`
- Use imperative, dan present tense: "change" not "changed" or "changes"
- Use capitals in front of the sentence
- Don't add full stop (.) at the end of the sentence

### Publish new release

Commit according to semantic release spec above and let CircleCI (and semantic-release) do the magic.
