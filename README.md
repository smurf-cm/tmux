# tmux

[tmux](https://tmux.app/) configuration.

## Dependencies

```sh
sudo pacman -S --needed tmux git
```

Optional fuzzy finder:

```sh
sudo pacman -S --needed fzf
```

## Install

```sh
./install.sh
```

Creates:

```text
~/.tmux.conf     -> ~/.local/config/tmux/tmux.conf
~/.config/tmux   -> ~/.local/config/tmux
```

## Plugins

Install TPM:

```sh
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

Start tmux and install the configured plugins:

```sh
tmux
```

Inside tmux, press `prefix + I`.

## Notes

Plugin source trees under `tmux/plugins/` are ignored by Git.
