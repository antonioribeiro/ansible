[Development Box](https://github.com/antonioribeiro/ansible)
============================================================


A Set of [Ansible](http://www.ansibleworks.com/docs/intro_installation.html) Roles and Playbooks to deploy an Ubuntu Based Development System.
----------------------------------------------------------------------------------

This system is currently PHP and **Laravel** focused, but it can easily be extended.

### In The Box

* PHP (5.5 or 5.4)
* [Composer](http://getcomposer.org/)
* [Laravel](http://laravel.com/) (a running site)
* [Artisan Anywhere](https://github.com/antonioribeiro/artisan-anywhere)
* [PHPUnit](https://github.com/sebastianbergmann/phpunit)
* [XDebug](http://xdebug.org/)
* NGINX (default) or Apache 2
* [Memcached](http://memcached.org/)
* [Redis](http://redis.io/) + [Redis Commander](https://github.com/nearinfinity/redis-commander)
* Postgres + phpPgAdmin
* MySQL + phpMyAdmin
* [Beanstalkd](http://kr.github.io/beanstalkd/) + [Beanstalkd Console](https://github.com/ptrofimov/beanstalk_console)
* [NodeJS](http://nodejs.org/)
* [Grunt](http://gruntjs.com/)
* [Fabric](http://fabfile.org/)
* [Docker](http://www.docker.io/)

### Requirements

* Ubuntu (tested on 12.04, 13.04 and 13.10)
* Ansible 1.3+

### Installing

* [Install Ansible](/docs/InstallAnsible.md) locally on your Workstation
* [Clone this repository](/docs/CloneRepository.md)
* Install [Virtualbox](https://www.virtualbox.org/) or any other virtualization system
* [Install an Ubuntu Box](/docs/InstallOS.md)
* [Create and copy your SSH Key to the box](/docs/CopySSHKey.md)
* [Configure your box](/docs/ConfigurePlaybook.md)
* [Run the Playbook](/docs/RunPlaybook.md)


* Copy your id_rsa key to your new server

### Contributing

Pull requests and issues are more than welcome.