# Tyfold Downloads

**Tyfold** is an IDE for everything you run in a terminal. Every session gets
its own pane: Claude Code, Codex CLI, opencode, a plain shell, whatever you run
next.

This repository is the **official public download host** for Tyfold's release
builds. Tyfold is a **commercial, closed-source** product. The source code is
private. Only the built, installable packages are published here, as GitHub
**[Releases](https://github.com/tyfold/downloads/releases)**.

## Download

Linux today. macOS and Windows next. Grab the package for your distro from the
**[latest release](https://github.com/tyfold/downloads/releases/latest)**:

| Platform | Package |
| --- | --- |
| Fedora / RHEL | `Tyfold-<version>-x86_64.rpm` |
| Debian / Ubuntu | `Tyfold-<version>-amd64.deb` |

Each release also publishes a `SHA256SUMS` file so you can verify your download:

```sh
sha256sum -c SHA256SUMS
```

## Prerequisite: bring your own CLI

Tyfold drives your **own** agent CLI (Claude Code, Codex or opencode) under your
**own** provider account. It doesn't host or resell a model, and your
credentials never leave your machine. Install and sign in to the CLI separately
before running Tyfold.

## Licence & privacy

Tyfold is licensed, not sold, under its End-User License Agreement. By
installing or using a build from this repository you agree to it.

- **Terms / EULA:** <https://tyfold.com/terms>
- **Privacy policy:** <https://tyfold.com/privacy>

## Links

- **Website:** <https://tyfold.com>
- **Releases:** <https://github.com/tyfold/downloads/releases>
- **Questions and bug reports:** <https://github.com/tyfold/downloads/discussions>

---

Tyfold is an independent, unaffiliated product. "Claude" and "Claude Code" are
trademarks of Anthropic, PBC; Tyfold is not endorsed by Anthropic.

Tyfold™ · © 2026
