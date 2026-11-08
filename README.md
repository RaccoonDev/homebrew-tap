# RaccoonDev Homebrew Tap

[Homebrew](https://brew.sh) formulas for tools by RaccoonDev. They work on macOS and Linux, on Intel and ARM.

## Formulas

| Formula | Description |
| --- | --- |
| [pominspect](https://github.com/RaccoonDev/pominspect) | Terminal UI for exploring a Maven build's effective POM and dependency tree, with the origin of every dependency |

## Install

```sh
brew install raccoondev/tap/pominspect
```

That adds this tap and installs the formula in one step. Alternatively:

```sh
brew tap raccoondev/tap
brew install pominspect
```

## Upgrade

```sh
brew update
brew upgrade pominspect
```

## Uninstall

```sh
brew uninstall pominspect
brew untap raccoondev/tap   # optional: remove the tap itself
```

## How the formulas are maintained

The formulas install the prebuilt binaries attached to each project's GitHub releases. Each project's release workflow regenerates its formula and commits it here, so **don't edit formulas by hand**: the next release overwrites the changes. Fix the generator in the project instead (for pominspect, [`.github/homebrew/formula.sh`](https://github.com/RaccoonDev/pominspect/blob/main/.github/homebrew/formula.sh)).

Problems with a tool itself belong in that project's issue tracker.
