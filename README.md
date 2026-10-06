# Gitleaks Pipeline Demo

A small practice repository for learning how Gitleaks will work inside GitHub Actions.

## Structure

- `src/` - sample application files
- `docs/` - notes/documentation
- `.github/workflows/` - GitHub Actions workflows will go here

## Current state

The GitHub Actions pipeline is intentionally NOT included yet.

We will add the Gitleaks workflow manually in the next step.

## Goal

Developer push -> GitHub repository -> GitHub Actions runner -> Gitleaks -> Scan repository -> PASS / FAIL -> Logs / artifacts

Use only fake/example secrets for this demo. Never commit real credentials.
