
williamyeh.sudo-agent-forwarding for Ansible Galaxy
============


## Summary

Role name in Ansible Galaxy: **[williamyeh.sudo-agent-forwarding](https://galaxy.ansible.com/williamyeh/sudo-agent-forwarding/)**

This Ansible role has only one simple feature:

 - Install specific sudo setting to allow SSH agent forwarding.


If you prefer a more complete sudoers solution, try alternatives such as [franklinkim.sudo](https://galaxy.ansible.com/franklinkim/sudo/), [mivok0.sudo](https://galaxy.ansible.com/mivok0/sudo/), [Stouts.sudo](https://galaxy.ansible.com/Stouts/sudo/), or [mchlumsky.sudoersd](https://galaxy.ansible.com/mchlumsky/sudoersd/) (a fork of [knopki.sudoers](https://galaxy.ansible.com/knopki/sudoers/)).




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
  become: true
  roles:
    - williamyeh.sudo-agent-forwarding
```


## Dependencies

None.


## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.


## History

Forked and rewritten from [knopki.sudoers](https://galaxy.ansible.com/knopki/sudoers/).
