cloud_helper
=========

A role with helpful cloud tasks that should be run before all other roles.
All tasks (except checking to see if it is running on a cloud-init instance) are **disabled by default**.

Requirements
------------

This role has no requirements.

Role Variables
--------------

Defaults:

```yaml
    enable_cloud_wait: false
    enable_jq: false
```

Dependencies
------------

This module has no dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: insight_infra.cloud_helper }

License
-------

Apache 2.0

Author Information
------------------

Maintained by [Richard Mah](https://github.com/shinyfoil) for [Insight Infrastructure](https://github.com/insight-infrastructure)
