# snyk-pom-dependency-management-workaround

[![Known Vulnerabilities](https://snyk.io/test/github/henrist/snyk-pom-dependency-management-workaround/badge.svg)](https://snyk.io/test/github/henrist/snyk-pom-dependency-management-workaround)

This repository shows a workaround instead of using BOM inside
`<dependencyManagement>` in `pom.xml`.

See the original repo for track of the issue itself:
https://github.com/henrist/snyk-pom-dependency-management

## Workaround: Don't use BOM

Official Snyk support reponse (my ticket #2007) as of 2019-10-17:

> Thanks for putting this scenario to our attention! Looks like
> this is a missing feature that we do not have support for BOMs in
> dependencyManagement via SCM tests. I have added a ticket to our
> backlog for this.
>
> In the meanwhile, you will need to directly manage the dependencies
> in order to see the expected result when importing your project from SCM.
