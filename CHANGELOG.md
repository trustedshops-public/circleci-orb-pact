## [3.0.0](https://github.com/trustedshops-public/circleci-orb-pact/compare/2.0.0...3.0.0) (2023-05-30)


### ⚠ BREAKING CHANGES

* The pact broker url is automatically prepended with https in case it does not contain a protocol.

### Features

* Add support for broker url without protocol ([dc83439](https://github.com/trustedshops-public/circleci-orb-pact/commit/dc834396defdd8a0772b942a8e1122803906aa1f))

## [2.0.0](https://github.com/trustedshops-public/circleci-orb-pact/compare/1.2.1...2.0.0) (2023-05-26)


### ⚠ BREAKING CHANGES

* Make compatible with orb tools v12 (#14)

### Code Refactoring

* Make compatible with orb tools v12 ([#14](https://github.com/trustedshops-public/circleci-orb-pact/issues/14)) ([eefb7ca](https://github.com/trustedshops-public/circleci-orb-pact/commit/eefb7ca9bb73d2476027dd9125a4e5f4993f50de))

## [1.2.1](https://github.com/trustedshops-public/circleci-orb-pact/compare/1.2.0...1.2.1) (2023-05-02)


### Bug Fixes

* **deps:** update pactfoundation/pact-cli docker tag to v0.51.0.2 ([#11](https://github.com/trustedshops-public/circleci-orb-pact/issues/11)) ([1b42864](https://github.com/trustedshops-public/circleci-orb-pact/commit/1b4286488052619f57de3a01ed05e36cd7328c8b))

## [1.2.0](https://github.com/trustedshops-public/circleci-orb-pact/compare/1.1.1...1.2.0) (2022-12-10)


### Features

* Make pact broker url for maven more robust ([9f34ca4](https://github.com/trustedshops-public/circleci-orb-pact/commit/9f34ca473ac8eee9ad3aa5c7c2597ac9663a4641))

## [1.1.1](https://github.com/trustedshops-public/circleci-orb-pact/compare/1.1.0...1.1.1) (2022-12-10)


### Bug Fixes

* Quote pact broker env vars ([16a4828](https://github.com/trustedshops-public/circleci-orb-pact/commit/16a482806ff3312a2efc188a2612beb550ee82b4))

## [1.1.0](https://github.com/trustedshops-public/circleci-orb-pact/compare/1.0.0...1.1.0) (2022-12-06)


### Features

* Upgrade pact-cli image to 0.51.0.0 ([858f214](https://github.com/trustedshops-public/circleci-orb-pact/commit/858f214c7d8d25dbe6e8b6a1dedd03035ce2042d))

# 1.0.0 (2022-02-18)


### Features

* Add initial orb sources ([#1](https://github.com/trustedshops-public/circleci-orb-pact/issues/1)) ([23d31e0](https://github.com/trustedshops-public/circleci-orb-pact/commit/23d31e0ef4ab0bd56dc3217ef64c9ed013875805))
