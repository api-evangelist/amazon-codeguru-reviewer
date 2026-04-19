# Amazon CodeGuru Reviewer

Amazon CodeGuru Reviewer is an automated code review service that uses machine learning and AWS best practices to identify security vulnerabilities, bugs, and hard-to-detect issues in your Java and Python code. It provides intelligent recommendations to help improve code quality and find defects that may be difficult to detect through manual code reviews.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/amazon-codeguru-reviewer/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Amazon, AWS, Code Review, Security, DevOps, Machine Learning, Developer Tools

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### Amazon CodeGuru Reviewer API

The Amazon CodeGuru Reviewer REST API.

**Human URL:** [https://docs.aws.amazon.com/codeguru/latest/reviewer-api/Welcome.html](https://docs.aws.amazon.com/codeguru/latest/reviewer-api/Welcome.html)

#### Tags:

 - Amazon, AWS, Code Review, Security, DevOps

#### Properties

- [Documentation](https://docs.aws.amazon.com/codegurureviewer/)
- [APIReference](https://docs.aws.amazon.com/codeguru/latest/reviewer-api/Welcome.html)
- [OpenAPI](openapi/amazon-codeguru-reviewer-openapi-original.yaml)

## Common Properties

- [GettingStarted](https://docs.aws.amazon.com/codeguru/reviewer)
- [Pricing](https://aws.amazon.com/codegurureviewer/pricing/)
- [Console](https://console.aws.amazon.com/codegurureviewer/)
- [Portal](https://aws.amazon.com/codegurureviewer/)
- [Documentation](https://docs.aws.amazon.com/codegurureviewer/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [Blog](https://aws.amazon.com/blogs/devops/)
- [SignUp](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html)
- [GitHubOrganization](https://github.com/aws)

## Features

| Name | Description |
|------|-------------|
| Automated Code Review | Automatically analyze code changes in pull requests and provide recommendations for bugs, security vulnerabilities, and  |
| Security Analysis | Detect security vulnerabilities including OWASP Top 10, input validation issues, encryption problems, and AWS API securi |
| Java and Python Support | Analyze Java and Python code with language-specific recommendations based on AWS best practices. |
| Repository Association | Connect CodeGuru Reviewer to GitHub, GitHub Enterprise, Bitbucket, CodeCommit, and S3 repositories. |
| Pull Request Integration | Automatically trigger code reviews on new pull requests and post recommendations as inline comments. |

## Use Cases

| Name | Description |
|------|-------------|
| Security Vulnerability Detection | Automatically detect security issues in code changes before they reach production, reducing security review burden on de |
| Automated Code Quality Enforcement | Enforce code quality standards across the organization with consistent, automated review feedback on every pull request. |
| Developer Productivity | Help developers identify and fix common coding errors and anti-patterns earlier in the development cycle. |

## Integrations

| Name | Description |
|------|-------------|
| GitHub | Associate GitHub repositories for automated code reviews on pull requests. |
| GitHub Enterprise | Connect self-hosted GitHub Enterprise repositories for automated code review. |
| Bitbucket | Integrate with Bitbucket repositories for pull request code reviews. |
| AWS CodeCommit | Analyze CodeCommit repositories and pull requests natively. |
| Amazon S3 | Associate S3 buckets for one-time code analysis. |
| Amazon CodeGuru Profiler | Combine code review recommendations with profiling insights for comprehensive code quality. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [amazon-codeguru-reviewer-openapi-original](openapi/amazon-codeguru-reviewer-openapi-original.yaml)

### JSON Schema

122 JSON Schema files generated from the OpenAPI specification.

- [amazon-codeguru-reviewer-analysis-type-schema](json-schema/amazon-codeguru-reviewer-analysis-type-schema.json)
- [amazon-codeguru-reviewer-analysis-types-schema](json-schema/amazon-codeguru-reviewer-analysis-types-schema.json)
- [amazon-codeguru-reviewer-arn-schema](json-schema/amazon-codeguru-reviewer-arn-schema.json)
- [amazon-codeguru-reviewer-associate-repository-request-schema](json-schema/amazon-codeguru-reviewer-associate-repository-request-schema.json)
- [amazon-codeguru-reviewer-associate-repository-response-schema](json-schema/amazon-codeguru-reviewer-associate-repository-response-schema.json)
- ...and 117 more in [json-schema/](json-schema/)

### JSON Structure

122 JSON Structure files in [json-structure/](json-structure/).

### JSON-LD

- [amazon-codeguru-reviewer-context](json-ld/amazon-codeguru-reviewer-context.jsonld)

### Examples

122 example JSON files in [examples/](examples/).

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [codegurureviewer](capabilities/shared/codegurureviewer.yaml) — 14 operations

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon CodeGuru Reviewer Automated Code Review](capabilities/amazon-codeguru-reviewer-code-review.yaml) | codegurureviewer | 8 | DevOps Engineer |

## Vocabulary

- [amazon-codeguru-reviewer-vocabulary](vocabulary/amazon-codeguru-reviewer-vocabulary.yaml) — Unified taxonomy mapping 6 resources, 5 actions, 1 workflows, and 3 personas

## Rules

- [amazon-codeguru-reviewer-spectral-rules](rules/amazon-codeguru-reviewer-spectral-rules.yml) — 10 rules enforcing Amazon CodeGuru Reviewer API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
