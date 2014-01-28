# ansible-docker-rackspace

Ansible Playbooks to launch Docker in the Rackspace Cloud.

## Requirements

* Ansible 1.4+
* Pyrax

With pip:
`$ pip install ansible pyrax`

*Roles will need to be downloaded from Ansible Galaxy*

```
$ ansible-galaxy install -p . angstwad.docker_ubuntu
$ ansible-galaxy install -p . angstwad.docker_ubuntu_1204
```

## How to Use

`$ ansible-playbook docker-rackspace.yml`

Modify the values of `group_vars/all` for your account/environment.
