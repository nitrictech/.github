# Security policy

Please don't report a security vulnerability in a public GitHub issue, discussion or pull request. That makes the problem public before there's a fix.

## Reporting a vulnerability

Report it privately in one of these ways:

- **On GitHub (preferred):** open the **Security & quality** tab of the affected repository and click **Report a vulnerability**.
- **By email:** send it to [security@nitric.io](mailto:security@nitric.io) if you don't use GitHub, or if the repository has no **Report a vulnerability** button.

Include as much as you can:

- The affected repository, and the version, commit or Docker image tag
- Steps to reproduce the problem
- What an attacker could do with it
- A suggested fix, if you have one

Don't open a public pull request with a fix. GitHub lets us work on one with you in a temporary private fork.

If you used AI tools to find the problem or write the report, say so, and check the report yourself before you send it. We'll close reports we can't reproduce.

## Scope

This policy covers the public repositories in the nitrictech organization and the releases built from them, including Docker images.

These are out of scope:

- Archived repositories. They don't get fixes.
- Forks of other projects, and bugs in third-party dependencies. Report those upstream. Do tell us if we use a vulnerable dependency in a way you can exploit.
- Scanner output without a working proof of concept.
- Problems that need admin access, or a setup our docs warn against.
- Example and demo apps. They aren't built for production use.

## What to expect

- We'll acknowledge your report within 3 business days. If you don't hear from us by then, email [security@nitric.io](mailto:security@nitric.io).
- We'll tell you whether we've confirmed the vulnerability, and keep you updated while we work on a fix.
- When we fix a confirmed vulnerability, we'll publish a GitHub security advisory, with a CVE where it's warranted. The advisory credits you, unless you'd rather not be named. If we decide not to fix it, we'll tell you why.

## Disclosure

Please keep the details private until we publish an advisory, or until 90 days after your report, whichever comes first. If a fix needs longer, we'll explain why and agree a new date with you.

## Supported versions

Security fixes go into the latest release only, or the default branch for repositories without releases. We don't backport them to older versions, so update to the latest release to get them.

## Testing

While you investigate:

- Only test installations you run, or have permission to test.
- Only access the data you need to show the problem, and don't change or delete anyone else's data.
- Don't disrupt anyone's services, for example with denial-of-service attacks or spam.
- Don't use social engineering or attack physical security.

## Bug bounty

We don't run a bug bounty program, so we can't pay for reports.
