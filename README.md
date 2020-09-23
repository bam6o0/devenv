# devenv
A virtual machine for constructing a development environment specialized for cloud development.


## How to use
###  Boot the VM
Create a .env file referring to the .env-example.
```
$ git clone https://github.com/bam6o0/devenv.git
$ cd devenv
$ cp .env-example .env
$ vim .env // Edit .env
$ vagrant up
$ vagrant ssh-config >> ~/.ssh/config // For vscode
$ vagrant ssh
```
### Authenticate AWS Cli with MFA Token.
A default profile is automatically generated using the token in `.env`.
```
$ aws-mfa
```
### 

## Preinstall list
+ ubuntu18.04
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
+ terraform
+ jq

## How to initialize
```
$ vagrant halt && vagrant destroy -f && vagrant up
```
