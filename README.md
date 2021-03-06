# golang_hello3

### Description 

This is `main.go` app that prints `hello`

### Requirements
If you are working on OS without `go` installed, you can use vagrantbox for local development

You can install it from here: [Installing vagrant](https://www.vagrantup.com/docs/installation/)

### Files
- `Vagrantfile` - this file is used in order to build DEV environment for the purpose of the app `go`
- `scripts/provision.sh` - script that install a go environment.
- `main.go` - source code of our application `main`
- `.gitignore` - configuration file which tell what to be ignored from GitHub

### Instructions
> Note that following instructions have been tested in Ubuntu and MAC OS

In order to run the app `main.go` app please follow the instructions below:

- Clone this repository to your local machine: `git clone https://github.com/berchev/golang_hello3.git`. 
- Change directory to `project directory` placed in your current directory: `cd golang_hello3`
- Type `vagrant up` in order to build the DEV Envirionment
- Once environment is created use `vagrant ssh` in order to login.
- Change to `/vagrant` directory: `cd /vagrant`
- Run `main.go` app file with following command: `go run main.go`
- If you want to use the compiled code go to [Releases](https://github.com/berchev/golang_hello3/releases) and download `main` binary file
- When you finish your job type `exit` in order to leave vagrant shell (Note that vagrant VM will be stay running)
- If you want to power off vagrant VM type: `vagrant halt`
- If vagrant environment in no longer needed type: `vagrant destroy`


### Thank you for choosing GO app !
