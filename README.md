# whuhacker's dotfiles

Below is my shell prompt:

![Screenshot of my shell prompt](http://i.imgur.com/AWBwXqx.jpg?1)

Below is my vim:

![Screenshot of my vim](http://i.imgur.com/nZsXvQU.jpg?1)

Disclaimer: I have tuned the dotfiles for my own use. Some of the setup may not be good for you.

## Installation

```bash
$ cd ~
$ git clone https://github.com/whuhacker/dotfiles.git & cd dotfiles
$ rsync --exclude ".git/" --exclude ".DS_Store" --exclude "README.md" -avh --no-perms . ~
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