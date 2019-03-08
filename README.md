Ansible-provision-vagrant
-------------------------
* provision centos machines with vagrant
* Vagrantfile
* vagrant up
* vagrant ssh-config
* vagrant destroy
* netstat -vanp tcp | grep 8084
* kill -9 51858

* check the hosts file if changes required
* check the ansible.cfg
* check the hosts file

* ansible-playbook prepare-hosts-vagrant/prepare_hosts.yml
* ansible-playbook prepare-hosts-vagrant/ssh_key_distribution.yml

* creating a j2 template 
* $ grep -v ^# /etc/ssh/sshd_config > sshd_config.j2


Ansible-provision-aws
-------------------------
* todo: Provision centos machines on aws

Ansible-install-kafka
-------------------------
* todo: xxxxx

Ansible-kafka-run-tests
-------------------------
* todo: xxxxx

Ansible-kafka-security
----------------------
* todo: Plaintext
* todo: Ssl
* todo: Kerberos with CA

Ansible-kafka-components
------------------------
todo: 
* Schema-registry
* Rest-api
* Kafka-connect
* Control-center
* Promotheus
* Interceptors
* K-streams , k-sql

Optimisations
-------------
* Rework the ansible-playbook with all required roles and optimisations
* Kubernetes - docker
* Upgrade kafka to newer version
* Work with repos for different kafka versions







