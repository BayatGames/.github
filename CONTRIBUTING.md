# Contributing

> This project has a [code of conduct][coc].
> By interacting with this repository, organization, or community you agree to
> abide by its terms.

Hi!  👋
We're excited that you're interested in contributing!
Take a moment to read the following guidelines.
And thanks for contributing to **Bayat Open Source**!  👏👌✨

## Contents

*   [Ecosystem](#ecosystem)
*   [Contributions](#contributions)
    *   [Improve documentation](#improve-documentation)
    *   [Improve issues](#improve-issues)
    *   [Give feedback on issues](#give-feedback-on-issues)
    *   [Write code](#write-code)
*   [Development Workflow](#development-workflow)
    *   [Branching Strategy](#branching-strategy)
    *   [Commit Guidelines](#commit-guidelines)
    *   [Pull Request Process](#pull-request-process)
*   [Coding Standards](#coding-standards)
*   [Support](#support)
*   [Submitting an issue](#submitting-an-issue)
*   [Submitting a pull request](#submitting-a-pull-request)
*   [Resources](#resources)
*   [License](#license)

## Ecosystem

The collective ([BayatGames][]) consists of several separate
projects for the gaming and game development industry.

## Contributions

There's several ways to contribute, not just by writing code.

### Improve documentation

As a user of this project you're perfect for helping us improve our docs.
Typo corrections, error fixes, better explanations, new examples, etcetera.
Anything!

### Improve issues

Some issues lack information, aren't reproducible, or are just incorrect.
Help make them easier to resolve.

### Give feedback on issues

We're always looking for more opinions on discussions in the issue tracker.

### Write code

Code contributions are very welcome.
It's often good to first create an issue to report a bug or suggest a new
feature before creating a pull request to prevent you from doing unnecessary
work.

## Development Workflow

Our development process is designed to be straightforward and transparent. Below is an outline of how we work.

### Branching Strategy

We follow a feature branch workflow:

1. Create a new branch from `main` for each feature, fix, or improvement
2. Name your branch with a descriptive prefix:
   * `feature/` for new features
   * `fix/` for bug fixes
   * `docs/` for documentation changes
   * `refactor/` for code refactoring
   * `test/` for changes to tests
   * `chore/` for maintenance tasks

Example: `feature/add-new-component` or `fix/resolve-memory-leak`

### Commit Guidelines

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>(<scope>): <description>

[optional body]

[optional footer(s)]
```

Types include: feat, fix, docs, style, refactor, test, chore, etc.

Examples:
```
feat(ui): add button component
fix(api): resolve authentication issue
docs(readme): update installation instructions
```

### Pull Request Process

1. Ensure your branch is up to date with the latest changes from `main`
2. Update documentation if necessary
3. Add tests for new features
4. Run all tests locally before submitting
5. Fill out the PR template completely
6. Request reviews from maintainers
7. Address review feedback promptly

## Coding Standards

- Follow the established code style and patterns in the repository
- Write meaningful comments for complex logic
- Include appropriate error handling
- Write tests for new functionality
- Document public APIs
- Keep accessibility in mind when developing UI components

## Support

See [`SUPPORT.md`][support] on how to get help.

## Submitting an issue

*   The issue tracker is for issues.
    See [`SUPPORT.md`][support] on how to get help.
*   Search the issue tracker (including closed issues) before opening a new
    issue
*   Ensure you're using the latest version of projects
*   Use a clear and descriptive title
*   Include as much information as possible: steps to reproduce the issue,
    error message, version, operating system, etcetera
*   The more time you put into an issue, the more we will
*   The best issue report is a failing test or demo proving it

## Submitting a pull request

*   Non-trivial changes are often best discussed in an issue first, to prevent
    you from doing unnecessary work
*   For ambitious tasks, you should try to get your work in front of the
    community for feedback as soon as possible
*   New features should be accompanied with tests and documentation
*   Don't include unrelated changes
*   Test before submitting code
*   Write a convincing description of why we should land your pull request:
    it's your job to convince us

## Resources

*   [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
*   [Making your first contribution](https://medium.com/@vadimdemedes/making-your-first-contribution-de6576ddb190)
*   [Using Pull Requests](https://help.github.com/articles/about-pull-requests/)
*   [GitHub Help](https://help.github.com)
*   [Conventional Commits](https://www.conventionalcommits.org/)
*   [All Contributors Specification](https://allcontributors.org/)
*   [Keep a Changelog](https://keepachangelog.com/)
*   [Semantic Versioning](https://semver.org/)

## License

Unity assets are licensed under [Unity Asset Store Terms and EULA][license]

All rights reserved © [Bayat][author]

---

Made with ❤️ by [Bayat][author]

<!-- Definitions -->

[license]: https://unity3d.com/legal/as_terms

[author]: https://bayat.io

[coc]: CODE_OF_CONDUCT.md

[bayatgames]: https://github.com/BayatGames

[support]: SUPPORT.md
