# golang_hello3

### Description 

This is `main.go` app that prints `hello`

### Requirements

You need vagrant tool installed in order to use this app.
You can install it from here: [Installing vagrant](https://www.vagrantup.com/docs/installation/)

### Files
- `Vagrantfile` - this file is used in order to build DEV environment for the purpose of the app `go`
- `provision.sh` - script used from `vagrant` in order to install all needed software on the vagrant box. Script is placed into `scripts` directory
- `main.go` - source code of our application `main`
- `.gitignore` - configuration file which tell what to be ignored (not uploaded to the repository)


### Instructions
**Note that following instructions are related for Ubuntu/MAC OS**

In order to run the app `main.go` app please follow the instructions below:

1. Clone this repository to your local machine: `git clone https://github.com/berchev/golang_hello.git`
2. Type `vagrant up` in order to build the DEV Envirionment
3. Once environment is created use `vagrant ssh` in order to login.
4. Change to `/vagrant` directory: `cd /vagrant`
5. Run `main.go` app file with following command: `go run main.go`
6. If you want to use the compiled code go to: github `releases` and download `main` binary file
7. When you finish your job type `exit` in order to leave vagrant shell (Note that vagrant VM will be stay running)
8. If you want to power off vagrant VM type: `vagrant halt`
9. If vagrant environment in no longer needed type: `vagrant destroy`


### Thank you for choosing GO app !
