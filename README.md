# CodeBuild CodeBreach Actors Lab

Intentionally vulnerable training repository for AWS CodeBuild webhook filter misconfigurations.

## Safety note
This repository is for training only.

⚠️ If two people attempt to obtain a reverse shell at the same time, sessions may conflict or overlap, causing confusion.

## PR Cleanup Policy

This repository is reset automatically by an hourly GitHub Action:

- **Non-seed PRs** (regular student PRs) are closed every hour.
- **Seed PRs** labeled `lab-seed-pr` are kept open for discoverability and only closed after they are at least **12 hours** old.

The seed PR is used so students can quickly find a successful CodeBuild check URL directly from the repository UI.
