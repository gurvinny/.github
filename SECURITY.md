# Security Policy

This is the default security policy for all public repositories under
[github.com/gurvinny](https://github.com/gurvinny). Individual repositories may publish their own
`SECURITY.md`, which takes precedence over this one.

## Reporting a vulnerability

Report privately through [GitHub Security Advisories](https://github.com/gurvinny) on the
affected repository, using **Report a vulnerability** under its Security tab. If that is
unavailable, contact me through my GitHub profile.

Please do not open a public issue or pull request for a security concern. A public report
discloses the finding before it can be corrected, and issues are disabled on some of these
repositories.

Expect an initial response within seven days. These are personal projects maintained outside
working hours, so triage is best-effort rather than guaranteed.

## Scope

In scope across these repositories:

- Credentials, keys, or tokens committed to a repository
- Vulnerabilities in code published here, including dependency issues that are reachable in the
  published configuration
- Infrastructure detail published in error
- Documentation that would leave a reader less secure if followed

Out of scope: the security of third-party tools referenced here, vulnerabilities in dependencies
that are not reachable in the shipped configuration, and the configuration of systems other than
the ones documented in a given repository.

## Disclosure

Report privately first. Once a fix is released, or after 90 days if no fix is practical, public
disclosure is welcome. Credit is given in the advisory unless you prefer otherwise.
