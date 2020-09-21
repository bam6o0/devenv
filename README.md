# devenv
A virtual machine for constructing a development environment specialized for cloud development.


## How to use
Create a .env file referring to the .env-example.
```
$ git clone https://github.com/bam6o0/devenv.git
$ cd devenv
$ cp .env-example .env
// Edit .env
$ vim .env
$ vagrant up
$ vagrant ssh
// For vacode
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
+ jq

## How to initialize
```
$ vagrant halt && vagrant destroy -f && vagrant up
```
