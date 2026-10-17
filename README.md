# homebrew-tap

Archived. The `dotfiles` formula (the `dot` CLI) moved to `staixbwlb/cask`
([STAIxBWLB/homebrew-cask](https://github.com/STAIxBWLB/homebrew-cask)).

```bash
brew tap staixbwlb/cask
brew trust staixbwlb/cask
brew install dotfiles
```

Existing installs migrate on `brew update` through `tap_migrations.json`.
If `brew info dotfiles` still names `entelecheia/tap`, run
`brew reinstall staixbwlb/cask/dotfiles`.
