## 🛡 Open Integrity Project: Cryptographic Roots of Trust for Open Source Development

The **Open Integrity Project** integrates cryptographic trust mechanisms into Git repositories, enabling them to serve as cryptographic roots of trust to ensure **verifiable chains of integrity, provenance, and authorship**. By leveraging Git's native **SSH-based signing** capabilities and structured verification processes, Open Integrity ensures transparency and immutability for software projects without requiring modifications to Git itself.

## 🎯 Project Goals

- **Immutable Proof-of-Origin** – Verify the authenticity of software artifacts
- **Signed Commits & Tags** – Ensure authorship integrity through SSH signatures (~128-bit security)
- **Tamper Detection** – Maintain verifiable repository history
- **Trust Delegation** – Enable controlled transition from inception key to authorized signers
- **Platform-Agnostic Validation** – Work across GitHub, GitLab, and self-hosted solutions

## 🧪 Open Integrity Forge: a proof-of-concept demo

[Open Integrity Forge](https://github.com/OpenIntegrityProject/open-integrity-forge) is a Git platform on Cloudflare in which the platform cannot make a commit valid: AI agents work in parallel forks with their own short-lived signing keys, every push is checked against the repository's own signer policy, and a change reaches `main` only when a person signs that merge commit with a passkey. It is a demonstration, not a specification; its rules and file formats are not yet reconciled with the tools in `core`.

- 🌐 [**Live demo**](https://forgedemo.gordianstack.com) — sign in with a passkey, then "Play the story"
- 🎬 [**Video walkthrough**](https://www.youtube.com/watch?v=_KdOGtynXig) — seven minutes
- 📘 [**Forge overview**](https://developer.blockchaincommons.com/open-integrity/forge/) on the Blockchain Commons developer site

## 💡 Learn More

- 📖 [**Documentation**](https://github.com/OpenIntegrityProject/core/tree/main/docs) — Documentation Hub, with problem statement, architecture, and guides
- 🛠️ [**Tools & Scripts**](https://github.com/OpenIntegrityProject/core/tree/main/src) — Tools for creating and verifying Open Integrity repositories
- 💬 [**Discussions**](https://github.com/orgs/OpenIntegrityProject/discussions) — Join the conversation

## 🤝 Get Involved

We welcome contributions from developers, security experts, and open-source enthusiasts.

- ⭐ **Star** our repositories to show support
- 📢 **Sharing** your discoveries with your network
- 💬 Ask a question or engage in discussions in our [**Community Discussions**](https://github.com/orgs/OpenIntegrityProject/discussions)
- ✍️ Report an issue in our [**Issue Tracker**](https://github.com/OpenIntegrityProject/core/issues)
- 🔎 Find [**Good First Issues**](https://github.com/OpenIntegrityProject/core/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) to get started
- 🏗️ Review our [**Contribution Guide**](https://github.com/OpenIntegrityProject/core/blob/main/docs/CONTRIBUTING.md)
- 💰 Become a financial patron to our host [Blockchain Commons via GitHub Sponsors](https://github.com/sponsors/BlockchainCommons)

## 📜 Copyright & License

Unless otherwise noted, all files are ©2025 Open Integrity Project / Blockchain Commons LLC., and licensed under the [BSD 2-Clause Plus Patent License](https://spdx.org/licenses/BSD-2-Clause-Patent.html) – See [LICENSE](https://github.com/OpenIntegrityProject/core/blob/main/LICENSE) for details.

## 🌍 About Us

The **Open Integrity Project** is an [Open Development](https://www.blockchaincommons.com/articles/Open-Development/) initiative hosted by [Blockchain Commons](https://www.BlockchainCommons.com), dedicated to advancing **open, interoperable, secure & compassionate digital infrastructure**, and embracing the [Gordian Principles](https://developer.BlockchainCommons.com/principles/) of **independence, privacy, resilience, and openness**.