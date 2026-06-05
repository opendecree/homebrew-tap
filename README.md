# OpenDecree Homebrew Tap

Homebrew tap for [OpenDecree](https://github.com/opendecree/decree) — the schema-driven, multi-tenant configuration service.

> **Alpha:** OpenDecree is pre-production software. Everything is subject to change.

## Install

```bash
brew tap opendecree/tap
brew install decree
```

## Upgrade

```bash
brew upgrade decree
```

## Uninstall

```bash
brew uninstall decree
brew untap opendecree/tap
```

## How this tap is maintained

The formula in `Formula/decree.rb` is automatically updated by [goreleaser](https://goreleaser.com/) on every new decree release. No manual edits are needed after the first release cycle.

Source: [opendecree/decree](https://github.com/opendecree/decree)
