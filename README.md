# ansible-role-mounts

Ansible role to manage critical mounts

This role covers the CIS requirements for:

   * /tmp
   * /var
   * /var/tmp
   * /var/log
   * /var/log/audit
   * /home
   * /dev/shm

Note:
This role will skip any mountpoint that does not exist.


## Requirements

    None


## Dependencies

    None


## Role Variables

    None


## Example playbook

    ```yaml
    ---
    - hosts: all

      roles:
          - foolean/mounts
    ```


## Compliance

    * CIS RedHat Enterprise Linux 8 Benchmark v2.0.0


## License

    BSD-3-Clause