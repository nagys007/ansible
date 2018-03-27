# ansible

Very simple ansible project

- Create a VM for ansible control machine using Vagrantfile
https://gist.github.com/nagys007/08397bfa56922b0fa07ec2f3536501e9

- Create another VM for ansible target machine, where nginx is going to be installed
https://gist.github.com/nagys007/72f4640dc6c0ca159a53d9e433a7762e

- `vagrant ssh` into the ansible control machine

- `git clone` this project

- change to the cloned project directory `cd ansible`

- `ansible-playbook --inventory-file inventory playbook.yml`

_nginx_ is now installed (but not yet configured/started) on target machine
