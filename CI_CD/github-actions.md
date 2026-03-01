# GitHub Actions Notes

## Purpose

Use GitHub Actions to automate build/test/deploy workflows on code push and pull requests.

## Basic Workflow Structure

1. Trigger: `on` (`push`, `pull_request`, manual dispatch)
2. Runner: `runs-on` (for example `ubuntu-latest`)
3. Steps:
   - Checkout repository
   - Setup runtime
   - Install dependencies
   - Run tests/build
   - Deploy (optional)

## Example Workflow (Node App)

```yaml
name: Node CI

on:
  push:
    branches: [main]
  pull_request:
    branches: [main]

jobs:
  build-and-test:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v4

      - name: Setup Node
        uses: actions/setup-node@v4
        with:
          node-version: 18

      - name: Install dependencies
        run: npm ci
        working-directory: Projects/Node_project

      - name: Start check
        run: npm run start --if-present
        working-directory: Projects/Node_project
```

## Notes For This Repository

- Frontend deployment practice is referenced in `Day_21_githublink(jenk..)` notes.
- No workflow file is committed yet under `.github/workflows/`.
- Recommended next file path for live pipeline:
  - `.github/workflows/node-ci.yml`
