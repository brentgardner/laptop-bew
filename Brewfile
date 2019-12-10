cask_args appdir: "/Applications"

tap "caskformula/caskformula"
tap "cloudfoundry/tap"
tap "homebrew/bundle"
tap "homebrew/cask"
tap "homebrew/core"
tap "homebrew/services"
tap "heroku/brew"

brew "libffi"
brew "automake"
brew "bfg"
brew "bison"
brew "chruby"
brew "coreutils"
brew "gdbm"
brew "git"
brew "gnupg"
brew "go"
brew "hub"
brew "libtool"
brew "imagemagick"
brew "pkg-config"
brew "libyaml"
brew "dialpad"

brew "nmap"
brew "nvm"

mkdir $HOME/.nvm
cp $(brew --prefix nvm)/nvm-exec ~/.nvm/
echo "export NVM_DIR=~/.nvm" >> ~/.zshrc
echo "source $(brew --prefix nvm)/nvm.sh" >> ~/.zshrc # need to do it in another session
nvm install node

brew "sqlite"
brew "python"
brew "opencv"
brew "perl"
brew "postgresql"
brew "pyenv"
brew "pyenv-virtualenv"
brew "pyenv-virtualenvwrapper"
brew "redis"

brew "wget"

brew "heroku"

cask "cloud"
cask "firefox"
cask "flux"
cask "github-desktop"

cask "powershell"

cask "visual-studio-code"
cask "google-chrome"
cask "microsoft-office"
cask "microsoft-teams"
cask "awscli"
cask "transmit"
cask "postman"
cask "dropbox"
cask "balsamiq-mockups"


