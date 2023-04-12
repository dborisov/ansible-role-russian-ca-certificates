# ansible-role-russian-ca-certificates
Ansible role for installing trusted CA certificates from the Ministry of Digital Development and Communications of the Russian Federation

# Supported Platforms
- RedHat 8
- RedHat 9

# Playbook Example
```
---
- hosts: all
  roles:
    - role: dborisov.russian_ca_certificates
```

# Deployment Example
```
ansible-playbook -i hosts playbooks/prod/russian-ca-certificates.yml
```
or via ad-hoc command
```
ansible localhost -m ansible.builtin.include_role -a name=dborisov.russian_ca_certificates
```

# Role Variables
None

# Dependencies
None

# License
MIT