# GearBoxHub

Your centralized destination for industrial gears, tools, and essentials. Simplifying access to quality equipment for engine construction needs.

## Table of Contents

- [Branches](#branches)
- [Development Process](#development-process)
- [How to Contribute](#how-to-contribute)
- [Project Configuration](#project-configuration)
- [Versioning](#versioning)
- [CI/CD](#cicd)
- [License](#license)

## Branches

- `prod`: Branch for production (final destination).
- `preprod`: Branch for pre-production (thorough testing before production).
- `dev`: Development branch (aggregating all pages).
- Feature-specific branches for each page (e.g., `page_home`, `page_checkout`, etc.).

## Development Process

1. Create a new branch from `dev` for each new feature or modification.
2. Use Pull Requests to integrate features into `dev`.
3. Test and validate features on the `dev` branch.
4. Merge changes from `dev` to `preprod` for thorough testing.
5. Once tests pass, merge from `preprod` to `prod` for deployment to production.

## How to Contribute

1. Clone the repository to your local machine.
2. Create a branch for your contribution (`git checkout -b feature/my-contribution`).
3. Make your changes and test them locally.
4. Create a Pull Request to the `dev` branch for review.

## Project Configuration

- Instructions for installing dependencies.
- Instructions for running the application locally.

## Versioning

- Use semantic versioning to label project versions.

## CI/CD

- Use GitHub Actions (or another CI/CD tool) for continuous integration, automated testing, and deployments.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
