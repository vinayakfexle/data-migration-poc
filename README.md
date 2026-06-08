# Data Migration POC

This repository contains a proof of concept for data migration workflows with timeout handling.

## Workflows

- **timeout-test.yml**: Demonstrates GitHub Actions workflow with 3 sequential jobs, 1-minute timeout per job, and continue-on-error handling to ensure jobs run even if previous jobs timeout or are cancelled.
