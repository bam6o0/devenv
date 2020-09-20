# devenv
Virtual Machines for Development Environments.

## How to use
Create a .env file referring to the .env-example.
```
$ vagrant up
$ vagrant ssh-config >> ~/.ssh/config
```

## How to initialize
```
$ vagrant halt && vagrant destroy -f && vagrant up
```