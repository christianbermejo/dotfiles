# Items

[oh-my-zsh - community-driven ZSH config framework](https://github.com/ohmyzsh/ohmyzsh)

[base16-shell - make your shell more colorful!](https://github.com/chriskempson/base16-shell)

[exa - `ls` replacement](https://the.exa.website/install/macos)

[antigen - Plugin manager for zsh](https://github.com/zsh-users/antigen)

[homebrew - package manager for macOS](https://brew.sh/)


# Procedure

- Install all the items listed above.
- Once installed, copy `.zshrc`,`.antigenrc` and `Brewfile` to the path `~`
- Apply ZSH-related configuration and installation
```
source .zshrc 
```
- Install applications via homebrew
```
brew bundle --file=~/Brewfile
```
