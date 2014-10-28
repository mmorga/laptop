# Customization Notes

This the is list of stuff that I'm planning to add to the Thoughtbot laptop script

# References

* https://github.com/lra/mackup
* https://gist.github.com/kevinelliott/0726211d17020a6abc1f
* https://github.com/kevinrenskers/dotfiles
* https://github.com/nicolashery/mac-dev-setup
* http://robots.thoughtbot.com/laptop-setup-for-an-awesome-development- environment
* http://brew.sh/
* http://caskroom.io/

# App Store Apps

* Degrees (Weather)
* Xcode (and command line `xcode-select —install
`)

# 3rd Party Websites

* Vidyo (not currently in cask)
* [Sublime Text 3](http://www.sublimetext.com/3)
* [LiveReload Extensions](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-)
* 1Password

# Homebrew

## Installed by Laptop

* postgres
* redis
* the_silver_searcher
* vim
* ctags
* tmux
* reattach-to-user-namespace
* imagemagick
* qt
* watch
* gh
* nvm
* rbenv, rbenv-gem-rehash, ruby-build
* ruby 2.1.3 with rbenv
* gems
    * bundler (+ config of )

## Standard Additions

* colordiff
* curl
* docker
* elasticsearch
* erlang
* git
* go
* graphviz
* inkscape
* mackup
* mercurial
* mysql
* node
* pandoc
* pyenv-virtualenv
* pyenv-virtualenvwrapper
* python
* rbenv-binstubs
* rbenv-bundler
* rbenv-gem-rehash
* ruby-build
* wget
* xclip
* zsh
* zsh-completions
* zsh-syntax-highlighting

## Custom Additions

* aspell
* diction
* elixir
* epubcheck
* plantuml
* sloccount
* task

# Homebrew Cask

```
brew install caskroom/cask/brew-cask
```

## Casks to Install

* anvil
* atom
* battery-guardian
* firefox
* gimp
* github
* google-chrome
* iterm2
* launchrocket
* livereload
* skype
* vagrant
* vagrant-manager
* virtualbox

## Custom Casks to Install

* grandperspective
* spotify
* dropbox

# Mackup

Talk about using this to sync machines and/or move to a new machine

Add an option to configure makeup for Box Sync instead of default Dropbox

# Install custom .dotfiles

Examples:

```
git clone git@github.com:kevinelliott/.dotfiles.git ~/.dotfiles
~/.dotfiles/install.sh
```

or

https://github.com/thoughtbot/dotfiles

or

https://github.com/kevinrenskers/dotfiles



# TODO

Section on npm setup including things like LESS for encore-ui development
