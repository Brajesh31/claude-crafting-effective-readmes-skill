# README Authoring Workflow

## 1. Collect facts before writing

Inspect the repository and identify its purpose, actual entry points, package manager, supported runtime, installation method, commands, configuration, tests, deployment process, and license status. Do not infer these from folder names.

## 2. Identify the audience

Choose the primary reader: end user, API consumer, contributor, internal teammate, operator, or future maintainer. A README can serve several audiences, but it should state the primary purpose first.

## 3. Draft in reader order

Recommended sequence:

- Project name and one-sentence description
- Status or compatibility notes, if relevant
- Demonstration or screenshot, if it adds value
- Main benefits and use cases
- Prerequisites
- Installation
- Quickstart
- Common tasks and configuration
- Troubleshooting
- Contributing and support
- License and acknowledgements, when applicable

## 4. Verify commands

Run each command in a clean environment where feasible. Mark placeholders clearly. Never invent expected output, environment variables, or supported versions.

## 5. Review the prose

Replace unexplained acronyms, generic claims, and long paragraphs. Use active voice and imperative steps. Keep one purpose per section.

## 6. Final checks

- Links resolve.
- Code fences identify their language.
- Shell commands match the package manager in the repository.
- Environment-variable names match the implementation.
- Screenshots are current and accessible.
- License and contribution instructions are accurate.
- No secrets, personal data, or internal-only endpoints are exposed.
