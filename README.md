# ansible-role-nvidia-elrepo

Role uses elrepo to install binary nvidia drivers for Red Hat Enterprise Linux 6/7 derivatives.

Driver version is selected based on the output of the nvidia-detect program and therefore the role requires no variables.

## Requirements

An Nvidia graphics card supported by the EL repo

## Role Variables

None

## Dependencies

gabethecabbage.elrepo

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

