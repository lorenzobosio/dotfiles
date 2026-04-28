# dotfiles

My personal Mac development setup.

## What's here

- `.zshrc` — Zsh config (Oh My Zsh + Starship + plugins + aliases)
- `Brewfile` — list of Homebrew packages, casks, and VS Code extensions

## Setup on a new Mac

1. Install Homebrew: https://brew.sh
2. Clone this repo: `git clone https://github.com/YOUR_USERNAME/dotfiles.git ~/dotfiles`
3. Symlink configs: `ln -s ~/dotfiles/.zshrc ~/.zshrc`
4. Install everything: `cd ~/dotfiles && brew bundle install`
5. Restart terminal
