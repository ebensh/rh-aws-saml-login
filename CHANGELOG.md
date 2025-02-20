# Changelog

## 0.5.0

### Features

* **Non-interactive mode**: Run any arbitrary command with the AWS environment variables set.

## 0.4.2

### Features

* More PyPI metadata
* Release binary wheels for Linux and macOS

## 0.4.1

### Bug Fixes

* Do not release a whell due to a `uv` bug

## 0.4.0

### Bug Fixes

* Fix kerberos ticket test on Linux ([#18](https://github.com/app-sre/rh-aws-saml-login/issues/18))

### Features

* Add `--version` option ([#16](https://github.com/app-sre/rh-aws-saml-login/issues/16))

### Chore

* Mention [uv](https://docs.astral.sh/uv/) as the recommended installation method.
* Replace poetry with [uv](https://docs.astral.sh/uv/) for the project management.
* Upgrade dependencies

## 0.3.4

* Upgrade dependencies

## 0.3.3

* Upgrade dependencies

## 0.3.2

* `--open-command` option to open the AWS web console with a custom command.

## 0.3.1

### Chore

* Upgrade dependencies

## 0.3.0

### Features

* **AWS account name shell completion**: Add shell completion (bash/zsh/fish) for AWS account names.

### Bug Fixes

* Fix project URLs in [PyPI](https://pypi.org/project/rh-aws-saml-login/)

## 0.2.0 (2024-02-13)

### Features

* **open AWS web console:** `--console` option to open the AWS web console for an account.

## 0.1.1 (2024-02-13)

### Bug Fixes

* **kinit:** fix hidden password prompt

## 0.1.0 (2024-02-12)

* Initial release
