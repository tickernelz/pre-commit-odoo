# Pre-commit Odoo Template

This repository contains a pre-commit configuration template for Odoo projects. It sets up various code quality tools and checks to ensure consistent and clean code across your Odoo development projects.

## Features

- Linting and formatting for Python, JavaScript, and XML files
- Consistent code style enforcement
- Automatic fixes for many common issues
- Odoo-specific checks

## Tools Included

- [Ruff](https://github.com/astral-sh/ruff): A fast Python linter and formatter
- [Prettier](https://prettier.io/): Code formatter for various file types
- [ESLint](https://eslint.org/): JavaScript linter
- [pylint-odoo](https://github.com/OCA/pylint-odoo): Odoo-specific pylint checks
- Various pre-commit hooks for additional checks

## Setup

1. Install pre-commit:
```shell
pip install pre-commit
```

2. Copy the following files to your Odoo project root:
- `.pre-commit-config.yaml`
- `.eslintrc.yml`
- `.prettierrc.yml`
- `.ruff.toml`
- `etc`

3. Install the pre-commit hooks:
```shell
pre-commit install
```

## Usage

Once installed, pre-commit will run automatically on `git commit`. You can also run it manually on all files:
```shell
pre-commit run --all-files
```

## Customization

You can customize the behavior of each tool by modifying their respective configuration files. Refer to each tool's documentation for more details on available options.

## Contributing

Contributions to improve this template are welcome. Please submit a pull request or open an issue to discuss proposed changes.
