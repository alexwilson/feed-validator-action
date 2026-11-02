# Changelog

## [2.0.0](https://github.com/alexwilson/feed-validator-action/compare/v1.1.0...v2.0.0) (2026-11-02)


### ⚠ BREAKING CHANGES

* **inputs:** `fail-on` must be one of errors, warnings, info or never. Any other value fails the step.

### Bug Fixes

* **fetch:** authenticate api call, retry downloads ([c23c46d](https://github.com/alexwilson/feed-validator-action/commit/c23c46df342eea5f086c0e8de3508e9fe5879394)), closes [#10](https://github.com/alexwilson/feed-validator-action/issues/10)
* **inputs:** reject unknown fail-on values ([a31dc51](https://github.com/alexwilson/feed-validator-action/commit/a31dc518b4b5b03e741c80692b3820f1a61cd08f)), closes [#10](https://github.com/alexwilson/feed-validator-action/issues/10)
* move python pin to 3.14 ([#11](https://github.com/alexwilson/feed-validator-action/issues/11)) ([cf8f077](https://github.com/alexwilson/feed-validator-action/commit/cf8f0770203f25e2ea1ba3b9d980caf2b73f3404))
* pass feed input through env ([028a339](https://github.com/alexwilson/feed-validator-action/commit/028a339331e193c621b0c9a0a272d42d94e7f731)), closes [#10](https://github.com/alexwilson/feed-validator-action/issues/10)
* pin python via .python-version, not 3.x ([cfc9dae](https://github.com/alexwilson/feed-validator-action/commit/cfc9daeec80eb65a2a32f64f0247f5fd563a1b39)), closes [#10](https://github.com/alexwilson/feed-validator-action/issues/10)

## [1.1.0](https://github.com/alexwilson/feed-validator-action/compare/v1.0.1...v1.1.0) (2026-05-23)


### Features

* surface info events in summary and add `fail-on: info` ([e6fbf4a](https://github.com/alexwilson/feed-validator-action/commit/e6fbf4a272f5cee5b4789a435e2f1bc9bb2e9b3c))
* surface info events in summary and add `fail-on: info` ([dec8def](https://github.com/alexwilson/feed-validator-action/commit/dec8defdd7ad29bf5f448871c84b887d2b147988))

## [1.0.1](https://github.com/alexwilson/feed-validator-action/compare/v1.0.0...v1.0.1) (2026-05-23)


### Bug Fixes

* fetch vendored feedvalidator at runtime ([ca9b754](https://github.com/alexwilson/feed-validator-action/commit/ca9b7544dab0887f43b589113324b47fd1164a20))
* fetch vendored feedvalidator at runtime ([c42ee2b](https://github.com/alexwilson/feed-validator-action/commit/c42ee2bf6385475f1ea90deddf4bd11ba5f93748))
