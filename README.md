# Ansible Role: Ansible

An Ansible Role that installs Ansible on RHEL/CentOS.

## Requirements

If using on a RedHat/CentOS-based host, make sure you've added the EPEL repository (it can easily be installed by including the `mauromedda.ansible_role_epel` role on Ansible Galaxy).

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```
    - hosts: servers
      roles:
        - { role: mauromedda.ansible_role_epel }
        - { role: mauromedda.ansible_role_ansible }
```

## License

BSD

## Author Information

Mauro Medda
