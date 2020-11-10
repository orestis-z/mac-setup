# Mac OS X setup
Facing the setup of a new machine, here's a very brief and basic list of the usual suspects, related to the setup of a mac computer to work with.

## Homebrew & cask
The package manager is the default first thing I always install. Simply following the default steps. Homebrew downloads and installs the Command Line Tools for Xcode, so we're all good. `brew cask` handles the tapping, so we are cask-enabled too. Finally, `brew-cask-upgrade` provides upgrade-like capabilities to cask, and we're all set.
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
brew cask
brew tap buo/cask-upgrade
```
## Mac App Store
If some previously purchased software from the Mac App Store needs to be included, we can use `mas` to ease the installs.

```bash
brew install mas
```

## Curated list of apps
Once we have `homebrew`, `cask` (and `mas` if needed) we're ready to go:

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
