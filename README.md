# ansible-docker-rackspace

Ansible Playbooks to launch Docker in the Rackspace Cloud on Ubuntu 12.04 or 13.10.

## Requirements

* Ansible 1.4+
* Pyrax

With pip:
`$ pip install ansible pyrax`

*Roles will need to be downloaded from Ansible Galaxy*

```
$ cd playbooks/
$ ansible-galaxy install -p . angstwad.docker_ubuntu
```

## Now What?

The playbooks will deploy a single Ubuntu 13.10 or 12.04 cloud instance; the naming convention should be obvious.  Modify the values of `playbooks/group_vars/all` for your account/environment, and run the appropriate playbook.  For example:

`$ ansible-playbook docker-rackspace.yml`
