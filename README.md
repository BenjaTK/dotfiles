# My Dotfiles

These are probably a bit of a mess, but they're my mess. Includes my Neovim setup based on `kickstart-modular`, my Hyprland setup, tmux, waybar, etc.


To apply this configuration:
1. Clone the repository into `home`
2. Move to `/stow-home`.
3. Run the next command to apply everything:
```zsh
stow -vt ~ *
```
4. Or, to apply a specific module, run
```zsh
stow -vt ~ module-name
```
