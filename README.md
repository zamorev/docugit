# Docugit

Native notes for macOS that sync through **your own Git repository**. Markdown on disk, optional privacy-first AI, and async teamwork without proprietary cloud lock-in.

This repository publishes **macOS release downloads only** — application source is maintained separately.

## Download

**[Latest release](https://github.com/zamorev/docugit/releases/latest)** — open the `.dmg`, then drag **Docugit** into Applications.

Direct link (v0.1.1):  
[Docugit-0.1.1.dmg](https://github.com/zamorev/docugit/releases/download/v0.1.1/Docugit-0.1.1.dmg)

### Install from Terminal (Homebrew)

Requires [Homebrew](https://brew.sh):

```bash
brew install --cask zamorev/tap/docugit
```

Without Homebrew, download and open the disk image:

```bash
curl -fL -o ~/Downloads/Docugit.dmg \
  "https://github.com/zamorev/docugit/releases/download/v0.1.1/Docugit-0.1.1.dmg" \
  && open ~/Downloads/Docugit.dmg
```

### Requirements

- macOS 14 (Sonoma) or later
- Git (Xcode Command Line Tools or Homebrew)

## Release notes

- [v0.1.1](https://github.com/zamorev/docugit/releases/tag/v0.1.1) — [full notes](releases/v0.1.1.md)
- [Changelog](./CHANGELOG.md)

## Feedback

Use [GitHub Issues](https://github.com/zamorev/docugit/issues) for bugs and feature requests.

## Verify download (optional)

```bash
shasum -a 256 Docugit-0.1.1.dmg
# expected: 88261b0391d9938a200c23614f947a5aac8558fefecb10daa4941e3775f9c4c1
```
