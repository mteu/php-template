<div align="center">

# Basic Project Builder Template

[![CGL](https://github.com/mteu/basic-project-template/actions/workflows/cgl.yaml/badge.svg)](https://github.com/mteu/basic-project-template/actions/workflows/cgl.yaml)
[![Latest Stable Version](http://poser.pugx.org/mteu/basic-project-template/v)](https://packagist.org/packages/mteu/basic-project-template)
[![License](http://poser.pugx.org/mteu/basic-project-template/license)](LICENSE.md)

:package:&nbsp;[Packagist](https://packagist.org/packages/mteu/basic-project-template) |
:floppy_disk:&nbsp;[Repository](https://github.com/mteu/basic-project-template) |
:bug:&nbsp;[Issue tracker](https://github.com/mteu/basic-project-template/issues)

</div>

This is a framework agnostic [Project Builder](https://github.com/CPS-IT/project-builder) template with a relatively basic initial setup. It facilitates a swift and easy-to-use creation
of Composer based PHP projects.

## 🚀 Features

### Core features

* Blank'ish Composer-based project template
* Ready-to-use [DDEV](https://ddev.readthedocs.io) configuration
* Support of current stable PHP versions >= 8.1

### Optional features

* Static code analysis template with [PHPStan](https://phpstan.org/)
* Automatic code migration with [Rector](https://getrector.com/)

## 🔥 Getting started

1. Create a new project:

   ```bash
   composer create-project cpsit/project-builder <target-directory>
   ```

2. Select `Packagist.org` as template source.
3. Select the package `mteu/basic-project-template`.
4. Answer all questions, follow the instructions, and you're good to go.

   > 💡 Please refer to the official Project Builder [documentation](https://github.com/CPS-IT/project-builder/blob/main/docs/usage.md)
   > to learn about alternative ways to create your project.

## 👩‍💻:🧑‍💻 Contribution

We welcome your feedback and ideas! One quick ask, though: Please do consult [`CONTRIBUTING.md`](CONTRIBUTING.md) before
proposing a PR. Thanks!

## 💛 Acknowledgement
This template is heavily based on the preparatory work done by [@eliashaeussler](https://github.com/eliashaeussler) and
[@mteu](https://github.com/mteu) in the [TYPO3 Template Package](https://github.com/CPS-IT/typo3-project-template).

## ⭐ License

This project is licensed under [GNU General Public License 3.0 (or later)](LICENSE.md).
