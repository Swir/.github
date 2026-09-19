<div align="center">

<img width="100%" src="assets/readme-hero.svg" alt="SWIR GitHub Standards" />

<br>

[![SWIR Standard](https://img.shields.io/badge/SWIR-STANDARD-02050A?style=flat-square&logo=github&logoColor=62E5FF)](https://github.com/Swir)
[![Security Baseline](https://img.shields.io/badge/SECURITY-BASELINE-02050A?style=flat-square&logo=githubactions&logoColor=62E5FF)](SECURITY.md)
[![Maintained](https://img.shields.io/badge/STATUS-MAINTAINED-02050A?style=flat-square&logo=git&logoColor=62E5FF)](https://github.com/Swir/.github)

**Shared repository standards for public projects maintained by [Swir](https://github.com/Swir).**

</div>

<img width="100%" src="assets/readme-divider.svg" alt="" />

## 🧭 Purpose

`Swir/.github` is the account-level home for reusable GitHub community-health standards.

When a public SWIR repository does not provide its own matching file, GitHub can use the default stored here. This keeps project maintenance consistent while allowing every repository to override the defaults when necessary.

```text
Swir/.github
    │
    ├── Issues
    ├── Pull requests
    ├── Security
    ├── Contributing
    ├── Support
    └── Ownership
           │
           ▼
    Public SWIR repositories
           │
           └── Local project file = override
```

---

## ⚡ Included standards

| Area | Default | Purpose |
|---|---|---|
| 🐞 **Bug reports** | Structured issue form | Reproducible, actionable reports |
| ✨ **Feature requests** | Structured issue form | Clear use case and proposed improvement |
| 📚 **Documentation** | Documentation form | Missing, outdated or unclear documentation |
| 🔀 **Pull requests** | PR checklist | Focused, testable, review-ready changes |
| 🤝 **Contributing** | Contribution guide | Shared contribution expectations |
| 🛡️ **Security** | Security policy | Responsible vulnerability reporting |
| 🧰 **Support** | Support guide | Correct routing for help requests |
| 🧭 **Conduct** | Code of conduct | Constructive project spaces |
| 👤 **Ownership** | CODEOWNERS | Default ownership by `@Swir` |

---

## 🧩 Engineering baseline

| Principle | Standard |
|---|---|
| **01 · Build useful** | Start with a real use case and keep the primary workflow understandable |
| **02 · Protect working features** | Improvements should not silently remove existing behavior |
| **03 · Keep code maintainable** | Prefer readable structure, clear names and focused changes |
| **04 · Document reality** | Setup, screenshots and limitations should match the current release |
| **05 · Release cleanly** | Versioning, changelog and release notes should explain what changed |
| **06 · Brand consistently** | Icons, screenshots and repository presentation should feel intentional |
| **07 · Stay discoverable** | Use accurate descriptions, topics and Search Keywords |
| **08 · Keep secrets out** | Tokens, credentials, keys and private data never belong in commits |

---

## 🎯 Default issue intake

### `[BUG]`
Reproducible software problems with version, environment, reproduction steps, expected behavior and logs/screenshots.

### `[FEATURE]`
Concrete improvements based on a real problem or use case, including proposed behavior and alternatives where relevant.

### `[DOCS]`
Missing, outdated, confusing or incorrect documentation.

> Project-specific issue forms can replace these defaults whenever a repository needs a specialized workflow.

---

## 🏗️ New project workflow

New SWIR software can start from **[Swir-Project-Template](https://github.com/Swir/Swir-Project-Template)**.

```text
CREATE  →  BRAND  →  BUILD  →  TEST  →  RELEASE  →  EVOLVE
```

The project template includes repository structure, CI, dependency maintenance, roadmap tracking, changelog, release workflow and quality checks.

---

## 📁 Repository map

```text
.github/
├── .github/
│   ├── CODEOWNERS
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.yml
│   │   ├── documentation.yml
│   │   ├── feature_request.yml
│   │   └── config.yml
│   └── PULL_REQUEST_TEMPLATE.md
├── assets/
│   ├── readme-divider.svg
│   └── readme-hero.svg
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── SUPPORT.md
└── README.md
```

---

## 🔄 Override model

These defaults are intentionally flexible.

A repository that needs different rules can add its own version of the relevant file. The project-specific file takes precedence while the remaining shared defaults continue to apply.

---

## 🔎 Search Keywords

`github community health files` • `github issue templates` • `github pull request template` • `github security policy` • `github contributing guide` • `github codeowners` • `open source repository standards` • `software project standards` • `SWIR github`

<img width="100%" src="assets/readme-divider.svg" alt="" />

<div align="center">

### `SWIR // BUILD • RELEASE • EVOLVE`

**One standard. Many projects.**

[**← SWIR Profile**](https://github.com/Swir) · [**Project Template →**](https://github.com/Swir/Swir-Project-Template)

</div>
