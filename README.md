dotfiles
====

dotfiles.

### Description

主に以下の設定ファイルをinstallします

- zsh
- git
- vim
- tmux

### Requirement

- zsh
- git
- vim7.4
- tmux

On OS X, you need to install some library.

You can install them by using [Homebrew](http://brew.sh).

- coreutil
- reattach-to-user-namespace

This dotfiles supports the following libraries.

- [pyenv](https://github.com/yyuu/pyenv)
- [rbenv](https://github.com/sstephenson/rbenv)
- [nvm](https://github.com/creationix/nvm)
- [peco](https://github.com/peco/peco)

### Install

```shell
$ git clone git@github.com:sota1235/dotfiles.git ~/.dotfiles

$ cd ~/.dotfiles

$ ./install
```

You can specify git user name and e-mail address by add options.

```shell
$ ./install -u {git user name} -e {git e-mail address}
```

#### Update

Exec `dot_update` command.

```shell
$ dot_update

(*'-') < Do you want to update the dotfiles? [y/N]
```

#### Uninstall

Exec `dot_uninstall` command.

```shell
$ dot_uninstall

(*;-;) < Do you want to uninstall the dotfiles? [n/Y]
```

### Usage

- zsh

![](https://i.gyazo.com/1404f537852307201b80d4477ea7e415.png)

- vim

Thanks for [nikezono/dotfiles](https://github.com/nikezono/dotfiles)

![](https://i.gyazo.com/7601ffa462abb53abb8034f60c842121.png)

- tmux

![](https://i.gyazo.com/c8aeebff9bb277d5c2e4a3295cac857b.png)

### Author

@sota1235
