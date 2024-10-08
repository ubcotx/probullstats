# CHANGELOG

## v0.2.0 (2024-07-31)

### Documentation

* docs: Use furo theme for documentation ([`3d2b5ee`](https://github.com/ubcotx/probullstats/commit/3d2b5eef357571a5c7b0f30f3335a3c1443642ad))

* docs: Add initial config and content for docs ([`8616ab1`](https://github.com/ubcotx/probullstats/commit/8616ab1176cfc61ab50d435b7be02719bc09d49b))

### Feature

* feat: Added logging for unhandled exceptions ([`0f6041e`](https://github.com/ubcotx/probullstats/commit/0f6041e34d12a36c54b8e36764cff7d14f2b9cc8))

### Test

* test(xdoctests): Got placeholder docstring tests working ([`7f95450`](https://github.com/ubcotx/probullstats/commit/7f95450a1876223e0d8fdbce80179783bc7c7a48))

## v0.1.1 (2024-07-29)

### Fix

* fix: Manually repair project version ([`3246090`](https://github.com/ubcotx/probullstats/commit/3246090777c833c25ed6537ab468480b9be8204f))

## v0.1.0 (2024-07-29)

### Build

* build: Ensure poetry installed before executing build command ([`324205d`](https://github.com/ubcotx/probullstats/commit/324205dede693d47d3747d8474e8d0e9cf359073))

### Ci

* ci: Configure manual trigger for release workflow ([`e163077`](https://github.com/ubcotx/probullstats/commit/e163077f273bced71d1c959420419cfc6538317e))

* ci: Pin action versions ([`82f4ccd`](https://github.com/ubcotx/probullstats/commit/82f4ccd575ad9fd546c9848f212033ce9ae6ee17))

* ci: Add semantic release utility to CD jobs ([`b2342ce`](https://github.com/ubcotx/probullstats/commit/b2342ceb76097b61b665588fd84042032e545703))

### Documentation

* docs: Initial README content ([`6bcfb54`](https://github.com/ubcotx/probullstats/commit/6bcfb54ad7f99ab883e093a48259725a40688f41))

### Feature

* feat(ci): Add python-semantic-release utility to project ([`57c4f84`](https://github.com/ubcotx/probullstats/commit/57c4f844a21289063b8848f26585636f717a0366))

* feat(dev-tools): Finalized ruff config ([`25ba11a`](https://github.com/ubcotx/probullstats/commit/25ba11ae1a87a7cd2b2b43bb0bf72bc7e0cb9409))

* feat(dev-tools): Finalized ruff config ([`20fc2cb`](https://github.com/ubcotx/probullstats/commit/20fc2cb908489826d1c4aecb622fedddcf77f7de))

* feat(build-pipeline): Defined nox sessions for running the test suite ([`5170e0f`](https://github.com/ubcotx/probullstats/commit/5170e0ff3795ccb07e6e1a22585bd90a0a0310bb))

* feat: Drop support for Python3.8 ([`4c2da7a`](https://github.com/ubcotx/probullstats/commit/4c2da7ab482f91d30a9bed11e9f849ef0209fafd))

* feat(dev-tools): Implemented noxfile sesions for lint, format, and test ([`e0329fb`](https://github.com/ubcotx/probullstats/commit/e0329fb5d6f3f63c03bdbb80bb50c9bf99f2ce4d))

* feat(build-pipeline): Implemented initial acceptance tests ([`632f52e`](https://github.com/ubcotx/probullstats/commit/632f52e03f3414b42cd34fdeef75d70fe5a1deda))

* feat(build-pipeline): Initial steps defined for CD jobs ([`6f393f4`](https://github.com/ubcotx/probullstats/commit/6f393f466c6a98291030776d29eb96054ab8eeaa))

* feat(build-pipeline): Initial steps defined for CI jobs ([`69e0ce1`](https://github.com/ubcotx/probullstats/commit/69e0ce15f819c9cd241297f378a89f9106f043f6))

### Fix

* fix(build-pipeline): Install and test artifact from TestPyPI ([`69f4c04`](https://github.com/ubcotx/probullstats/commit/69f4c04ad49e4fccef1ee4730de56da58723ece3))

* fix: mypy and unittest errors ([`0ecc38c`](https://github.com/ubcotx/probullstats/commit/0ecc38cecf77139cde574e0b6467647e12c71e40))

* fix(dev-tools): Added configurations for mypy and ruff ([`e98bf08`](https://github.com/ubcotx/probullstats/commit/e98bf08ed8b17a57dae908a2241ad2bf7615b78c))

### Unknown

* Reset version for automatic publishing ([`c2ec72a`](https://github.com/ubcotx/probullstats/commit/c2ec72afc2a4f89250a31ef9954eb03ff3ddfe4e))

* Manually create changelog ([`0758beb`](https://github.com/ubcotx/probullstats/commit/0758bebe963c37a94766f5cf4d0d0b76153edd85))

* Reorganize container and workspace settings ([`84fc51b`](https://github.com/ubcotx/probullstats/commit/84fc51b80243cd33a3ce0a284a6ffc3f876f748f))

* Remove conditional check on publish step ([`cc233fd`](https://github.com/ubcotx/probullstats/commit/cc233fd80eb5bede438dbadc6cbb296f77a4a52d))

* Fix typo in CD pipeline ([`5720daf`](https://github.com/ubcotx/probullstats/commit/5720daf14aebab8a1a2fcee24f8a5913032606ba))

* Configure docstring plugin for project ([`49e8014`](https://github.com/ubcotx/probullstats/commit/49e8014fefec08447edcff739dbf699f67ab4c02))

* Update CD workflow to publish to testpypi ([`286999c`](https://github.com/ubcotx/probullstats/commit/286999cdcb287e0f66337dc7ae3d7181901f8169))

* Add nox session for testing artifact installed from package index ([`96baf13`](https://github.com/ubcotx/probullstats/commit/96baf13cf84fb1da449352a695e43ea5c8112270))

* Add nox sessions to run mypy over multiple python versions ([`6a5f3ee`](https://github.com/ubcotx/probullstats/commit/6a5f3ee7bd8b9e408a5ea6c433f433434985c53e))

* Change typehint syntax to support 3.9 and 3.10 ([`8977af8`](https://github.com/ubcotx/probullstats/commit/8977af83aaecdd37a5d8241f0d674df09a5bd96e))

* Move noqa pragma to per-file-ignores ([`f60bf8f`](https://github.com/ubcotx/probullstats/commit/f60bf8f72838225a55007eadf464f55bb16ae071))

* Resolve linter and mypy conflicts ([`775e76e`](https://github.com/ubcotx/probullstats/commit/775e76eb9ded7b06b59fc746160838290cf598e1))

* First acceptance test passing! ([`55ac53e`](https://github.com/ubcotx/probullstats/commit/55ac53e33737bcbd8c2b3455afe3aa59a82e2695))

* Configure package to install script entrypoint ([`89181fa`](https://github.com/ubcotx/probullstats/commit/89181fa6bc6688c0cce8cf2565283744165d1f51))

* Implement step logic for feature testing ([`fdceec8`](https://github.com/ubcotx/probullstats/commit/fdceec87a680bccbf55a19ec0db379308e42f4fe))

* Added dependencies to project ([`c067d3a`](https://github.com/ubcotx/probullstats/commit/c067d3ab86399c8b263aca85b58cd7a911d78892))

* Remove debugging statements from build pipeline ([`bfbf1b7`](https://github.com/ubcotx/probullstats/commit/bfbf1b7df93fb40c486eaf10910ce74a994df44c))

* Dump env info in build pipeline steps for debugging ([`ecba30f`](https://github.com/ubcotx/probullstats/commit/ecba30fbd6ba5b211c04332b94eb1ab3b176e235))

* Add .gitignore and poetry.lock ([`ad20744`](https://github.com/ubcotx/probullstats/commit/ad2074479321a2ed5d86280208e7b0e173e2f2a3))

* Initial commit ([`5633154`](https://github.com/ubcotx/probullstats/commit/5633154bd0a735c6faaba6639bb04bb0fd391d7d))
