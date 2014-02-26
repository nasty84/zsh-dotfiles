# dotfiles

> These are my personal dotfiles, used to bootstrap and configure developer boxes

For a complete feature list, check out [FEATURES.md][1]

# Install On Ubuntu

Install `zsh`, which requires a _reboot_.

````shell
sudo sh ./ubuntu/zsh.sh
````

After boot, install everything else.

```shell
sudo sh ./ubuntu.sh
```

![shell.png][2]

# Install On OSX

```shell
sudo sh ./osx.sh
```

### Manual Steps

- Follow instructions on [ST3 site](https://sublime.wbond.net/installation#ST3) to install **Package Control**

### Customization

- Anything placed in `~/.zshrc.user` will run on every shell instance
- You can open that file using the `dotconfig` alias
- You can check out the distributed `~/.zshrc` file with the `zshconfig` alias, but it's recommended you don't change them **(if you must, fork this project)**

# License

MIT

# OSX (coming soon)

- https://github.com/sindresorhus/quick-look-plugins

[1]: FEATURES.md
[2]: https://raw.github.com/bevacqua/dotfiles/master/images/ubuntu.png
