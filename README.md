# My Development Environment Setup (MacOS)

- Note: Python3, Pip3, virtualenv are already installed

- Step 1: Install Homebrew. This intalls Xcodedevelop tools
```
$ mkdir environment && cd environment
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
$ brew update
$ brew doctor
```

- Step 2: Install Productivity Applications
```
$ brew cask install microsoft-office
$ brew cask install google-backup-and-sync
$ brew cask install google-chrome
$ brew cask install firefox
$ brew cask install kindle
$ brew cask install spotify
```

- Step 3: Install Communications
```
$ brew cask install slack
$ brew cask install whatsapp
$ brew cask install wechat
$ brew cask install zoomus
$ brew cask install skype
```

- Step 4: Install Developer Tools
```
$ brew install node # this installs npm as well
$ brew cask install sublime-text
$ brew cask install visual-studio-code
$ brew cask install visual-studio
$ brew cask install postman
$ brew cask install docker
$ brew cask install virtualbox
$ brew cask install vagrant
$ brew cask install vagrant-manager
```

- Step 5: Install commandline tools
```
$ brew install git
$ brew install ansible
$ brew install terraform
$ brew install awscli
$ brew cask install google-cloud-sdk
$ brew install azure-cli
$ brew install kubectl
$ brew install aws-iam-authenticator
$ brew install jq
$ brew install wget
```

- Step 6: Install the following manually
```
- Windows Remote Desktop
- OpenVPN Client or Cisco Client VPN
```

- Step 7: Install if/when needed
```
- Serverless Framework
- AWS SAM
- AWS Amplify
- React
- Vue
- mysql client: sqlite
- bandwdth test: iperf
- network scanner: nmap
- http load testing: wrk, wrk2, ab, siege, 
```
