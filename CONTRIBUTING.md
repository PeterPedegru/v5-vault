# Contributing to PoolTogether v5 Vault

Thanks for your interest in contributing to **PoolTogether v5 Vault**!  
This repository contains the core smart contracts and helper utilities for managing Vaults in the PoolTogether v5 ecosystem.

We welcome all contributions — from small documentation fixes to improvements in tests, scripts, or Solidity contracts.

---

## 🏁 Quick Start (via GitHub Web)

1. **Fork** the repo (top-right corner → **Fork**).
2. In your fork, click **Add file → Create new file**.
3. Set the file path (for example, `CONTRIBUTING.md`) and paste your content or edits.
4. Commit your changes to a **new branch** and open a **Pull Request (PR)** against `pooltogether/v5-vault:main`.

---

## 🧑‍💻 Local Development Setup

You can work with this repository locally using **Foundry**.

### Prerequisites

- [Foundry](https://book.getfoundry.sh/getting-started/installation)
- [Node.js](https://nodejs.org/en/download/)
- [pnpm](https://pnpm.io/) or npm

### Setup

```bash
git clone https://github.com/pooltogether/v5-vault.git
cd v5-vault
pnpm install
forge build
```

### Run Tests

```bash
forge test
```

This will compile and run the smart contract tests to verify that everything works correctly.

---

## 🌱 Good First Contributions

If you’re new to this project, here are simple and valuable ways to contribute:

- Fix typos or grammar in documentation (e.g., `README.md`)
- Improve or clarify comments in Solidity files
- Add missing [NatSpec](https://docs.soliditylang.org/en/latest/natspec-format.html) comments to functions
- Add or expand test cases
- Improve formatting or consistency of `.sol` files (without changing logic)
- Fix small linter or style issues reported by Foundry

---

## 🧾 Commit and Pull Request Guidelines

Before submitting your Pull Request:

1. **Write clear commit messages** explaining _what_ changed and _why_.
2. Ensure your changes **pass tests** (`forge test`).
3. If you edit contracts, run `forge fmt` before committing.
4. Add a short description in your PR explaining:
   - The purpose of the change
   - Any related issue or discussion (if applicable)

Example PR title:

```
docs: fix typos in README and clarify setup instructions
```

---

## 💬 Communication & Discussion

If you’re unsure about something, feel free to open a **Draft PR** or start a **Discussion** in the repository.  
We’re happy to help guide you through your first contribution!

---

## ⚖️ License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project itself (MIT).

---

### 💚 Thank you for contributing to PoolTogether!
Even small documentation or comment improvements make a big difference.
