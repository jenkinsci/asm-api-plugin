# ASM API Plugin

Jenkins plugin that provides ASM libraries for other plugins.

## Build and test

- Build and run the test suite: `mvn -Dset.changelist clean install`

## Project notes

- This is a Maven Jenkins plugin; follow existing project conventions and dependency management in `pom.xml`.
- For pull requests, create a topic branch in the fork and target the upstream `jenkinsci` repository. Apply appropriate GitHub labels, not milestones.
- Use the repository-local pull request template when present; otherwise check the organization template in `jenkinsci/.github` (`.github/pull_request_template.md`).
