# Security Policy

## Supported Versions

The latest released version in the Groovy 3.0.x stream of releases
is the currently recommended version of Groovy and requires JDK8 as a minimum.
The latest released version in the Groovy 2.5.x stream is recommended where JDK7 is required.

| Version  | Supported          | Comment                                  |
| -------- | ------------------ | ---------------------------------------- |
| <= 2.3.x | :x:                |                                          |
| 2.4.x    | :grey_question:    | Only severe/critical vulnerabilities (*) |
| 2.5.x    | :white_check_mark: |                                          |
| 3.0.x    | :white_check_mark: |                                          |
| 4.x      | :grey_question:    | Pre-release status (**)                  |

(\*) The 2.4.x stream is no longer the focus of the core team
but critical security fixes or community contributions may lead
to additional releases.

(**) While in early stages of pre-release, security fixes are
done on a best effort basis.

## List of Security Vulnerability Fixes

The Groovy website has a list of [Security fixes](https://groovy-lang.org/security.html)
applicable to Groovy 2.4.4 and above (versions released since moving to Apache).

## Reporting a Vulnerability

Apache Groovy follows the Apache
[general guidelines for handling security vulnerabilities](http://www.apache.org/security/committers.html).
