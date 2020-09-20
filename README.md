# devenv
Virtual Machines for Development Environments.

## How to use
Create a .env file referring to the .env-example.
```
$ vagrant up
$ vagrant ssh-config >> ~/.ssh/config
```

## Preinstall list
+ docker
+ docker-compose
+ python3
+ pip3
+ venv
+ n
+ nodejs
+ npm
+ aws-cli
+ aws-cdk
+ aws-mfa

## How to initialize
```
$ vagrant halt && vagrant destroy -f && vagrant up
```