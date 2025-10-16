# Automated Code Quality Checker (CI/CD)

This project automatically checks Python code quality using **GitHub Actions** and **Pylint**.

## Features
- Runs Pylint automatically on every push or pull request.
- Ensures your code follows standard quality rules.
- Fails the build if code quality drops.

## How It Works
1. GitHub Actions workflow runs whenever you push code.
2. It installs dependencies and runs `pylint main.py`.
3. If issues are found, the workflow fails and shows the error report.

## Commands
Run locally:
