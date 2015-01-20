http://www.ansibleworks.com/docs/bestpractices.html

* common
* system
* mysql
* nginx
* pagespeed
* ruby
* rails(init)
* varnish
* rbenv
* postgresql

## usage:

http://runeleaf.wordpress.com/2013/08/06/ansible-on-osx/

## settings:

```bash
 > python --version
 Python 2.7.5
 
 > easy_install virtualenv
 > virtualenv ansible-env
 > source ansible-env/bin/activate
 (ansible-env)> easy_install pip
 (ansible-env)> pip install paramiko PyYAML jinja2
 (ansible-env)> pip install ansible
 (ansible-env)> export ANSIBLE_HOSTS=~/.ansible/hosts
```

## play:

```bash
 > source ansible-env/bin/activate
 > cd ansible-playbook
 > git checkout works origin/centos-6-4-ruby-2
 (ansible-env)> ansible-playbook testserver.yml -K -vvvv -i develop
```

