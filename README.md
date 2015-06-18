
williamyeh.sudo-agent-forwarding for Ansible Galaxy
============


## Summary

Role name in Ansible Galaxy: **[williamyeh.sudo-agent-forwarding](https://galaxy.ansible.com/list#/roles/2871)**

This Ansible role has the following feature:

 - Install specific sudo setting to allow SSH agent forwarding.


If you prefer a more complete sudoers solution, try alternatives such as [franklinkim.sudo](https://galaxy.ansible.com/list#/roles/1380), [mivok0.sudo](https://galaxy.ansible.com/list#/roles/61), [Stouts.sudo](https://galaxy.ansible.com/list#/roles/842), or [mchlumsky.sudoersd](https://galaxy.ansible.com/list#/roles/4179) (a fork of [knopki.sudoers](https://galaxy.ansible.com/list#/roles/325)).




## Role Variables

None.


## Usage


### Step 1: add role

Add role name `williamyeh.sudo-agent-forwarding` to your playbook file.

You're done!


Simple example:

```yaml
---
# file: simple-playbook.yml

- hosts: all

  roles:
    - williamyeh.sudo-agent-forwarding
```


## Dependencies

None.


## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.


## History

Forked and rewritten from [knopki.sudoers](https://galaxy.ansible.com/list#/roles/325).
