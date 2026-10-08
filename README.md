# Docugit

Native notes for macOS that sync through **your own Git repository**. Markdown on disk, optional privacy-first AI, and async teamwork without proprietary cloud lock-in.

This repository publishes **macOS release downloads only** — application source is maintained separately.

## Download

**[Latest release](https://github.com/zamorev/docugit/releases/latest)** — open the `.dmg`, then drag **Docugit** into Applications.

Direct link (v0.2):  
[Docugit-0.2.dmg](https://github.com/zamorev/docugit/releases/download/v0.2/Docugit-0.2.dmg)

### Install from Terminal (Homebrew)

Requires [Homebrew](https://brew.sh):

```bash
brew install --cask zamorev/tap/docugit
```

Without Homebrew, download and open the disk image:

```bash
curl -fL -o ~/Downloads/Docugit.dmg \
  "https://github.com/zamorev/docugit/releases/download/v0.2/Docugit-0.2.dmg" \
  && open ~/Downloads/Docugit.dmg
```

### Requirements

- macOS 14 (Sonoma) or later
- Git (Xcode Command Line Tools or Homebrew)

## Release notes

- [v0.2](https://github.com/zamorev/docugit/releases/tag/v0.2) — [full notes](releases/v0.2.md)
- [v0.1.1](https://github.com/zamorev/docugit/releases/tag/v0.1.1) — [full notes](releases/v0.1.1.md)
- [Changelog](./CHANGELOG.md)

## Feedback

Use [GitHub Issues](https://github.com/zamorev/docugit/issues) for bugs and feature requests.

## Verify download (optional)

```bash
shasum -a 256 Docugit-0.2.dmg
# expected: c5b03bc3a9c0dd452965ed79beae99712d4f63e894adfa3f881123efb934b9f4
```
