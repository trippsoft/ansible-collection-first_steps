<!-- BEGIN_ANSIBLE_DOCS -->

# Ansible Role: trippsc2.first_steps.debian
Version: 1.1.4

This role performs first steps on a freshly installed Debian system.

## Requirements

| Platform | Versions |
| -------- | -------- |
| Debian | <ul><li>bookworm</li></ul> |

## Dependencies

| Collection |
| ---------- |
| ansible.posix |

## Role Arguments
|Option|Description|Type|Required|Choices|Default|
|---|---|---|---|---|---|
| debian_install_firewalld | <p>Whether to install the firewalld package.</p> | bool | no |  | True |
| debian_install_ssl_cert | <p>Whether to install the ssl-cert package.</p> | bool | no |  | True |


## License
MIT

## Author and Project Information
Jim Tarpley (@trippsc2)
<!-- END_ANSIBLE_DOCS -->
