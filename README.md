# How-to-nstall-nvm-on-Mac
How to install nvm on Mac

# Install NVM using Homebrew

brew upgrade

brew install nvm

echo 'export NVM_DIR="$HOME/.nvm"' >> ~/.zshrc

echo '[ -s "$(brew --prefix nvm)/nvm.sh" ] && \. "$(brew --prefix nvm)/nvm.sh"' >> ~/.zshrc

echo '[ -s "$(brew --prefix nvm)/etc/bash_completion.d/nvm" ] && \. "$(brew --prefix nvm)/etc/bash_completion.d/nvm"' >> ~/.zshrc

source ~/.zshrc
 

# Verify Installation

nvm --version
