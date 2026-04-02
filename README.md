# ScanClusive GitHub Action - Example

This repository demonstrates how to integrate [ScanClusive](https://scanclusive.com) accessibility scanning into your GitHub Actions workflow.

![Accessibility](https://scanclusive.com/api/badges/YOUR_PROJECT_ID)

## What this example shows

- Running a WCAG scan on every push and PR
- Setting a compliance threshold (90%)
- Failing the pipeline on critical violations
- Uploading scan results as artifacts for trend tracking
- Posting scan results as PR comments
- Weekly scheduled scans

## Setup

1. Create a ScanClusive account and project at [scanclusive.com](https://scanclusive.com)
2. Generate an API key in Settings > API Keys
3. Add the following to your repository:
   - **Secret**: `SCANCLUSIVE_API_KEY` -your API key
   - **Variable**: `SCANCLUSIVE_PROJECT_ID` -your project ID
4. Copy `.github/workflows/accessibility.yml` to your repository

## License

MIT
