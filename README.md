# dotfiles

> These are my personal dotfiles, used to bootstrap and configure developer boxes

For a complete feature list, check out [FEATURES.md][1]

# Install On OSX

```shell
git clone https://github.com/bevacqua/dotfiles.git ~/.dotfiles && sudo sh ~/.dotfiles/osx.sh
```

![shell-osx.png][4]

# Install On Ubuntu

Install `zsh`, using the script below, then you need to _reboot_. Apologies!

````shell
sudo sh ./ubuntu/zsh.sh
````

After boot, install everything else.

```shell
sudo sh ./ubuntu.sh
```

![shell-ubuntu.png][2]

### Customization

- Anything placed in `~/.zshrc.user` will run on every shell instance
- You can open that file using the `dotconfig` alias
- You can check out the distributed `~/.zshrc` file with the `zshconfig` alias, but it's recommended you don't change them **(if you must, fork this project)**
- I won't install Sublime Text packages for you. You do that. _You did get [`Package Control`][3], though._ I have some recommended packages on the [FEATURES][1] document.

# License

MIT

[1]: FEATURES.md
[2]: https://raw.github.com/bevacqua/dotfiles/master/images/ubuntu.png
[3]: https://sublime.wbond.net/
[4]: https://raw.github.com/bevacqua/dotfiles/master/images/osx.png
