# Change Log

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

<a name="1.30.0"></a>
# [1.30.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.29.1...v1.30.0) (2020-03-23)


### Bug Fixes

* Remove assumption on lint job including -report suffix ([f0a21ad](https://github.com/edahlseng/configuration-ci-general/commit/f0a21ad))


### Features

* Add variant parameter to test job ([b227287](https://github.com/edahlseng/configuration-ci-general/commit/b227287))



<a name="1.29.1"></a>
## [1.29.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.29.0...v1.29.1) (2020-03-06)


### Bug Fixes

* Install Terraform before running setup-steps ([66e4965](https://github.com/edahlseng/configuration-ci-general/commit/66e4965))



<a name="1.29.0"></a>
# [1.29.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.28.0...v1.29.0) (2020-01-06)


### Features

* Make terraform-image-tag parameter optional ([2a3e109](https://github.com/edahlseng/configuration-ci-general/commit/2a3e109))



<a name="1.28.0"></a>
# [1.28.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.27.1...v1.28.0) (2020-01-05)


### Bug Fixes

* Error on non-success status code in post-pr-comment command ([4436c7d](https://github.com/edahlseng/configuration-ci-general/commit/4436c7d))
* Put linting results at the end of the lint job ([15b3ca7](https://github.com/edahlseng/configuration-ci-general/commit/15b3ca7))


### Features

* Add halt command ([766d773](https://github.com/edahlseng/configuration-ci-general/commit/766d773))
* Add install-dependencies job ([d81192b](https://github.com/edahlseng/configuration-ci-general/commit/d81192b))
* Add install-dependencies-clojure command ([08cf23d](https://github.com/edahlseng/configuration-ci-general/commit/08cf23d))
* Add install-terraform-version command ([4adb1bb](https://github.com/edahlseng/configuration-ci-general/commit/4adb1bb))
* Add log-in-to-docker-hub command ([85cfccb](https://github.com/edahlseng/configuration-ci-general/commit/85cfccb))
* Add run-pre-init-script command ([9db0ad3](https://github.com/edahlseng/configuration-ci-general/commit/9db0ad3))
* Add set-up-environment-variables-from-suffix command ([263d66a](https://github.com/edahlseng/configuration-ci-general/commit/263d66a))
* Add set-up-terraform-variables command ([b4f05b3](https://github.com/edahlseng/configuration-ci-general/commit/b4f05b3))
* Add tag-current-commit command ([dafaf4f](https://github.com/edahlseng/configuration-ci-general/commit/dafaf4f))
* Add terraform-run job ([f3cf99e](https://github.com/edahlseng/configuration-ci-general/commit/f3cf99e))
* Add tfenv executor ([9e9e7aa](https://github.com/edahlseng/configuration-ci-general/commit/9e9e7aa))
* Add validate-circleci-orb job ([755682e](https://github.com/edahlseng/configuration-ci-general/commit/755682e))
* Update Docker images from stretch to buster ([38a61af](https://github.com/edahlseng/configuration-ci-general/commit/38a61af))



<a name="1.27.1"></a>
## [1.27.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.27.0...v1.27.1) (2019-12-17)


### Bug Fixes

* Append AWS credentials rather than overwriting ([4a7a5a6](https://github.com/edahlseng/configuration-ci-general/commit/4a7a5a6))
* Handle ~/.aws directory already exists in configure-aws-profile ([0474f9a](https://github.com/edahlseng/configuration-ci-general/commit/0474f9a))
* Specify AWS credentials correctly in configure-aws-profile command ([93f82c4](https://github.com/edahlseng/configuration-ci-general/commit/93f82c4))



<a name="1.27.0"></a>
# [1.27.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.26.0...v1.27.0) (2019-12-17)


### Features

* Add parameters to configure-aws-profile command ([c9ba324](https://github.com/edahlseng/configuration-ci-general/commit/c9ba324))



<a name="1.26.0"></a>
# [1.26.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.25.0...v1.26.0) (2019-11-27)


### Features

* Add recursive and directory parameters in lint-terraform ([ffcf380](https://github.com/edahlseng/configuration-ci-general/commit/ffcf380))



<a name="1.25.0"></a>
# [1.25.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.24.0...v1.25.0) (2019-10-24)


### Features

* Add checkout job ([ca86ff4](https://github.com/edahlseng/configuration-ci-general/commit/ca86ff4))
* Add generic lint job ([104f06a](https://github.com/edahlseng/configuration-ci-general/commit/104f06a))
* Add variant parameter to build job ([7ac6b04](https://github.com/edahlseng/configuration-ci-general/commit/7ac6b04))



<a name="1.24.0"></a>
# [1.24.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.23.1...v1.24.0) (2019-10-13)


### Features

* Add NPM dependency caching to install-dependencies-npm job ([9ed2f8f](https://github.com/edahlseng/configuration-ci-general/commit/9ed2f8f))



<a name="1.23.1"></a>
## [1.23.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.23.0...v1.23.1) (2019-10-10)


### Bug Fixes

* Fix check for NPM in build and test jobs ([6415183](https://github.com/edahlseng/configuration-ci-general/commit/6415183))
* Reduce logs when checking for command runner in build and test jobs ([291a82f](https://github.com/edahlseng/configuration-ci-general/commit/291a82f))



<a name="1.23.0"></a>
# [1.23.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.22.2...v1.23.0) (2019-09-25)


### Features

* Prevent Terraform from asking for input for variables not set ([446b9c2](https://github.com/edahlseng/configuration-ci-general/commit/446b9c2))
* Save Terraform output to log file during plan and apply ([9fc69f2](https://github.com/edahlseng/configuration-ci-general/commit/9fc69f2))



<a name="1.22.2"></a>
## [1.22.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.22.1...v1.22.2) (2019-09-09)


### Bug Fixes

* Handle existing pull request not found ([e9f9baa](https://github.com/edahlseng/configuration-ci-general/commit/e9f9baa))
* Include authorization token when looking for existing pull request ([26a04a8](https://github.com/edahlseng/configuration-ci-general/commit/26a04a8))
* Include username in head ref when searching for existing PR ([3017df8](https://github.com/edahlseng/configuration-ci-general/commit/3017df8))



<a name="1.22.1"></a>
## [1.22.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.22.0...v1.22.1) (2019-08-21)


### Dependency Updates

* Bump node executor from 10.13.0 to 10.16.3 ([b60ddbe](https://github.com/edahlseng/configuration-ci-general/commit/b60ddbe))



<a name="1.22.0"></a>
# [1.22.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.21.1...v1.22.0) (2019-07-29)


### Features

* Fall back from Makefile to NPM in build and test jobs ([e8d5a6e](https://github.com/edahlseng/configuration-ci-general/commit/e8d5a6e))



<a name="1.21.1"></a>
## [1.21.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.21.0...v1.21.1) (2019-07-28)


### Bug Fixes

* Correct typo, allowing create-github-release job to now finish ([31df1c3](https://github.com/edahlseng/configuration-ci-general/commit/31df1c3))



<a name="1.21.0"></a>
# [1.21.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.20.1...v1.21.0) (2019-07-15)


### Features

* Add check-docker-image-service-health command ([e85af0b](https://github.com/edahlseng/configuration-ci-general/commit/e85af0b))



<a name="1.20.1"></a>
## [1.20.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.20.0...v1.20.1) (2019-05-28)


### Bug Fixes

* Prevent error exit when grep doesn't match any lines ([d71ab70](https://github.com/edahlseng/configuration-ci-general/commit/d71ab70))



<a name="1.20.0"></a>
# [1.20.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.19.1...v1.20.0) (2019-05-20)


### Features

* Add lock-timeout parameters ([c0a815d](https://github.com/edahlseng/configuration-ci-general/commit/c0a815d))



<a name="1.19.1"></a>
## [1.19.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.19.0...v1.19.1) (2019-05-15)


### Bug Fixes

* Update test job to use correct executor and correct command ([a90e878](https://github.com/edahlseng/configuration-ci-general/commit/a90e878))



<a name="1.19.0"></a>
# [1.19.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.18.3...v1.19.0) (2019-05-15)


### Features

* Add build job ([d46e8b3](https://github.com/edahlseng/configuration-ci-general/commit/d46e8b3))



<a name="1.18.3"></a>
## [1.18.3](https://github.com/edahlseng/configuration-ci-general/compare/v1.18.2...v1.18.3) (2019-05-13)


### Bug Fixes

* Prevent error when working with an empty release in Changelog ([24e34f6](https://github.com/edahlseng/configuration-ci-general/commit/24e34f6))



<a name="1.18.2"></a>
## [1.18.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.18.1...v1.18.2) (2019-05-13)


### Bug Fixes

* Improve logging and exit process for create-release-pr job ([7dcf552](https://github.com/edahlseng/configuration-ci-general/commit/7dcf552))



<a name="1.18.1"></a>
## [1.18.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.18.0...v1.18.1) (2019-05-13)


### Bug Fixes

* Prevent release PRs from being created if changelog is empty ([6b14ab3](https://github.com/edahlseng/configuration-ci-general/commit/6b14ab3))



<a name="1.18.0"></a>
# [1.18.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.17.2...v1.18.0) (2019-04-25)


### Bug Fixes

* Escape double quotes when creating a GitHub release ([c70c072](https://github.com/edahlseng/configuration-ci-general/commit/c70c072))
* Exit as error if request to create GitHub release is unsuccessful ([226dc64](https://github.com/edahlseng/configuration-ci-general/commit/226dc64))


### Features

* Add `docker_layer_caching` parameter to `build-image` job ([3ebd135](https://github.com/edahlseng/configuration-ci-general/commit/3ebd135))



<a name="1.17.2"></a>
## [1.17.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.17.1...v1.17.2) (2019-04-21)


### Bug Fixes

* Escape newlines when creating GitHub release ([bdd73b1](https://github.com/edahlseng/configuration-ci-general/commit/bdd73b1))



<a name="1.17.1"></a>
## [1.17.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.17.0...v1.17.1) (2019-04-05)


### Bug Fixes

* Correct typo with variable name ([475e25f](https://github.com/edahlseng/configuration-ci-general/commit/475e25f))



<a name="1.17.0"></a>
# [1.17.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.16.1...v1.17.0) (2019-04-05)


### Features

* Add set-up-npm-authentication command ([27a58d6](https://github.com/edahlseng/configuration-ci-general/commit/27a58d6))



<a name="1.16.1"></a>
## [1.16.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.16.0...v1.16.1) (2019-03-29)


### Bug Fixes

* Add missing comma to JSON data ([fa97939](https://github.com/edahlseng/configuration-ci-general/commit/fa97939))
* Correct log messages for release commit checks ([d9b32ee](https://github.com/edahlseng/configuration-ci-general/commit/d9b32ee))



<a name="1.16.0"></a>
# [1.16.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.15.0...v1.16.0) (2019-03-29)


### Features

* Add setup-steps parameter to validate-js job ([97cd234](https://github.com/edahlseng/configuration-ci-general/commit/97cd234))



<a name="1.15.0"></a>
# [1.15.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.14.0...v1.15.0) (2019-03-29)


### Features

* Use stretch instead of jessie based Docker images ([59c59af](https://github.com/edahlseng/configuration-ci-general/commit/59c59af))



<a name="1.14.0"></a>
# [1.14.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.13.3...v1.14.0) (2019-03-10)


### Features

* Add cleanup-isolated-commit-deployments job ([3960e7f](https://github.com/edahlseng/configuration-ci-general/commit/3960e7f))
* Add release details to created GitHub releases ([1bd18f6](https://github.com/edahlseng/configuration-ci-general/commit/1bd18f6))



<a name="1.13.3"></a>
## [1.13.3](https://github.com/edahlseng/configuration-ci-general/compare/v1.13.2...v1.13.3) (2019-02-05)


### Bug Fixes

* Delete multiple workspaces in cleanup-pr-deployments ([08a9b85](https://github.com/edahlseng/configuration-ci-general/commit/08a9b85))



<a name="1.13.2"></a>
## [1.13.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.13.1...v1.13.2) (2019-02-05)


### Bug Fixes

* Auto approve the terraform destroy step for cleanup-pr-deployments ([1e9c1fb](https://github.com/edahlseng/configuration-ci-general/commit/1e9c1fb))



<a name="1.13.1"></a>
## [1.13.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.13.0...v1.13.1) (2019-02-05)


### Bug Fixes

* Use correct get-workspace command within cleanup-pr-deployments ([ad2068c](https://github.com/edahlseng/configuration-ci-general/commit/ad2068c))



<a name="1.13.0"></a>
# [1.13.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.12.0...v1.13.0) (2019-01-25)


### Features

* Add cleanup-pr-deployments job ([b16ed12](https://github.com/edahlseng/configuration-ci-general/commit/b16ed12))
* Add halt-if-not-pr command ([0e058ce](https://github.com/edahlseng/configuration-ci-general/commit/0e058ce))
* Add post-pr-comment command ([9169b2f](https://github.com/edahlseng/configuration-ci-general/commit/9169b2f))
* Add select-or-create-workspace command ([a6f49cb](https://github.com/edahlseng/configuration-ci-general/commit/a6f49cb))
* Add workspace parameter to terraform-plan and terraform-apply jobs ([d641cbe](https://github.com/edahlseng/configuration-ci-general/commit/d641cbe))



<a name="1.12.0"></a>
# [1.12.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.11.0...v1.12.0) (2019-01-23)


### Features

* Add add-github-to-known-hosts command ([aaa7024](https://github.com/edahlseng/configuration-ci-general/commit/aaa7024))



<a name="1.11.0"></a>
# [1.11.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.10.0...v1.11.0) (2019-01-18)


### Features

* Add run-validate-after-init parameter to validate-terraform job ([41bd762](https://github.com/edahlseng/configuration-ci-general/commit/41bd762))



<a name="1.10.0"></a>
# [1.10.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.9.0...v1.10.0) (2019-01-17)


### Bug Fixes

* Move setup_remote_docker before setup-steps for build-image job ([fcfefaf](https://github.com/edahlseng/configuration-ci-general/commit/fcfefaf))


### Features

* Add `configure-aws-profile` command ([f2e2bed](https://github.com/edahlseng/configuration-ci-general/commit/f2e2bed))
* Add `login-ecr` command ([9aacc1f](https://github.com/edahlseng/configuration-ci-general/commit/9aacc1f))
* Add build-options parameter to build-image job ([f9a8575](https://github.com/edahlseng/configuration-ci-general/commit/f9a8575))



<a name="1.9.0"></a>
# [1.9.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.8.1...v1.9.0) (2019-01-16)


### Features

* Add build-image job ([c5024dd](https://github.com/edahlseng/configuration-ci-general/commit/c5024dd))



<a name="1.8.1"></a>
## [1.8.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.8.0...v1.8.1) (2019-01-09)


### Bug Fixes

* Add default for artifact-paths parameter ([cbf7c0a](https://github.com/edahlseng/configuration-ci-general/commit/cbf7c0a))



<a name="1.8.0"></a>
# [1.8.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.7.2...v1.8.0) (2019-01-09)


### Bug Fixes

* Remove redundant word from GitHub Release name ([791b7a9](https://github.com/edahlseng/configuration-ci-general/commit/791b7a9))


### Features

* Add lint-css job ([9b0328d](https://github.com/edahlseng/configuration-ci-general/commit/9b0328d))
* Add validate-js job ([a84d970](https://github.com/edahlseng/configuration-ci-general/commit/a84d970))



<a name="1.7.2"></a>
## [1.7.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.7.1...v1.7.2) (2019-01-08)


### Bug Fixes

* Add additional logging ([576f751](https://github.com/edahlseng/configuration-ci-general/commit/576f751))
* Improve array expansion for iterating over artifact paths ([bd05ee6](https://github.com/edahlseng/configuration-ci-general/commit/bd05ee6))



<a name="1.7.1"></a>
## [1.7.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.7.0...v1.7.1) (2019-01-07)


### Bug Fixes

* Put .git directory after creating tag ([f88138b](https://github.com/edahlseng/configuration-ci-general/commit/f88138b))



<a name="1.7.0"></a>
# [1.7.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.6.1...v1.7.0) (2019-01-07)


### Features

* Add create-github-release job ([8b2f9ba](https://github.com/edahlseng/configuration-ci-general/commit/8b2f9ba))



<a name="1.6.1"></a>
## [1.6.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.6.0...v1.6.1) (2018-12-12)


### Bug Fixes

* Add option for terraform-apply to ignore a missing plan ([3fd2c23](https://github.com/edahlseng/configuration-ci-general/commit/3fd2c23))
* Add setup-steps to validate-terraform job ([ea43d7f](https://github.com/edahlseng/configuration-ci-general/commit/ea43d7f))
* Set Terraform executor to use a CircleCI-compatible Docker image ([84e4680](https://github.com/edahlseng/configuration-ci-general/commit/84e4680))
* Set user on Node Docker executor ([9f51b61](https://github.com/edahlseng/configuration-ci-general/commit/9f51b61))



<a name="1.6.0"></a>
# [1.6.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.5.0...v1.6.0) (2018-12-07)


### Features

* Add setup-steps parameter to install-dependencies-npm job ([b4ca5ab](https://github.com/edahlseng/configuration-ci-general/commit/b4ca5ab))



<a name="1.5.0"></a>
# [1.5.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.4.0...v1.5.0) (2018-12-04)


### Features

* Add Terraform-related jobs and executor ([bd4d790](https://github.com/edahlseng/configuration-ci-general/commit/bd4d790))



<a name="1.4.0"></a>
# [1.4.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.3.2...v1.4.0) (2018-11-19)


### Features

* Add tag job ([65e1c35](https://github.com/edahlseng/configuration-ci-general/commit/65e1c35))
* Add test job ([6c45cd1](https://github.com/edahlseng/configuration-ci-general/commit/6c45cd1))



<a name="1.3.2"></a>
## [1.3.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.3.1...v1.3.2) (2018-11-18)


### Bug Fixes

* Use correct URL for checking for an existing release pull request ([b662ab6](https://github.com/edahlseng/configuration-ci-general/commit/b662ab6))



<a name="1.3.1"></a>
## [1.3.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.3.0...v1.3.1) (2018-11-18)


### Bug Fixes

* Use proper path for validating orbs ([91e1610](https://github.com/edahlseng/configuration-ci-general/commit/91e1610))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.2.0...v1.3.0) (2018-11-18)


### Bug Fixes

* Add version number tag to release pull request ([5574dc2](https://github.com/edahlseng/configuration-ci-general/commit/5574dc2))


### Features

* Add lint-circleci-orb job ([973927d](https://github.com/edahlseng/configuration-ci-general/commit/973927d))
* Add publish-circleci-dev job ([24d9774](https://github.com/edahlseng/configuration-ci-general/commit/24d9774))
* Add tag-and-publish-circleci job ([0448b35](https://github.com/edahlseng/configuration-ci-general/commit/0448b35))
* Parameterize Git user and credentials ([1e1ddc4](https://github.com/edahlseng/configuration-ci-general/commit/1e1ddc4))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.1.2...v1.2.0) (2018-11-18)


### Bug Fixes

* Add names to steps ([cf90df8](https://github.com/edahlseng/configuration-ci-general/commit/cf90df8))


### Features

* Rename get command to get-workspace ([0edb986](https://github.com/edahlseng/configuration-ci-general/commit/0edb986))



<a name="1.1.2"></a>
## [1.1.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.1.1...v1.1.2) (2018-11-18)


### Bug Fixes

* Add description to tag command ([91e7e6a](https://github.com/edahlseng/configuration-ci-general/commit/91e7e6a))
* Rename ssh-fingerprint parameters to git-ssh-fingerprint ([02b2b92](https://github.com/edahlseng/configuration-ci-general/commit/02b2b92))



<a name="1.1.1"></a>
## [1.1.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.1.0...v1.1.1) (2018-11-18)


### Bug Fixes

* Remove quotes for regex comparison ([2fb9297](https://github.com/edahlseng/configuration-ci-general/commit/2fb9297))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/edahlseng/configuration-ci-general/compare/v1.0.2...v1.1.0) (2018-11-18)


### Features

* Add create-release-pr job ([e696099](https://github.com/edahlseng/configuration-ci-general/commit/e696099))
* Add tag-and-publish-npm job ([cf41ff5](https://github.com/edahlseng/configuration-ci-general/commit/cf41ff5))



<a name="1.0.2"></a>
# [1.0.2](https://github.com/edahlseng/configuration-ci-general/compare/v1.0.1...v1.0.2) (2018-11-17)


### Bug Fixes

* Update commit message checking to working regex ([b9b101f](https://github.com/edahlseng/configuration-ci-general/commit/b9b101f))



<a name="1.0.1"></a>
# [1.0.1](https://github.com/edahlseng/configuration-ci-general/compare/v1.0.0...v1.0.1) (2018-11-17)


### Bug Fixes

* Add more logging ([8e9cb51](https://github.com/edahlseng/configuration-ci-general/commit/8e9cb51))



<a name="1.0.0"></a>
# 1.0.0 (2018-11-17)


### Features

* Add general orb ([81fb280](https://github.com/edahlseng/configuration-ci-general/commit/81fb280))
