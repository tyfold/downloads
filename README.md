# Tyfold — Downloads

**Tyfold** is a desktop control room for many terminal sessions at once — plain
shells or LLM CLIs, with first-class support for Claude Code — and every
session's status gathered into one dashboard.

This repository is the **official public download host** for Tyfold's release
builds. Tyfold is a **commercial, closed-source** product; the source code is
private. Only the built, installable packages are published here, as GitHub
**[Releases](https://github.com/tyfold/downloads/releases)**.

## Download

Linux-first today (macOS / Windows later). Grab the package for your distro from
the **[latest release](https://github.com/tyfold/downloads/releases/latest)**:

| Platform | Package |
| --- | --- |
| Fedora / RHEL | `Tyfold-x86_64.rpm` |
| Debian / Ubuntu | `Tyfold-amd64.deb` |

Each release also publishes a `SHA256SUMS` file so you can verify your download:

```sh
sha256sum -c SHA256SUMS
```

> **Builds are published here at launch.** Until then this repository reserves
> the download home; the release list may be empty.

## Prerequisite — bring your own Claude Code

Tyfold drives your **own** local LLM CLI (today `claude`) under your **own**
provider credentials — it does not host or resell a model, and your credentials
never leave your machine. Install and sign in to Claude Code separately before
running Tyfold.

## Licence & privacy

Tyfold is licensed, not sold, under its End-User License Agreement. By
installing or using a build from this repository you agree to it.

- **Terms / EULA:** <https://tyfold.com/terms>
- **Privacy policy:** <https://tyfold.com/privacy>

## Links

- **Website:** <https://tyfold.com>
- **Releases:** <https://github.com/tyfold/downloads/releases>

---

Tyfold is an independent, unaffiliated product. "Claude" and "Claude Code" are
trademarks of Anthropic, PBC; Tyfold is not endorsed by Anthropic.

Tyfold™ — © 2026
