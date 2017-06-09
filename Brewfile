tap 'caskroom/cask'
tap 'caskroom/versions'
tap 'homebrew/bundle'
tap 'homebrew/versions'

brew 'bundle install'
brew 'homebrew/versions/bash-completion2', args: ['with-default-names']
brew 'zsh'
brew 'zsh-completions'
brew 'bash'
brew 'iterm2-beta'
brew "mysql", restart_service: true, conflicts_with: ["homebrew/versions/mysql56"]

cask 'iterm2-beta'
cask 'atom'
cask 'google-chrome'
cask 'google-chrome-canary'
