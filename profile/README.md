# N1neTails Lab

Welcome to **N1netails Lab** 🦊

N1neTails Lab is an application security research organization. It hosts **forks of real open source applications** used as subjects for AppSec analysis — static analysis, dependency and supply chain review, secure code review, and security tooling evaluation.

---

## ⚠️ These Are Not Vulnerable-by-Design Applications

The repositories here are **forks of genuine open source projects**. They are not training targets, not deliberately broken, and not published because anyone believes they are insecure.

- A repository existing in this org is **not** a claim that the upstream project is vulnerable.
- Forks are **point-in-time snapshots** and are not kept in sync with upstream. Never use them as a source of the real project — go to the upstream repository.
- Nothing here should be treated as a security assessment of the upstream project, published or otherwise.
- Each fork keeps the upstream project's original license, copyright, and attribution.

N1neTails Lab is **not affiliated with, endorsed by, or speaking for** any of the upstream projects it forks.

---

## 🎯 Purpose

Forks in this organization are used to:

- Run and tune Static Application Security Testing (SAST) tools against real-world code
- Write, test, and refine CodeQL queries
- Exercise GitHub Advanced Security features on realistic codebases
- Evaluate scanner accuracy — including false positive and false negative rates
- Study dependency and software supply chain risk in real projects
- Practice secure code review at production scale and complexity
- Build and validate AppSec automation workflows

Real applications are the point. Synthetic vulnerable apps do not tell you how a tool behaves against a large, idiomatic, actively maintained codebase.

---

## 🔍 Areas of Analysis

- Web Application Security
- API Security
- Software Supply Chain Security
- Container Security
- Cloud Security
- Infrastructure as Code (IaC)
- Secure Development Practices

Analysis covers weakness classes such as injection, cross-site scripting, path traversal, insecure deserialization, secret exposure, authentication and authorization flaws, dependency vulnerabilities, and memory safety issues.

---

## 🤝 Responsible Disclosure

If analysis in this organization surfaces a plausible security issue in an upstream project, it is reported **privately to that project's maintainers first**, through their documented security process. Findings are not published here, filed as public issues, or discussed in public before the upstream project has had the opportunity to respond.

Scanner output is not a finding. Results are validated before anything is reported.

See [SECURITY.md](https://github.com/n1netails-lab/.github/blob/main/SECURITY.md) for the full policy.

---

## 📬 Contact

Security concerns about anything in this organization — including a request to remove a fork — can be raised through the process in [SECURITY.md](https://github.com/n1netails-lab/.github/blob/main/SECURITY.md). Upstream maintainers who would prefer their project not be forked here: reach out, and it will be taken down.
