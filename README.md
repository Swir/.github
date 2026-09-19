<div align="center">

# ⚡ SWIR // GitHub Standards

### Shared engineering & community baseline for the SWIR ecosystem

**ISSUES • PULL REQUESTS • SECURITY • SUPPORT • DOCUMENTATION • RELEASE QUALITY**

![Standard](https://img.shields.io/badge/SWIR-STANDARD-02050A?style=for-the-badge&logo=github&logoColor=62E5FF)
![Community](https://img.shields.io/badge/COMMUNITY-READY-02050A?style=for-the-badge&logo=githubsponsors&logoColor=62E5FF)
![Security](https://img.shields.io/badge/SECURITY-BASELINE-02050A?style=for-the-badge&logo=githubactions&logoColor=62E5FF)
![Maintained](https://img.shields.io/badge/STATUS-MAINTAINED-02050A?style=for-the-badge&logo=git&logoColor=62E5FF)

[![Author](https://img.shields.io/badge/Author-Swir-0088FF?style=flat-square&logo=github)](https://github.com/Swir)
[![Template](https://img.shields.io/badge/Project_Template-SWIR-0088FF?style=flat-square&logo=github)](https://github.com/Swir/Swir-Project-Template)

</div>

<img width="100%" src="https://raw.githubusercontent.com/Swir/Swir/main/assets/power-divider-v4.svg" alt="SWIR electric divider" />

## 🧭 What this repository is

**`Swir/.github` is the control layer for shared repository standards across the SWIR account.**

When a public SWIR repository does not provide its own community-health file, GitHub can fall back to the matching default stored here. That keeps projects consistent without copying the same maintenance files into every repository.

```text
SWIR/.github
     │
     ├── Issue standards
     ├── Pull request standard
     ├── Security policy
     ├── Contribution rules
     ├── Support guidance
     └── Code ownership
            │
            ▼
     Public SWIR repositories
            │
            └── Project-specific file = local override
```

---

## ⚡ Included standards

| Area | Default | Purpose |
|---|---|---|
| 🐞 **Bug reports** | Structured issue form | Reproducible, useful bug reports |
| ✨ **Feature requests** | Structured issue form | Clear problem → proposed improvement |
| 📚 **Documentation** | Documentation form | Report missing, outdated or unclear docs |
| 🔀 **Pull requests** | PR checklist | Focused, testable and review-ready changes |
| 🤝 **Contributing** | Contribution guide | Consistent expectations for contributors |
| 🛡️ **Security** | Security policy | Responsible vulnerability reporting |
| 🧰 **Support** | Support guide | Route help requests to the right place |
| 🧭 **Conduct** | Code of conduct | Keep project spaces constructive |
| 👤 **Ownership** | CODEOWNERS | Default ownership by `@Swir` |

---

## 🧩 SWIR engineering baseline

| Principle | Standard |
|---|---|
| **01 · BUILD USEFUL** | Start with a real use case and make the main flow understandable |
| **02 · PROTECT WORKING FEATURES** | Improvements should not silently remove or break existing behavior |
| **03 · KEEP CODE MAINTAINABLE** | Prefer readable structure, clear names and focused changes |
| **04 · DOCUMENT REALITY** | README, setup steps and limitations should match the current release |
| **05 · RELEASE CLEANLY** | Versioning, changelog and release notes should explain what changed |
| **06 · BRAND CONSISTENTLY** | Icons, screenshots and repository presentation should look intentional |
| **07 · STAY DISCOVERABLE** | Use accurate descriptions, topics and Search Keywords |
| **08 · KEEP SECRETS OUT** | Tokens, credentials, keys and private data never belong in commits |

---

## 🎯 Default issue intake

### `[BUG]`
For reproducible problems. Reports request the version, operating system, reproduction steps, expected behavior and logs/screenshots.

### `[FEATURE]`
For meaningful improvements. Requests focus on the user problem, proposed solution, alternatives and context.

### `[DOCS]`
For documentation that is missing, outdated, confusing or incorrect.

> Individual repositories can provide their own issue forms whenever a project needs a specialized workflow.

---

## 🏗️ New project workflow

For new software, start from **[Swir-Project-Template](https://github.com/Swir/Swir-Project-Template)**.

```text
CREATE  →  BRAND  →  BUILD  →  TEST  →  RELEASE  →  EVOLVE
```

The template already includes repository structure, CI, dependency updates, roadmap tracking, changelog, release workflow and quality checklists.

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
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── SECURITY.md
├── SUPPORT.md
└── README.md
```

---

## 🔄 Override model

Defaults are intentionally **not restrictive**.

If a repository needs different rules, simply add a project-specific version of the relevant file. The local project file takes precedence, while the rest of the account-wide defaults remain available.

---

## 🔎 Search Keywords

`github community health files` • `github issue templates` • `github pull request template` • `github security policy` • `github contributing guide` • `github codeowners` • `open source repository standards` • `software project standards` • `SWIR github`

---

<img width="100%" src="https://raw.githubusercontent.com/Swir/Swir/main/assets/power-divider-v4.svg" alt="SWIR electric divider" />

<div align="center">

### `SWIR // BUILD • RELEASE • EVOLVE`

**One standard. Many projects. Less chaos.**

[**← SWIR Profile**](https://github.com/Swir) · [**Project Template →**](https://github.com/Swir/Swir-Project-Template)

</div>
