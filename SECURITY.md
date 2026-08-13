# Security Policy

This policy applies across the **n1netails-lab** organization.

## What This Organization Is

N1neTails Lab hosts forks of real open source applications used for application security research — SAST evaluation, CodeQL query development, dependency and supply chain review, and secure code review practice.

Forks are point-in-time snapshots. They are not maintained, not kept in sync with upstream, and **not intended for production use by anyone**. If you need the software itself, get it from the upstream project.

## Reporting a Vulnerability in an Upstream Project

If you find a security issue in code that originates from an upstream project, **report it to that project's maintainers**, not here. Their security policy is the correct channel — this org has no ability to ship a fix to their users, and a public report here would disclose the issue before they can respond.

## Reporting a Vulnerability in Something This Org Actually Owns

For issues in code, workflows, or configuration authored by N1neTails Lab — automation, CodeQL queries, CI configuration — open a private security advisory on the relevant repository ("Security" tab → "Report a vulnerability").

Please do not open a public issue for a suspected vulnerability.

## How Findings Are Handled

When analysis in this organization surfaces a plausible issue in an upstream project:

1. **Validate first.** Raw scanner output is not a finding. Results are triaged and confirmed before anything is reported.
2. **Report privately to upstream**, using the project's documented security process. If the project has no security policy, maintainers are contacted privately.
3. **Wait.** Upstream sets the disclosure timeline. Nothing is published, filed publicly, or discussed in public until they have had the opportunity to respond and, where they choose to, ship a fix.
4. **Credit upstream.** Any eventual public writeup describes the issue as the upstream project disclosed it, and links to their advisory.

Findings are not published in this organization. Fork repositories are not used as a disclosure channel.

## For Upstream Maintainers

If your project is forked here and you would prefer it not be, say so and it will be removed — no justification needed.

If you would like to be notified about what is being run against your code, or want results shared with you directly, that is welcome. Open a private advisory on the fork or contact the org owner.

## Out of Scope

- Vulnerabilities in unmodified upstream code, reported here rather than upstream
- Reports that a fork is outdated relative to upstream — this is expected and documented
- Automated scanner output submitted without validation
