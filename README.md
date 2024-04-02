# nvm-insallation
Documentation, comment installer NVM, sur Mac pour profiter de toutes les meilleures foncctionnalites


# 1.Install Homebrew
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

# 2.Install nvm
brew install nvm and source $(brew --prefix nvm)/nvm.sh

# 3.Install Node.js
nvm install node

# 4. List available Node.js versions
nvm ls-remote

# 5. Install the desired version
nvm install 16

# 6.Use the installed version
 6.1. nvm use 16
 6.2. nvm alias default 16


