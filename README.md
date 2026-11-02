# Rust Pro issue tracker

This is the public issue tracker for **Rust Pro**, the Rust development plugin for JetBrains IDEs.
The commercial plugin's source code is maintained separately and is not published in this repository.

## Report a problem or suggest an improvement

- [Report a bug](https://github.com/Jetplugins/intellij-rust-pro-plugin/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/Jetplugins/intellij-rust-pro-plugin/issues/new?template=feature_request.yml)
- [Browse existing issues](https://github.com/Jetplugins/intellij-rust-pro-plugin/issues)

Before opening an issue, search for an existing report and update Rust Pro to the latest available version. Include the plugin version, IDE name and full build, operating system, Rust toolchain and rust-analyzer versions, reproduction steps, and a minimal Rust/Cargo example. For analysis and build issues, include the selected Cargo features and target. Mention local, WSL2, SSH or Docker execution and relevant LSP4IJ, rustfmt or CodeLLDB versions.

Rust sources, Cargo manifests, build output and IDE logs can contain confidential project information. Remove credentials, license keys, proprietary code, personal information and unrelated sensitive data before attaching examples, screenshots or logs to a public issue.

For security vulnerabilities, use [GitHub's private vulnerability reporting](https://github.com/Jetplugins/intellij-rust-pro-plugin/security/advisories/new) instead of opening a public issue. See the [security policy](SECURITY.md).

## About Rust Pro

Rust Pro combines native IntelliJ editing and Cargo workflows with rust-analyzer through Red Hat LSP4IJ:

- Token and semantic highlighting, completion, navigation, documentation, inspections, formatting and refactoring.
- Cargo workspace, feature and dependency tools, checked dependency-upgrade previews, native run/test configurations and test-result trees.
- CodeLLDB debugging and Rust value presentation in supported IDE products.
- Rustup toolchain setup, analyzer exploration, and optional nextest, coverage, profiling and dependency-quality tools.
- Local and configured WSL2, SSH and Docker execution.

Rust Pro supports IntelliJ Platform 2025.2 and newer. Compiler assistance and execution require compatible installed Rust tools and a trusted project. Debugging requires CodeLLDB and a supported IDE product. Optional quality and remote tools are installed/configured separately.

Learn more at [JetPlugins](https://jetplugins.dev).
