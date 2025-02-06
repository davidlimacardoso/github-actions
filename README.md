# GitHub Actions Repository

![GitHub Actions](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-MIT-blue)
![Contributors](https://img.shields.io/badge/contributors-1-orange)
![Issues](https://img.shields.io/badge/issues-0-brightgreen)

This repository contains a collection of GitHub Actions, sources, and scripts that belong to other action repositories. It serves as a centralized repository to facilitate the reuse and sharing of actions across different projects.

## Purpose

The main purpose of this repository is to provide a set of actions and scripts that can be utilized in other GitHub repositories, promoting efficiency and standardization in CI/CD workflows.

## Repository Structure
> [!NOTE]
> - **Actions**: Code and configurations for each GitHub Action.
> - **Scripts**: Auxiliary scripts that can be used by these actions.
> - **Examples**: Sample workflows demonstrating how to use the actions.

## How to Use

To use an action from this repository in your own project, add the following to your `.github/workflows/your-workflow.yml` file:

```yaml
steps:
  - name: Example Action
    uses: your-username/github-actions-repo@main
    with:
      # Pass parameters here
```

Replace your-username/github-actions-repo with the name of your GitHub repository and main with the desired branch.

## Contribution Guidelines
Contributions are welcome! Feel free to open an issue or submit a pull request. Please ensure that your contributions adhere to the following guidelines:

- Follow the existing code style.
- Write clear and concise commit messages.
- Update documentation as necessary.

## License
> [!CAUTION]
> This project is licensed under the MIT License.

## Contact
> [!IMPORTANT]
> For any inquiries or suggestions, please reach out via GitHub [issues](https://github.com/davidlimacardoso/github-actions/issues).

### Badges

> [!NOTE]
> - **Build Status**: You can use a badge to indicate the build status of your actions.
> - **License**: Indicates the license type.
> - **Contributors**: Shows the number of contributors.
> - **Issues**: Displays the number of open issues.

### Customization

- Replace `your-username/github-actions-repo` with your actual repository name.
- Update the badge links with the correct URLs for your project.
- Feel free to add more badges as needed, such as for coverage, dependencies, etc.

This README template provides a clear overview of your project and encourages collaboration!
