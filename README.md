# macbook-pro-setup

# Homebrew
https://brew.sh  
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

# Misc
```
brew install --cask iterm2
brew install --cask telegram
brew install --cask google-chrome
brew install --cask brave-browser
brew install --cask sublime-text
brew install --cask evernote
brew install --cask sourcetree
brew install --cask atom
brew install --cask skype
brew install --cask spotify
brew install --cask insomnia
brew install --cask obsidian
```

# 1Password 
https://1password.com/downloads/mac/
Add Brave plugin

# spectacle (preferences -> launch spectacle on login)
```
brew install --cask spectacle
```

# docker
```
brew install --cask docker
--sudo mkdir /srv/docker  
--sudo chown /srv/docker $USER
--add /srv/docker to docker->preferences->file sharing
brew install docker-compose
mkdir -p ~/.docker/cli-plugins
ln -sfn /opt/homebrew/opt/docker-compose/bin/docker-compose ~/.docker/cli-plugins/docker-compose 
```

# slack (sign in with okta)
```
brew install --cask slack
```

# Java 8
```
curl -s "https://get.sdkman.io" | bash
sdk install java 8.0.332-zulu
```

# Maven
```
brew install maven
```

# Node

```
brew install nvm
nvm install lts/gallium && nvm alias default lts/gallium && nvm use default
npm i -g install npm eslint flow-bin yarn
```


# Intellij
```
https://www.jetbrains.com/toolbox-app/download/download-thanks.html?platform=mac
- IntelliJ
- WebStrom
- Datagrip

OR

brew install --cask intellij-idea-ce (Community Edition)  
brew install --cask ntellij-idea (Licenced Version)

```

# Git bash completion
```
brew install git bash-completion
```

# Git config
```
git config --global user.name "Your Name"  
git config --global user.email "you@example.com"  
git config --global alias.co checkout  
git config --global apply.whitespace nowarn  
```

# Git bash prompt
```
brew install bash-git-prompt
```

examples:  
(master↑3|✚1): on branch master, ahead of remote by 3 commits, 1 file changed but not staged  
(status|●2): on branch status, 2 files staged  
(master|✚7…): on branch master, 7 files changed, some files untracked  
(master|✖2✚3): on branch master, 2 conflicts, 3 files changed
(master|⚑2): on branch master, 2 stash entries  
(experimental↓2↑3|✔): on branch experimental; your branch has diverged by 3 commits, remote by 2 commits; the repository is otherwise clean  
(:70c2952|✔): not on any branch; parent commit has hash 70c2952; the repository is otherwise clean

# Postgres (install only)
```
brew install postgresql
```

# Wget
```
brew install wget
```

# Rpm
```
brew install rpm
```

# Vim
```
echo "syntax on" > ~/.vimrc
```

# Evernote
```

```
# Google cloud SDK
```
brew install --cask google-cloud-sdk
gcloud init
sudo gcloud alpha compute config-ssh
sudo gcloud beta compute config-ssh
```
Or reinstall
```
brew reinstall --cask google-cloud-sdk
```

# 
# dotfiles courtesy of AWS Randall Hunt
```
git clone https://github.com/sligokid/dotfiles
```

# Xcode https://github.com/nodejs/node-gyp#on-macos
```
xcode-select --install
```
OR reinstall
```
sudo rm -rf /Library/Developer/CommandLineTools
xcode-select --install
``` 
