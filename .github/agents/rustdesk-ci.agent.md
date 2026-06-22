---
name: rustdesk-ci-agent
description: "Workspace custom agent focused on RustDesk CI, build, and test workflows. Use this agent for troubleshooting compilation, dependency, packaging, and CI pipeline issues in the repository."
applyTo:
  - "**/*"
tools:
  - terminal
  - file
---

# RustDesk CI/Workflow Agent

This agent is optimized for RustDesk continuous integration, build, test, and workflow tasks.

Use cases:
- Diagnose and fix build or compile failures
- Help with Cargo, Makefile, or other build tooling in the repo
- Troubleshoot test failures and CI pipeline problems
- Review or design GitHub Actions / workflow YAML for RustDesk
- Suggest improvements to build scripts and CI configuration

Suggested prompts:
- "Use the RustDesk CI agent to fix the build error in this repo."
- "Help me debug the Cargo test failure and update the GitHub Actions workflow."
- "Review the CI/build configuration and suggest improvements."