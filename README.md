# gh-actions

## References

· https://github.com/actions/starter-workflows - 

· https://github.com/actions# gh-actions

This repository contains workflows and actions for automating tasks using GitHub Actions. It includes workflows for debugging, validating branches, and deploying releases.

## Workflows

### 1. **Release Workflow**
- **File:** [.github/workflows/release.yml](.github/workflows/release.yml)
- **Description:** Handles deployment releases. It allows users to select a release branch and environment (production, staging, or development) via workflow dispatch.

### 2. **Debug Workflow**
- **File:** [.github/workflows/actions/debug.yml](.github/workflows/actions/debug.yml)
- **Description:** Displays variables, secrets, and deployment details for debugging purposes.

### 3. **Validate Workflow**
- **File:** [.github/workflows/actions/validate.yml](.github/workflows/actions/validate.yml)
- **Description:** Validates that the release branch name starts with `release/`. Outputs validation results and provides error messages if the branch name is invalid.

## References

Here are some useful resources and repositories for GitHub Actions:

- [GitHub Actions Starter Workflows](https://github.com/actions/starter-workflows) - A collection of starter workflows for common use cases.
- [GitHub Actions Official Repository](https://github.com/actions) - Official GitHub Actions maintained by GitHub.
- [Awesome Actions](https://github.com/sdras/awesome-actions) - A curated list of awesome GitHub Actions.
- [Actions Toolkit](https://github.com/actions/toolkit) - A toolkit for building custom GitHub Actions.
- [GitHub Actions Marketplace](https://github.com/marketplace?type=actions) - Explore and use actions created by the community.

## Getting Started

To use the workflows in this repository:
1. Clone the repository.
2. Customize the workflows as needed.
3. Push changes to your repository and trigger workflows via GitHub Actions.

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests to improve the workflows or add new ones.

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.