# Ansible Playbook for Ubuntu CLI

[![Build Status](https://travis-ci.org/suzuki-shunsuke/ansible-playbook-ubuntu-cli.svg?branch=master)](https://travis-ci.org/suzuki-shunsuke/ansible-playbook-ubuntu-cli)

* 日本語対応
* wget
* curl
* nodebrew
* silver searcher
* tree
* vim-gnome
* neobundle.vim
* vim config
* zsh
* zip
* zplug
* zsh config
* tmux
* tmux config
* tpm
* docker engine
* docker compose
* git
* gitconfig
* git lfs
* pyenv
* pyenv install dependencies
* rbenv
* rbenv/ruby-build
* rbenv install dependencies
* go
* gvm
* gvm install dependencies
* hub
* direnv
* ghq
* fzf
* colorrc

## Install Ansible roles dependencies

```
$ ansible-galaxy install -r roles.yml
```

## Create Vagrant Package

```
$ vagrant destroy
$ vagrant up --provision-with=ansible
$ vagrant package
```

## TODO

* [apt-get autoremove](https://github.com/ansible/ansible-modules-core/issues/4029)
