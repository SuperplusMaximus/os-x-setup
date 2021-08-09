# os-x-setup
Mac OS commands lines setup

```
xcode-select --install
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
# install zsh before echo the brew path
brew update
brew install iterm2
# update iterm2 settings -> colors, keep directory open new shell, keyboard shortcuts
brew install bash # latest version of bash
# set brew bash as default shell
which bash
# copie and paste the path to /etc/shells files
brew install fortune
brew install cowsay 
brew install git
brew install vcprompt
# update bash_profile
brew cask install spectacle
brew cask install alfred
# set CMD+space to launch alfred
brew cask install firefox
# install nvm/node
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
nvm install stable
mkdir ~/workspace
npm install -g lite-server eslint
brew cask install visual-studio-code
# update vscode settings
# install vscode extensions
```
