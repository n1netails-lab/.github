# Contributing

This organization hosts forks of real open source applications, used as subjects for application security research.

## Contribute Upstream, Not Here

If you want to fix a bug, add a feature, or patch a vulnerability in a forked application, **send it to the upstream project**. Forks here are analysis snapshots — they are not maintained, changes made here reach no users, and a patch merged here does nothing for the people actually running the software.

Pull requests that change upstream application code will be closed with a pointer to the upstream repository.

## What Is Welcome

- **Analysis tooling** — CodeQL queries, scanner configuration, CI workflows used to run analysis
- **Corrections to org documentation** — including this file, `SECURITY.md`, and the org profile
- **Triage help** — evidence that a reported finding is a false positive, or that a scanner result was misread

## Security Findings

Do not open a public issue or pull request for a suspected vulnerability, in a fork or anywhere else in this org. Follow [SECURITY.md](SECURITY.md): upstream issues go to upstream maintainers privately, and issues in this org's own code go through a private security advisory.

## Licensing

Forks retain their upstream license and attribution. Do not add, remove, or alter `LICENSE`, `NOTICE`, copyright headers, or attribution in forked code. Contributions to this org's own tooling are made under that repository's license.
