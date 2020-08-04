# basic mac development environment setup
https://youtu.be/tMNOpaQrfAE?t=2331

## osx setup commands: 

 - `$ xcode-select --install`
 - install brew: https://brew.sh/
 - `$ brew update`
 - `$ brew cask install iterm2`
   - preset natural text editing
   - fonts
   - color
   - reuse previous session's directory
 - `$ brew install bash` 
   - `echo $SHELL` -> get the default shell path
   - `which bash` -> get the installed shell path
   - `$ nano /etc/shells` -> add new shell to file
   - `chsh -s [PATH TO SHELL]` -> save new shell as default
 - `$ brew install git`
 - `$ brew install vcprompt`
 - install nvm: https://github.com/nvm-sh/nvm 
   - `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash` 
 - `$ nvm install stable` 
 - update bash profile: 
   - add `.bash_profile` to home directory (see dotfiles repo)
 - `$ brew cask install spectacle`
 - `$ brew cask install alfred`
   - change to default app instead of spotlight  (system preferences > keyboard > shortcuts)
 - `$ brew cask install google-chrome` and `$ brew cask install firefox`
   - tabliss, adblock, gofullpage
   - duckduckgo search engine
 - Install Hyperswitch: https://bahoom.com/hyperswitch/get
 - `mkdir ~/development`
 - `$ brew cask install visual-studio-code`
   - update vscode settings
   - install vscode extensions 
     - Apache Conf
     - Awesome Flutter Snippets
     - Beautify css/sass/scss/less
     - better comments
     - community material theme
     - dart
     - es7 react/redux/graphql
     - eslint
     - express snippets
     - flutter
     - import cost
     - live server
  


## designer tools
 - `$ brew cask install figma`



npm install -g lite-server eslint




## fonts:

 - https://github.com/tonsky/FiraCode


# credit

big thank's to CJ's Stream. This guide is heavy influenced by him. Some of these settings are adapted to my personal preferences and needs.

- https://gist.github.com/w3cj
- https://github.com/nvm-sh
- https://github.com/tonsky

