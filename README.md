# Sample Python Project

A simple Python project with GitHub Actions workflow for daily flake8 analysis and Slack reporting.

## Setup

```bash
pip install -r requirements.txt
```

## GitHub Actions Workflow

This project includes a GitHub Actions workflow that:
- Runs daily at 7PM
- Analyzes code with flake8
- Reports results to Slack

JUST SET A `SLACK_WEBHOOK_URL` secret
