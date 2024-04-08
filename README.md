# Dotfiles

This repository contains my customized configuration files for Zsh, including my `.zshrc` and `.p10k.zsh` files.

## .zshrc

`.zshrc` is a configuration file for the Z shell (Zsh). It contains various settings, aliases, and customizations to enhance my Zsh experience.

## .p10k.zsh

`.p10k.zsh` is the configuration file for Powerlevel10k, a Zsh theme. It customizes the appearance of my terminal prompt, providing a visually appealing and informative prompt.

### Usage

To use these configurations:

1. Clone this repository to your local machine:

`git clone <repository_url>`

2. Symlink the configuration files to your home directory (replace `<repository_path>` with the path to where you cloned this repository, by default `dotfiles`):

`ln -s <repository_path>/.zshrc ~/.zshrc`

`ln -s <repository_path>/.p10k.zsh ~/.p10k.zsh`

3. Restart your terminal or source the configuration files:

`source ~/.zshrc`

Now, your Zsh configuration will be updated with the settings from this repository.

### Troubleshooting

`ln: ~/.zshrc: File exists` -> Remove existing `.zshrc` from `~` before creating a symlink.
