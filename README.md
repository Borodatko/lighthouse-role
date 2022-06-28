Lighthouse-role
=========

This role download from repository and install Lighthouse.

Role Variables
--------------

There are three variables:

```yaml
git_url: https://github.com/VKCOM/lighthouse.git # Download link
www_path: /var/www/lighthouse                    # Use for clone from repostitory to this path
config_path: /etc/nginx/conf.d                   # Use for copy nginx config to this path
```

Example Playbook
----------------

An example of using role:

```yaml
- hosts: all
  roles:
    - lighthouse
```

License
-------

BSD-3-Clause

Author Information
------------------

Orlov Dmitriy

