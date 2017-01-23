# ansible-simple-sinatra-app

## Environment Tested

* CentOS 6.8 x86_64
* Ansible 2.2.1.0

## Roles

* Disable SELinux
* Install Rbenv, Ruby & Bundler
* Install Apache
* Install Passenger
* Deploy simple-sinatra-app

## Usage

$ git clone https://github.com/buddy-joseph/ansible-simple-sinatra-app.git
$ ansible-playbook sinatra.yml -i hosts -k

## Note

* Update IP in hosts file accordingly
* Default user is root (this can be changed to another user with root privledges)