# Event-Driven Ansible CI - ead-ci

A proof of concept tool to trigger CI using [EDA](https://ansible.readthedocs.io/projects/rulebook/en/latest/)

## Requirements

Collections

```Shell
ansible-galaxy collection install ansible.eda
ansible-galaxy collection install kubealex.eda
```

Dependencies for the collections:

```Shell
pip install --user aiomqtt
```