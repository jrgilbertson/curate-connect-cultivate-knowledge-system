# Contributing to Lifelong Learning System Template

Thank you for considering contributing to this project! This document outlines the process for contributing and releasing new versions.

## Development Process

1. **Fork the Repository**: Start by forking the repository and then clone it locally.
2. **Create a Feature Branch**: Create a branch for your feature or bugfix:

   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make Changes**: Implement your changes.
4. **Test Your Changes**: Ensure your changes don't break existing functionality.
5. **Commit Your Changes**: Commit with clear, descriptive messages.
6. **Push Your Changes**: Push your branch to your fork.
7. **Create a Pull Request**: Submit a PR against the main repository.

## Code Style

This project follows these coding standards:

- Python code follows [Black](https://github.com/psf/black) formatting
- Import sorting with [isort](https://pycqa.github.io/isort/)
- Linting with [flake8](https://flake8.pycqa.org/en/latest/)

## Release Process

This project follows [Semantic Versioning](https://semver.org/):

- MAJOR version for incompatible API changes
- MINOR version for backward-compatible functionality additions
- PATCH version for backward-compatible bug fixes

### Steps for Creating a Release

1. **Update CHANGELOG.md**: Move items from Unreleased to the new version section.
2. **Update Version**: Update version number in relevant files.
3. **Create a Git Tag**: Tag the release commit:

   ```bash
   git tag -a vX.Y.Z -m "Release vX.Y.Z"
   ```

4. **Push the Tag**:

   ```bash
   git push origin vX.Y.Z
   ```

5. **Create a GitHub Release**: Create a release on GitHub referencing the tag.

## Questions?

If you have any questions about contributing, please open an issue in the repository.
