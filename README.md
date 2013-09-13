Setup
=========

Pre-requisite
-----

    $ brew install ctags

Git Config
-----

    $ git config --global init.templatedir '~/.git_template'
    $ mkdir -p ~/.git_template

Script Setup
-----

    $ chmod +x hooks/*
    $ cp -r hooks ~/.git_template

Re-init existing Git repos
-----

    $ cd YOUR_GIT_REPO
    $ git init

Resources
-----

http://tbaggery.com/2011/08/08/effortless-ctags-with-git.html
