# Security policy

## Reporting a vulnerability

Report suspected vulnerabilities privately through GitHub's
[private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability):
open the affected repository, go to the **Security** tab, and choose **Report a
vulnerability**.

Please do not open a public issue or pull request for a suspected
vulnerability.

Useful reports include what an attacker could do, the affected repository and
version or commit, and the steps to reproduce it.

## Scope

snowball projects are static sites and small stateless services. They hold no
user accounts and no user data. The most useful reports concern exposed
credentials, a server-side request or injection path, a dependency with a known
exploited vulnerability, or data published that should not have been.

Reports about a hosting provider, a third-party data source or a dependency
belong with that party first.

## Supported versions

Only the current published version of each project is supported. Fixes land on
`main` and are released from there; older tags are not patched.

## Expectations

These are personal, zero-cost projects maintained by one founder. There is no
paid bounty and no guaranteed response time. Credible reports will be
acknowledged and addressed as soon as is practical.
