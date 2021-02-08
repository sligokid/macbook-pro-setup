# macbook-pro-setup

# Homebrew
https://brew.sh  
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

# (Keep in Dock)
# iterm2
$ brew cask install iterm2

# spectacle (preferences -> enable on startup)
$ brew cask install spectacle

# sublime-text
$ brew cask install sublime-text

# chrome
$ brew cask install google-chrome

# docker
```
$ brew cask install docker
$ sudo mkdir /srv/docker  
$ sudo chown /srv/docker $USER
# add /srv/docker to docker->preferneces->file sharing
```

# slack (sign in with okta)
$ brew cask install slack

# pulse
https://www.pulsesecure.net/trynow/client-download/#top

# Java 8
$ brew tap caskroom/versions  
$ brew cask install java8

OR 
curl -s "https://get.sdkman.io" | bash
$ sdk install java 8.0.282.hs-adpt

# Maven
$ brew install maven

# Intellij
$ brew cask install intellij-idea-ce (Community Edition)  
$ bres cask install intellij-idea (Licenced Version)

# Node
$ brew install npm

# Git bash completion
$ brew install git bash-completion

git config --global user.name "Your Name"  
git config --global user.email "you@example.com"  
git config --global alias.co checkout  
git config --global apply.whitespace nowarn  

# Git bash prompt
__brew intstall bash-git-prompt__  
examples:  
(master↑3|✚1): on branch master, ahead of remote by 3 commits, 1 file changed but not staged  
(status|●2): on branch status, 2 files staged  
(master|✚7…): on branch master, 7 files changed, some files untracked  
(master|✖2✚3): on branch master, 2 conflicts, 3 files changed
(master|⚑2): on branch master, 2 stash entries  
(experimental↓2↑3|✔): on branch experimental; your branch has diverged by 3 commits, remote by 2 commits; the repository is otherwise clean  
(:70c2952|✔): not on any branch; parent commit has hash 70c2952; the repository is otherwise clean

# Postgres (install only)
$ brew install postgresql

# Wget
$ brew install wget

# Rpm
$ brew install rpm

# Vim
echo "syntax on" > ~/.vimrc

# Amazon Music
brew cask install amazon-music

# Evernote
brew cask install evernote

# 
# dotfiles courtesy of AWS Randall Hunt
$ git clone https://github.com/sligokid/dotfiles

# Xcode https://github.com/nodejs/node-gyp#on-macos
$ xcode-select --install
