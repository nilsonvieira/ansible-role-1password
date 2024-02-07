# How to Install
Configure the `requirements.yml` file.
```
- name: 1password
  src: https://github.com/nilsonvieira/ansible-role-1password
  version: main
```
In the Roles include:
```
  roles:
    - 1password
```
Execute the command to install role.

```bash
ansible-galaxy role install -r requirements.yml