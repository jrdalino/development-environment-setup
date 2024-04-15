# My Development Environment Setup (MacOS)

- Step 1: Install https://ohmyz.sh/

- Step 2: Install Comand Line Developer Tools 
```
% xcode-select --install
```

- Step 3: Install Homebrew, Homebrew installs the latest python, pip and setuptools packages
```
$ mkdir environment && cd environment
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ brew update
$ brew doctor
```
```
% brew install python3
% pip install3 virtualenv
```

- Step 4: Install Productivity Applications
```
$ brew install --cask microsoft-office
$ brew install --cask google-backup-and-sync
$ brew install --cask google-drive
$ brew install --cask google-chrome
$ brew install --cask firefox
$ brew install --cask kindle
$ brew install --cask spotify
$ brew install --cask adobe-acrobat-reader
```

- Step 5: Install Communications
```
$ brew install --cask slack
$ brew install --cask whatsapp
$ brew install --cask zoom
$ brew install --cask skype
$ brew install --cask microsoft-teams
$ brew install --cask amazon-chime
$ brew install --cask google-chat
$ brew install --cask webex
$ brew install --cask messenger
```

- Step 6: Install Developer Tools
```
$ brew install gnupg
$ brew install git
$ brew install --cask github
$ brew install openjdk
$ brew install gradle
$ brew install node # this installs npm as well
$ brew install yarn
$ brew install --cask sublime-text
$ brew install --cask visual-studio-code
$ brew install --cask intellij-idea-ce
$ brew install --cask android-studio
$ brew install --cask postman
$ brew install --cask rancher
$ brew install --cask virtualbox
$ brew install --cask nosql-workbench-for-amazon-dynamodb
$ brew install mkdocs

```

- Step 7: Install commandline tools
```
$ brew install ansible
$ brew install terraform
$ brew install awscli
$ brew install --cask google-cloud-sdk
$ brew install azure-cli
$ brew install kubectl
$ brew install aws-iam-authenticator
$ brew install jq
$ brew install wget
$ brew install --cask ngrok
```

- Step 8: Install AWS Amplify
```
npm install -g @aws-amplify/cli
```

- Step 9: Install if/when needed
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
