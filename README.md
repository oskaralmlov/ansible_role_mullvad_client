mullvad_client
=========

Downloads, installs and configures the Mullvad Client.

Role Variables
--------------

Are documented in `defaults/main.yml`.

Example Playbook
----------------
```yaml
- hosts: servers
  tasks:

     - ansible.builtin.import_role:
         name: mullvad_client
```
