# Branch Protection Rules

This document outlines the recommended branch protection rules for repositories in this organization. These settings help ensure code quality and maintain a consistent workflow.

## Recommended Branch Protection Settings

### Main Branch (`main` or `master`)

- **Require pull request reviews before merging**
  - Required approving reviews: 1
  - Dismiss stale pull request approvals when new commits are pushed
  - Require review from Code Owners

- **Require status checks to pass before merging**
  - Require branches to be up to date before merging
  - Required status checks:
    - Continuous integration tests
    - Linting checks
    - Build verifications

- **Require conversation resolution before merging**
  - Ensures all comments in the PR are addressed

- **Require signed commits**
  - All commits must be signed to verify author identity

- **Require linear history**
  - Prevents merge commits, ensuring a clean, linear git history

- **Include administrators**
  - Apply these rules to repository administrators

- **Allow force pushes**
  - Disallow force pushes to protected branches

- **Allow deletions**
  - Prevent deletion of the protected branch

## Setting Up Branch Protection

To set up these branch protection rules:

1. Go to your repository settings
2. Click on "Branches" in the sidebar
3. Under "Branch protection rules", click "Add rule"
4. Enter the branch name pattern (e.g., `main` or `master`)
5. Configure the settings as recommended above
6. Click "Create" or "Save changes"

## Development Workflow

We recommend using a feature branch workflow:

1. Create a new branch from `main` for each feature or bug fix
2. Make changes in your branch
3. Open a pull request to merge your changes back to `main`
4. Request reviews and address feedback
5. Once approved and all checks pass, merge your PR

This protects the main branch while allowing collaborative development.
