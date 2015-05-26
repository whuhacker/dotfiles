# whuhacker's dotfiles

Below is my shell prompt:

![Screenshot of my shell prompt](http://i.imgur.com/AWBwXqx.jpg?1)

Below is my vim:

![Screenshot of my vim](http://i.imgur.com/nZsXvQU.jpg?1)

**Disclaimer:** These dotfiles are for my own use. Some of the configuration may not be suitable for you.

## Installation

```bash
$ cd ~
$ git clone https://github.com/whuhacker/dotfiles.git && cd dotfiles
$ rsync --exclude ".git/" --exclude "solarized/" --exclude ".DS_Store" --exclude "README.md" -avh --no-perms . ~
$ source ~/.bash_profile

# don't forget to change your git username and email
$ git config --global user.name "Your Name"
$ git config --global user.email you@company.com
```

## Homebrew

You may want to install some common [Homebrew](http://brew.sh) formulae when setting up a new Mac.

```bash
$ ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ ./brew.sh
```

## Solarized color scheme

[Solarized](https://github.com/altercation/solarized) is precision color scheme for multiple applications (terminal, vim, etc.) with both dark/light modes, which is popular among Mac users. To apply the recommended theme to Terminal.app,
1. Double click the `Solarized Dark ansi.terminal` and `Solarized Light ansi.terminal` in the `solarized` folder.
2. Open Teminal.app, select Preferences > Profiles, choose Solarized as the default profile.