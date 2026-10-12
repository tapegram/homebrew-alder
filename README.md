# homebrew-alder

The Homebrew tap for [Alder](https://github.com/tapegram/alder).

```sh
brew install tapegram/alder/alder
alder version
```

The formula in `Formula/alder.rb` is written by GoReleaser when a version of Alder is
released (a `vX.Y.Z` tag on tapegram/alder; see chapter 11 of the Alder book, "Cutting a
release"). Do not edit it by hand. Alder needs Go on PATH; the formula depends on `go`.
