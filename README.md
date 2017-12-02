# ansible-role-nvidia-elrepo

RHEL/CentOS - Nvidia driver from ELRepo

## Requirements

An Nvidia graphics card supported by the EL repo

## Role Variables

None

## Dependencies

pgporada.elrepo

## Example Playbook

    ---
    - hosts: servers
      roles:
        - role: gabethecabbage.nvidia-elrepo
    ...

## License

BSD

## Author Information

This role was created by [Gabe Schrecker](https://github.com/gabethecabbage).

