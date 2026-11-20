# seshness/herdr

Homebrew tap for [herdr-core](https://github.com/herdrdev/herdr-core) (`hc`),
installing upstream's signed release builds from releases.herdr.dev.

```sh
brew install seshness/herdr/herdr-core
```

Update with `brew upgrade herdr-core` (`hc update` defers to Homebrew).
A weekly workflow points the formula at upstream's latest release;
`scripts/bump` does the same by hand.
