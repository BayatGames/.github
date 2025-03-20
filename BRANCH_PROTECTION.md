# Branch Protection Rules

This document outlines the recommended branch protection configurations for repositories within the Bayat Games organization. These settings help maintain code quality, security, and consistency across our development workflow.

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
  - Ensures all discussion comments in the PR are addressed before merging

- **Require signed commits**
  - All commits must be cryptographically signed to verify author identity

- **Require linear history**
  - Prevents merge commits, ensuring a clean, linear git history for better readability

- **Include administrators**
  - Apply these rules to repository administrators without exceptions

- **Allow force pushes**
  - Disallow force pushes to protected branches to prevent history loss

- **Allow deletions**
  - Prevent deletion of the protected branch to maintain integrity

## Implementation Instructions

To implement these branch protection rules:

1. Navigate to your repository settings
2. Select "Branches" in the left sidebar
3. Under "Branch protection rules", click "Add rule"
4. Enter the branch name pattern (e.g., `main` or `master`)
5. Configure the settings according to the recommendations above
6. Click "Create" or "Save changes" to apply the rules

## Recommended Development Workflow

We recommend following a feature branch workflow:

1. Create a new branch from `main` for each feature or bug fix
2. Make your changes in the feature branch
3. Open a pull request to merge your changes into `main`
4. Request code reviews and address any feedback
5. Once approved and all checks pass, merge your PR

This workflow ensures that the main branch remains stable and production-ready at all times while enabling collaborative development.
