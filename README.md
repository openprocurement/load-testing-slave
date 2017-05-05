# load-testing-slave
## System min. requirements:
* RAM: 2GB;
* HDD: 30 GB;
* CPU: DualCore

## Requirements:
* [Vagrant](https://www.vagrantup.com/docs/getting-started/);
* [Ansible from v2.2.0.0](http://docs.ansible.com/ansible/intro.html).

## Usage:
* From directory where placed Vagrant file run command in terminal:
  ```
  vagrant up --provider=<your_provider>
  ```
  example:
  ```
  vagrant up --provider=virtualbox
  ```

More informations: https://www.vagrantup.com/docs/providers/
