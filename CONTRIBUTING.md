# Contributing to Carbon Locker

First off, thank you for considering contributing to Carbon Locker! Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

## How Can I Contribute?

### 🌡️ Reporting Bugs

If you find a bug, please open an issue using the [bug report template](https://github.com/carbonable-labs/carbon-locker/issues/new?assignees=&labels=bug&template=01_BUG_REPORT.md&title=bug%3A+). Be sure to include a clear title and description, as much relevant information as possible, and a code sample or screenshot if applicable.

### 📝 Requesting Features

If you have an idea for a new feature, please submit a feature request using the [feature request template](https://github.com/carbonable-labs/carbon-locker/issues/new?assignees=&labels=enhancement&template=02_FEATURE_REQUEST.md&title=feat%3A+). Include a clear and concise description of the feature, why it would be useful, and any additional context. You can also contact us through Discord or Telegram to discuss about it.

## ⛏️ Submitting Pull Requests

1. **Choose an issue**: Pick an unassigned issue and ask for more information if needed via Telegram or Discord.
2. **Fork the repository**: Click the "Fork" button on the top right of the repository page and create a new branch dedicated to the issue.
3. **Code your changes**: Implement your feature or fix the bug. Follow the project's coding style and commit message principles.
4. **Test your changes**: Ensure that all tests pass and your changes do not break existing functionality.
5. **Submit your changes**: Push your changes and open a new pull request with a clear description of your changes and link to any relevant issues.

## 📦 Project Setup

#### Requirements

- [Scarb](https://docs.swmansion.com/scarb/): _v2.6.0_
- [Starknet Foundry](https://foundry-rs.github.io/starknet-foundry/index.html) _v0.26.0_

We recommend installing dependencies using [asdf](https://asdf-vm.com/):

```bash
asdf plugin add scarb
asdf install scarb 2.6.0
asdf plugin add starknet-foundry
asdf install starknet-foundry 0.26.0
```

#### Compile

To compile the project, run:

```bash
scarb build
```

### License

By contributing to Carbon Locker, you agree that your contributions will be licensed under the License used.

### Thank You

Thank you for your interest in contributing to Carbon Locker! We look forward to building something great together.
