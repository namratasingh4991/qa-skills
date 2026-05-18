![GitHub stars](https://img.shields.io/github/stars/namratasingh4991/qa-skills)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)](https://github.com/namratasingh4991/qa-skills/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](https://github.com/namratasingh4991/qa-skills/blob/main/CONTRIBUTING.md)

# QA Skills Marketplace: Reusable AI Workflows for Quality Assurance

> 60+ QA skills and 32 chained workflows across 8 plugins. Claude Code, Cowork, and multi-model AI systems. From test strategy to automation, performance, security, release governance, and defect orchestration.

## Start Here

Need a test strategy? → `/test-strategy`  
Building test automation? → `/automation-plan`  
Performance concerns? → `/perf-testing`  
Security validation? → `/security-test`  
Planning a release? → `/release-governance`  
Analyzing regressions? → `/regression-analysis`  

If this project helps you, ⭐ the repo.

## Why QA Skills Marketplace?

Generic AI gives you text. QA Skills Marketplace gives you structure.

Each skill encodes proven QA frameworks — test strategy, risk-based testing, automation best practices, performance benchmarking, security validation, release governance, regression intelligence, and defect orchestration — and walks you through it step by step.

The result: better quality decisions, faster releases, and fewer production issues.

## How It Works (Skills, Commands, Plugins)

**Skills** are the building blocks of the marketplace. Each skill gives Claude domain knowledge, QA frameworks, or a guided workflow for a specific testing task.

**Commands** are user-triggered workflows invoked with `/command-name`. They chain one or more skills into an end-to-end process. For example, `/test-strategy` chains test planning, risk analysis, and test case design together.

**Plugins** group related skills and commands into installable packages. Each plugin covers a QA domain — test strategy, automation, performance, security, API testing, mobile testing, data quality, and toolkit. Installing the marketplace gives you all 8 plugins with 60+ skills and 32 commands.

## Installation

### Claude Cowork (recommended for non-developers)

1. Open **Customize** (bottom-left)
2. Go to **Browse plugins** → **Personal** → **+**
3. Select **Add marketplace from GitHub**
4. Enter: `namratasingh4991/qa-skills`

All 8 plugins install automatically. You get both commands and skills.

### Claude Code (CLI)

```bash
# Step 1: Add the marketplace
claude plugin marketplace add namratasingh4991/qa-skills

# Step 2: Install individual plugins
claude plugin install qa-testing-fundamentals@qa-skills
claude plugin install qa-automation@qa-skills
claude plugin install qa-performance@qa-skills
claude plugin install qa-security@qa-skills
claude plugin install qa-api-testing@qa-skills
claude plugin install qa-mobile-testing@qa-skills
claude plugin install qa-data-quality@qa-skills
claude plugin install qa-toolkit@qa-skills
```

### Other AI assistants (skills only)

The `skills/*/SKILL.md` files follow the universal skill format and work with any tool that reads it.

| Tool | How to use | What works |
|------|-----------|----------|
| **Cursor** | Copy skill folders to `.cursor/skills/` | Skills only |
| **Codex CLI** | Copy skill folders to `.codex/skills/` | Skills only |
| **Gemini CLI** | Copy skill folders to `.gemini/skills/` | Skills only |
| **OpenCode** | Copy skill folders to `.opencode/skills/` | Skills only |
| **Windsurf** | Copy skill folders to `.windsurf/skills/` | Skills only |

---

## Available Plugins

<details>
<summary><strong>1. qa-testing-fundamentals</strong> — Test strategy, risk analysis, test case design, test planning (8 skills, 4 commands)</summary>

**Skills (8):**
- `test-strategy` — Comprehensive test strategy framework
- `risk-analysis` — Risk-based testing approach
- `test-case-design` — Design effective test cases
- `test-plan` — Create a detailed test plan
- `exploratory-testing` — Exploratory testing guidelines
- `test-estimation` — Estimate testing effort and timeline
- `test-data-strategy` — Plan test data requirements
- `test-coverage-analysis` — Measure and optimize test coverage

**Commands (4):**
- `/test-strategy` — Create a comprehensive test strategy
- `/test-plan` — Develop a detailed test plan
- `/risk-analysis` — Perform risk-based testing analysis
- `/test-coverage` — Analyze test coverage requirements

</details>

<details>
<summary><strong>2. qa-automation</strong> — Test automation frameworks, script generation, CI/CD integration (9 skills, 4 commands)</summary>

**Skills (9):**
- `automation-framework-selection` — Choose the right test automation framework
- `page-object-model` — Design using Page Object Model pattern
- `test-script-generation` — Generate automated test scripts
- `selenium-webdriver` — Selenium WebDriver best practices
- `api-automation` — API test automation
- `ci-cd-integration` — Integrate tests into CI/CD pipelines
- `flaky-test-analysis` — Identify and fix flaky tests
- `test-execution-reporting` — Generate test execution reports
- `automation-maintenance` — Maintain test automation suites

**Commands (4):**
- `/automation-plan` — Plan test automation strategy
- `/generate-tests` — Generate automated test scripts
- `/setup-ci-cd` — Integrate automation into CI/CD
- `/fix-flaky-tests` — Analyze and fix flaky tests

</details>

<details>
<summary><strong>3. qa-performance</strong> — Performance testing, load testing, optimization (7 skills, 3 commands)</summary>

**Skills (7):**
- `perf-test-strategy` — Performance testing strategy
- `load-testing-plan` — Design load testing scenarios
- `stress-testing` — Conduct stress testing
- `baseline-analysis` — Establish performance baselines
- `bottleneck-identification` — Identify performance bottlenecks
- `optimization-recommendations` — Performance optimization guidance
- `perf-monitoring` — Performance monitoring and alerting

**Commands (3):**
- `/perf-testing` — Plan performance testing
- `/load-test` — Design load testing scenarios
- `/perf-analysis` — Analyze performance metrics

</details>

<details>
<summary><strong>4. qa-security</strong> — Security testing, vulnerability assessment, OWASP (8 skills, 4 commands)</summary>

**Skills (8):**
- `security-test-strategy` — Security testing framework
- `owasp-top-10` — Test against OWASP Top 10
- `vulnerability-scanning` — Automated vulnerability scanning
- `penetration-testing` — Penetration testing approach
- `authentication-testing` — Test authentication mechanisms
- `authorization-testing` — Test authorization controls
- `data-protection` — Data protection and encryption testing
- `security-reporting` — Security issue reporting and remediation

**Commands (4):**
- `/security-test` — Plan security testing
- `/vulnerability-scan` — Identify vulnerabilities
- `/penetration-test` — Design penetration testing
- `/security-audit` — Conduct security audit

</details>

<details>
<summary><strong>5. qa-api-testing</strong> — API testing, REST/GraphQL, contract testing (7 skills, 3 commands)</summary>

**Skills (7):**
- `api-test-strategy` — API testing strategy
- `rest-api-testing` — REST API testing approach
- `graphql-testing` — GraphQL API testing
- `contract-testing` — Contract testing between services
- `api-validation` — Validate API responses and schemas
- `api-performance` — API performance testing
- `api-security` — API security testing

**Commands (3):**
- `/api-testing` — Plan API testing strategy
- `/contract-test` — Design contract testing
- `/api-validation` — Validate API functionality

</details>

<details>
<summary><strong>6. qa-mobile-testing</strong> — Mobile app testing, device compatibility, UX testing (7 skills, 3 commands)</summary>

**Skills (7):**
- `mobile-test-strategy` — Mobile testing strategy
- `device-compatibility` — Test across devices and OS versions
- `network-conditions` — Test under different network conditions
- `mobile-usability` — Mobile UX/usability testing
- `app-permissions` — Test app permissions and privacy
- `mobile-performance` — Mobile-specific performance testing
- `mobile-automation` — Mobile test automation tools and frameworks

**Commands (3):**
- `/mobile-testing` — Plan mobile testing strategy
- `/device-compatibility` — Plan compatibility testing
- `/mobile-usability` — Evaluate mobile UX

</details>

<details>
<summary><strong>7. qa-data-quality</strong> — Data validation, ETL testing, analytics testing (6 skills, 3 commands)</summary>

**Skills (6):**
- `data-validation-strategy` — Data quality validation approach
- `etl-testing` — ETL pipeline testing
- `data-integrity` — Test data integrity and consistency
- `analytics-validation` — Validate analytics data
- `database-testing` — Database testing best practices
- `data-quality-metrics` — Define data quality KPIs

**Commands (3):**
- `/data-validation` — Plan data quality testing
- `/etl-testing` — Test ETL pipelines
- `/analytics-validation` — Validate analytics data

</details>

<details>
<summary><strong>8. qa-release-governance</strong> — Release governance, regression intelligence, defect orchestration (8 skills, 4 commands)</summary>

**Skills (8):**
- `release-governance` — Release governance framework
- `regression-testing-strategy` — Regression test strategy
- `regression-pack-creation` — Create regression test packs
- `defect-management` — Defect tracking and management
- `defect-severity-classification` — Classify defect severity
- `release-readiness` — Assess release readiness
- `hotfix-strategy` — Plan hotfix testing
- `post-release-validation` — Post-release testing and monitoring

**Commands (4):**
- `/regression-analysis` — Plan regression testing
- `/release-governance` — Assess release readiness
- `/defect-triage` — Triage and prioritize defects
- `/post-release` — Plan post-release validation

</details>

---

## About

This marketplace evolves with QA practice and AI capabilities.

Selected skills based on industry best practices from:
- ISTQB (International Software Testing Qualifications Board)
- OWASP (Open Web Application Security Project)
- Ministry of Testing
- Google Testing Blog
- James Bach & Michael Bolton (Context-Driven Testing)
- Lisa Crispin & Janet Gregory (Agile Testing)

Curated by Namrata Singh for QA professionals and AI-augmented testing teams.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

MIT — see [LICENSE](LICENSE).
