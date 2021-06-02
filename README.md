# Terraform Example and Demos
<!-- markdownlint-disable MD013 -->

![terraform-lint](https://github.com/oehrlis/terraform/workflows/terraform-lint/badge.svg)

This repository provides a collection of example *terraform* configurations and
modules, which I’ve created for my presentations at various conferences and user
group meetings. In most cases, the Terraform configurations are for Oracle Cloud
Infrastructure (OCI). Slides and additional information are usually available at
[www.oradba.ch](www.oradba.ch).

| User Group   | Description                              |
|--------------|------------------------------------------|
| [SOUG](SOUG) | Presentations at Swiss Oracle User Group |

## Requirements

- [Terraform](https://www.terraform.io/downloads.html) v0.13.1 or greater
- Terraform OCI provider v4.13.0 or greater see [oci](https://registry.terraform.io/providers/hashicorp/oci/latest)

## Files and Folders

- [SOUG](SOUG) Terraform examples used during the presentation at SOUG day.
- [AUTHOR_GUIDE](AUTHOR_GUIDE.md) General author's guide to *Markdown Doc
  Template*. This has to be adapted to the corresponding guideline.
- [CHANGELOG](CHANGELOG.md) Change log for the *Markdown Doc Template*.

## Releases and Versions

You find all official releases and release information on the GitHub
project [release page](https://github.com/oehrlis/terraform/releases). As well
documented in the [CHANGELOG](CHANGELOG.md).

The versioning and release tags follow the [semantic versioning](https://semver.org/).
A version number is specified by MAJOR.MINOR.PATCH, increase the:

- *MAJOR* version when you make incompatible API changes,
- *MINOR* version when you add functionality in a backwards compatible manner, and
- *PATCH* version when you make backwards compatible bug fixes.

Additional labels for pre-release and build metadata are available as extensions
to the MAJOR.MINOR.PATCH format.

## Issues

Please file your bug reports, enhancement requests, questions and other support requests within [Github's issue tracker](https://help.github.com/articles/about-issues/).

- [Questions](https://github.com/oehrlis/terraform/issues?q=is%3Aissue+label%3Aquestion)
- [Open enhancements](https://github.com/oehrlis/terraform/issues?q=is%3Aopen+is%3Aissue+label%3Aenhancement)
- [Open bugs](https://github.com/oehrlis/terraform/issues?q=is%3Aopen+is%3Aissue+label%3Abug)
- [Submit new issue](https://github.com/oehrlis/terraform/issues/new)

## How to Contribute

1. Describe your idea by [submitting an issue](https://github.com/oehrlis/terraform/issues/new)
2. [Fork this respository](https://github.com/oehrlis/terraform/fork)
3. [Create a branch](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/), commit and publish your changes and enhancements
4. [Create a pull request](https://help.github.com/articles/creating-a-pull-request/)

## License

*oehrlis/terraform* is licensed under the Apache License 2.0. You may obtain a
copy of the License at <http://www.apache.org/licenses/LICENSE-2.0>.
