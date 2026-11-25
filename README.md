# Roosterbuild Homebrew tap

Homebrew cask for [Rooster](https://roosterbuild.com), a scheduler for dbt Core.
Works on macOS and Linux.

## Install

```bash
brew install roosterbuild/tap/rooster
```

## Upgrade

```bash
brew upgrade rooster
```

Rooster also tells you in its UI and in `rooster version` when a new version is out.

## Uninstall

```bash
brew uninstall rooster
```

## About this repository

The release workflow writes `Casks/rooster.rb` each time a new version of Rooster
is released. Don't edit it by hand: the next release overwrites it.

Release notes and downloads are at
[roosterbuild/rooster-releases](https://github.com/roosterbuild/rooster-releases/releases).
Other ways to install are in the [docs](https://roosterbuild.com/docs).
