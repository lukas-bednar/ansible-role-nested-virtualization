Nested Virtualization
=========

An ansible role to enable or disable nested virtualization on target system.

Requirements
------------

None

Role Variables
--------------

```yaml
---
nested_virtualization_state: enabled / disabled
```

Dependencies
------------
None

Example Playbook
----------------

```yaml
---
# Enable nested virtualization on your servers
- hosts: servers
  roles:
    - role: "nested-virtualization"

# Disable nested virtualization on your servers
- hosts: servers
  roles:
    - role: "nested-virtualization"
      nested_virtualization_state: "disabled"
```

License
-------

GPLv3

Author Information
------------------

[Lukas Bednar](https://github.com/lukas-bednar)
