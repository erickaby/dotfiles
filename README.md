# dotfiles

## Dependencies

First, make sure you have all those things installed:

- `git`: to clone the repo
- `curl`: to download some stuff
- `tar`: to extract some stuff
- `fish`: the shell
- `sudo`: some configs may need that

- `terminal-notifier`

## Install

Then, run these steps:

```bash
git clone https://github.com/erickaby/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
./script/bootstrap.fish
```

## macOS defaults

You use it by running:

```bash
~/.dotfiles/macos/set-defaults.sh
```

And logging out and in again or restart.

Thanks to [caarlos0](https://github.com/caarlos0/dotfiles.fish)
