# Homebrew tap for Swarm

[Swarm](https://swarm-term.com) is a macOS terminal whose tabs are persistent
sessions, on your Mac or on Linux and macOS servers over SSH.

## Install

The app, with `swarmctl` (macOS 13 or later):

```bash
brew install --cask arturborycki/swarm/swarm
```

Only the daemon and `swarmctl`, built from source (macOS or Linux; needs Rust,
which Homebrew installs):

```bash
brew install arturborycki/swarm/swarmd
```

Swarm installs its own updates; `brew upgrade` also works.

## Source

The cask and formula are kept in
[arturborycki/swarm-term](https://github.com/arturborycki/swarm-term/tree/main/packaging/homebrew)
and copied here on each release by `scripts/update-homebrew.sh`. Please open
issues there.
