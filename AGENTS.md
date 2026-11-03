# Agent Instructions & Workflow Guidelines

## Verification & Deployment Workflow
- **Commit and Push After Every Update**: Always stage, commit, and push immediately after completing any code or configuration change in this repository so the user can verify and inspect live deployments.
- **Selective Staging**: Stage only intentional changes (`git add <file>`), avoiding scratch scripts, temporary files, and local logs.
- **Commit Messages**: Use clean, descriptive Conventional Commit messages (e.g., `fix:`, `feat:`, `chore:`).
