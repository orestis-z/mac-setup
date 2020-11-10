# Mac OS X setup

Facing the setup of a new machine, here's are instructions to set up the mac computer environment I like to work with.

## Homebrew & cask

Install Homebrew and Cask, a software package management system that simplifies the installation of software on Apple's macOS:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
brew cask
brew tap buo/cask-upgrade
```
## Mac App Store
Install `mas`, a CLI for the App Store:

```bash
brew install mas
```

## Curated list of apps

Once we have `homebrew`, `cask` and `mas` installed, we're ready to go.

### Productivity

```bash
# Magnet
mas purchase 441258766

# Go2Shell
brew cask install go2shell
```
### Browsers

```bash
# Browsers
brew cask install google-chrome
brew cask install firefox
brew cask install tor-browser
brew cask install opera
```

### Common apps

```bash
# Gimp
brew cask install gimp

# MS (requires license)
brew cask install microsoft-office

# The Unarchiver
brew cask install the-unarchiver

# VLC
brew cask install vlc

# Messaging
brew cask install all-in-one-messenger

# DaisyDisk
mas purchase 411643860
```

### Development

```bash
brew cask install iterm2
brew install bash-completion
brew install tree
brew install wget
brew install htop
brew install pstree
brew install watch

# Go2Shell
brew cask install go2shell

# AWS CLI
brew install awscli

# API development
brew cask install paw

# Text editors/IDEs
brew cask install sublime-text
brew cask install visual-studio-code

# Charles proxy
brew cask install charles

# Dash
brew cask install dash

# ES
brew install elasticsearch

# Git-related
brew cask install fork
brew cask install meld

# Gradle
brew install gradle

# Ngrok
brew cask install ngrok

# GoLang
brew install go

# Python
brew install python
brew install python3
brew install ipython

# JS
brew install node
brew install yarn

# Virtualization
brew cask install virtualbox
brew cask install docker

# Databases
brew cask install psequel

# VPN
brew cask install tunnelblick

# Xcode
mas install 497799835
```
