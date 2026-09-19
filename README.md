<div align="center">

<img width="100%" src="assets/readme-hero.svg" alt="SWIR GitHub Standards — one foundation for a consistent project experience" />

<br>

**Shared standards for better contributions, clearer support and reliable releases.**

Issues &nbsp;·&nbsp; Pull requests &nbsp;·&nbsp; Security &nbsp;·&nbsp; Project quality

[**Contribution guide**](CONTRIBUTING.md) · [**Security policy**](SECURITY.md) · [**Start a project →**](https://github.com/Swir/Swir-Project-Template)

[Highlights](#highlights) · [Quick Start](#quick-start) · [Engineering baseline](#engineering-baseline) · [Override model](#override-model)

</div>

<img width="100%" src="assets/readme-divider.svg" alt="" />

## What is SWIR GitHub Standards?

[Swir/.github](https://github.com/Swir/.github) is the shared home for GitHub community standards across [SWIR projects](https://github.com/Swir). It gives contributors a familiar way to report problems, propose changes, ask for help and work with maintainers.

GitHub uses the supported defaults here when a repository owned by Swir has no matching local file. Individual projects can tailor those defaults to their needs. See the [override model](#override-model) for the scope and exceptions.

## Highlights

| Standard | What it provides |
|---|---|
| **Bug reports** | A [structured form](.github/ISSUE_TEMPLATE/bug_report.yml) for the version, environment, reproduction steps, expected behavior and logs or screenshots. |
| **Feature requests** | A [proposal form](.github/ISSUE_TEMPLATE/feature_request.yml) that connects a real use case to an improvement and relevant alternatives. |
| **Documentation reports** | A [dedicated form](.github/ISSUE_TEMPLATE/documentation.yml) for missing, outdated, confusing or incorrect documentation. |
| **Pull requests** | A [review checklist](.github/PULL_REQUEST_TEMPLATE.md) for focused changes with testing and compatibility notes. |
| **Contributing** | [Shared expectations](CONTRIBUTING.md) for readable code, useful context and preservation of working features. |
| **Security** | A [reporting policy](SECURITY.md) for responsible vulnerability disclosure. |
| **Support** | A [support guide](SUPPORT.md) that helps route questions and reports to the right place. |
| **Community conduct** | A [code of conduct](CODE_OF_CONDUCT.md) for constructive project spaces. |
| **Repository ownership** | [CODEOWNERS](.github/CODEOWNERS) assigns this repository to `@Swir`; other projects configure their own ownership. |

## Quick Start

### Contribute to an existing project

1. Check that project's README, documentation, releases and existing issues.
2. Use its **New issue** page for a `[BUG]`, `[FEATURE]` or `[DOCS]` report, following the available forms.
3. Read the [contribution guide](CONTRIBUTING.md) before preparing a change and use the [PR checklist](.github/PULL_REQUEST_TEMPLATE.md) to make it reviewable.

For help, follow the [support guide](SUPPORT.md). For vulnerabilities, follow the [security policy](SECURITY.md) and use the affected project's private reporting channel when available.

### Start a new project

Create a repository from **[Swir-Project-Template](https://github.com/Swir/Swir-Project-Template)**, then complete its [setup checklist](https://github.com/Swir/Swir-Project-Template/blob/main/TEMPLATE_SETUP.md).

The template supplies the project structure, CI, weekly Dependabot updates, roadmap, changelog, quality checklist and manual release workflow. These shared standards provide the contribution and community guidance around it.

## Engineering baseline

| Principle | What it means in practice |
|---|---|
| **Build useful** | Begin with a real use case and keep the main workflow understandable. |
| **Protect working features** | Preserve existing behavior when improving the product. |
| **Keep code maintainable** | Use clear names, readable structure and focused changes. |
| **Document reality** | Keep setup instructions, screenshots and limitations aligned with the current release. |
| **Release cleanly** | Make versions, changelogs and release notes explain what changed. |
| **Brand consistently** | Give icons, screenshots and repository presentation a coherent SWIR identity. |
| **Stay discoverable** | Write accurate descriptions, repository topics and Search Keywords. |
| **Keep secrets out** | Never commit tokens, credentials, private keys or personal data. |

## Override model

**Shared where useful. Specific where needed.**

A project's own supported community file takes precedence over the corresponding shared default. GitHub displays inherited guidance without copying it into the project's checkout. A local `.github/ISSUE_TEMPLATE` configuration replaces the shared issue-template set as a whole. See [GitHub's default community file rules](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file).

[CODEOWNERS is configured per repository](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners). CI, Dependabot and release workflows also live in each project; the [project template](https://github.com/Swir/Swir-Project-Template) supplies their starting configuration.

## Repository map

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

## Search Keywords

`github community health files` · `github issue templates` · `github pull request template` · `github security policy` · `github contributing guide` · `github codeowners` · `open source repository standards` · `software project standards` · `SWIR github`

<img width="100%" src="assets/readme-divider.svg" alt="" />

<div align="center">

**SWIR · BUILD · RELEASE · EVOLVE**

One standard. Many projects.

[**← SWIR Profile**](https://github.com/Swir) · [**Project Template →**](https://github.com/Swir/Swir-Project-Template)

</div>
