Ansible Sandbox
===============

Ansible Sandbox is a collection of plays that demonstrate various roles I’ve
created.

Dependencies
------------

Required roles are hosted on github and can be found at.

- jameskyle/ansible-common
- jameskyle/ansible-docker
- jameskyle/ansible-kubernetes
- jameskyle/ansible-jkyle

Example Playbooks
-----------------

Example playbooks are found in the ‘playbooks’ directory. So far, there are

jkyle
    A playbook that deploys the jkyle user and configures his home environment
    using dotfiles from a git repository.

kubernetes
    A playbook that deploys a docker + kubernetes cluster on bare metal.
    Primarily targets RHEL based systems.

License
-------

BSD

Author Information
------------------

James A. Kyle  
james@jameskyle.org  
https://github.com/jameskyle
