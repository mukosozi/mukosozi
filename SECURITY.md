# Security Policy

Mukosozi takes security seriously, even at this early stage of development. This policy describes how to report a vulnerability and what to expect after you do.

## Reporting a Vulnerability

**Please do not report security issues through public GitHub issues, discussions, or pull requests.**

To report a vulnerability privately, use GitHub's [Private Vulnerability Reporting](https://github.com/mukosozi/mukosozi/security/advisories/new) feature for this repository. This creates a confidential advisory visible only to the maintainer.

If you cannot use GitHub's reporting flow for any reason, email the maintainer at `mukosozi.rw@gmail.com` with a subject line beginning `[SECURITY]`.

## What to Include

A useful report typically contains:

- A clear description of the issue and its potential impact
- Steps to reproduce the issue
- The affected file(s) or component(s)
- The version or commit hash where the issue was observed
- Any suggested mitigation or fix, if you have one

## Response Expectations

This project is maintained by a single person alongside other commitments, so timelines are honest rather than aspirational:

| Stage | Target |
|---|---|
| Acknowledge receipt of report | Within 7 days |
| Initial assessment and triage | Within 14 days |
| Fix or mitigation released (for confirmed valid reports) | Best effort, depends on severity and complexity |

For reports indicating an active exploit or critical impact, response will be expedited.

## Supported Versions

Only the latest minor release receives security fixes. Older versions are not maintained.

| Version | Supported |
|---|---|
| Latest `0.x` minor release | ✅ |
| Older releases | ❌ |

## Disclosure Policy

After a vulnerability is confirmed:

1. The maintainer will work with the reporter to develop and verify a fix.
2. A coordinated disclosure timeline will be agreed upon — typically 30 to 90 days, depending on severity and complexity.
3. A fix will be released, followed by public disclosure with credit to the reporter (unless anonymity is requested).

## Scope

**In scope:**

- The Mukosozi web application (`mukosozi.html`)
- Any source code or scripts in this repository
- Linguistic data files (`data/`) where a crafted entry could enable an attack on a consumer of the data

**Out of scope:**

- Issues requiring physical access to the user's device
- Social engineering attacks against the maintainer or users
- Denial of service in a single-user, client-side context
- Theoretical issues with no demonstrable impact
- Issues in unreleased or experimental code on non-`main` branches
- Vulnerabilities in third-party dependencies — please report those upstream to the relevant project

## Bug Bounty

Mukosozi is an independent open-source project with no funding. **No monetary rewards are offered for vulnerability reports.** Credit and acknowledgment in release notes or a published security advisory is offered for valid reports, unless the reporter prefers to remain anonymous.

## Acknowledgments

Vulnerabilities reported under this policy will be acknowledged in the relevant release notes or in a published GitHub security advisory, with the reporter's consent.

---

*This policy may evolve as the project grows. Material changes will be reflected in the commit history of this file.*
