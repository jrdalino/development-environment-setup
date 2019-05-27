# MyProject Prerequisites

### Prerequisites for https://github.com/jrdalino/microservices-architecture-devsecops

- Working Directory
```
$ cd ~
$ mkdir environment
$ cd ~/environment
```

- Homebrew
```
$ brew --version
```

- AWS CLI
```
$ aws --version
$ aws configure
```

- Git
```
$ git --version
$ git config --global user.name "REPLACE_ME_WITH_YOUR_NAME"
$ git config --global user.email REPLACE_ME_WITH_YOUR_EMAIL@example.com
$ git config --global credential.helper '!aws codecommit credential-helper $@'
$ git config --global credential.UseHttpPath true
```

- Python
```
$ python3 --version
Python 3.7.3
```

- Virtualenv
```
$ virtualenv --version
16.4.3
$ echo 'venv' > .gitignore
$ python3 -m venv venv
$ source venv/bin/activate
(venv) $
(venv) $ deactivate
```

- Flask
```
(venv) $ pip install flask
(venv) $ flask --version
Flask 1.0.2
Python 3.7.3 (default, Mar 27 2019, 09:23:15) 
[Clang 10.0.1 (clang-1001.0.46.3)]
```

- Boto3
```
(venv) $ pip install boto3
```

- Docker
```
$ docker -v
Docker version 18.09.2, build 6247962
```
